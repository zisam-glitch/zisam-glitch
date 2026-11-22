# Zisam Shaikh

[![Follow @zisam-glitch](https://img.shields.io/github/followers/zisam-glitch?label=Follow%20%40zisam-glitch&style=for-the-badge&logo=github)](https://github.com/zisam-glitch)
[![Star kvdock](https://img.shields.io/github/stars/zisam-glitch/kvdock?label=Star%20kvdock&style=for-the-badge&logo=github)](https://github.com/zisam-glitch/kvdock)
[![Dev.to Blog](https://img.shields.io/badge/Dev.to-%40zisamglitch-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/zisamglitch)
[![Interactive Playground](https://img.shields.io/badge/Playground-Stampede_Simulator-38BDF8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://zisam-glitch.github.io/kvdock/playground/index.html)

Systems & Infrastructure Engineer · Author of [kvdock](https://github.com/zisam-glitch/kvdock)  
[Email](mailto:zisamshaikh7@gmail.com) · [Dev.to (@zisamglitch)](https://dev.to/zisamglitch) · [Documentation & Live Simulator](https://zisam-glitch.github.io/kvdock/)

---

### Focus
Architecting zero-dependency runtimes, thread-safe memory models, and deterministic storage primitives. Primary maintainer of the `kvdock` cross-language ecosystem across Rust, Go, TypeScript, Swift, and Kotlin.

> 👤 **Follow [@zisam-glitch on GitHub](https://github.com/zisam-glitch)** for weekly deep dives into zero-dependency systems programming, single-flight concurrency, and distributed caching architecture.

---

### ⚡ Flagship Project: `kvdock`

> ⭐ **Primary Flagship Repository:** [**zisam-glitch/kvdock**](https://github.com/zisam-glitch/kvdock) [![GitHub Repo stars](https://img.shields.io/github/stars/zisam-glitch/kvdock?style=social)](https://github.com/zisam-glitch/kvdock) — Universal zero-dependency caching engine with single-flight stampede coalescing & multi-tier L1/L2 storage. **[Star `kvdock` on GitHub ★](https://github.com/zisam-glitch/kvdock)**

A universal, zero-dependency key-value and caching engine engineered natively across five languages with unified semantics, strict thread safety, and deterministic eviction.

| Runtime | Language / Target | Architecture | Status |
| :--- | :--- | :--- | :---: |
| [**kvdock**](https://github.com/zisam-glitch/kvdock) | `TypeScript` `Node.js` | Zero-dependency core, pluggable storage fleet (20+ adapters), stampede protection | [![npm](https://img.shields.io/npm/v/kvdock.svg?style=flat-square)](https://www.npmjs.com/package/kvdock) [![CI](https://github.com/zisam-glitch/kvdock/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock/actions) |
| [**kvdock-rs**](https://github.com/zisam-glitch/kvdock-rs) | `Rust 2024` | Zero-dependency core, mutex-guarded $O(1)$ LRU, monotonic `Instant` TTL | [![CI](https://github.com/zisam-glitch/kvdock-rs/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock-rs/actions) |
| [**kvdock-go**](https://github.com/zisam-glitch/kvdock-go) | `Go 1.27` | Concurrent generic `Get[T]`, container/list LRU, atomic operational telemetry | [![CI](https://github.com/zisam-glitch/kvdock-go/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock-go/actions) |
| [**kvdock-swift**](https://github.com/zisam-glitch/kvdock-swift) | `Swift 6.3` | Actor-isolated concurrency, monotonic `ContinuousClock` TTL enforcement | [![CI](https://github.com/zisam-glitch/kvdock-swift/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock-swift/actions) |
| [**kvdock-kt**](https://github.com/zisam-glitch/kvdock-kt) | `Kotlin / JVM` | Thread-safe generic caching, access-order `LinkedHashMap` $O(1)$ LRU | [![CI](https://github.com/zisam-glitch/kvdock-kt/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock-kt/actions) |

---

### 📝 Latest Engineering Articles & Deep-Dives
<!-- BLOG-POST-LIST:START -->
- [Sub-Millisecond Route & Eden Treaty Caching in Bun, Elysia.js, and Hono](https://dev.to/zisamglitch/sub-millisecond-route-eden-treaty-caching-in-bun-elysiajs-and-hono-59hp)
- [Benchmarking TypeScript KV & Cache Engines in 2026: KVDock vs. Unstorage vs. Keyv](https://dev.to/zisamglitch/benchmarking-typescript-kv-cache-engines-in-2026-kvdock-vs-unstorage-vs-keyv-4ab1)
- [Cut OpenAI & Vercel AI SDK Token Costs by 70% with Deterministic Prompt Caching](https://dev.to/zisamglitch/cut-openai-vercel-ai-sdk-token-costs-by-70-with-deterministic-prompt-caching-1hph)
- [Next.js 15 Custom Cache Handler: Self-Host ISR with L1 RAM + L2 Redis & Stop Cache Stampedes](https://dev.to/zisamglitch/nextjs-15-custom-cache-handler-self-host-isr-with-l1-ram-l2-redis-stop-cache-stampedes-3533)
- [Zero-Dependency Architecture: Why We Built KVDock with 0 External Dependencies](https://dev.to/zisamglitch/zero-dependency-architecture-why-we-built-kvdock-with-0-external-dependencies-50fj)
- [Building a Zero-Dependency Key-Value Engine in 5 Languages (Rust, Go, TypeScript, Swift, Kotlin)](https://dev.to/zisamglitch/building-a-zero-dependency-key-value-engine-in-5-languages-rust-go-typescript-swift-kotlin-3gp4)
<!-- BLOG-POST-LIST:END -->

---

### 🔬 Foundational Open Source Contributions
Targeting memory bounds, vector instruction safety, and protocol specifications:

* **[BurntSushi/aho-corasick #190](https://github.com/BurntSushi/aho-corasick/pull/190)** (Rust) — Documented panic boundary on `Bound::Excluded(usize::MAX)` in `Input::range` with regression test suite.
* **[BurntSushi/memchr #244](https://github.com/BurntSushi/memchr/pull/244)** (Rust) — Corrected 64-bit ARM Neon movemask bitshift in `all_zeros_except_least_significant`.
* **[square/okhttp #9837](https://github.com/square/okhttp/pull/9837)** (Kotlin) — Standardized DNS lookup error handling to raise `UnknownHostException` with preserved cause.
* **[DefinitelyTyped/DefinitelyTyped #75860](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/75860)** (TypeScript) — Implemented WHATWG Invoker Commands API (`command`, `commandfor`) for React `ButtonHTMLAttributes`.
* **[kvdock #31](https://github.com/zisam-glitch/kvdock/pull/31)** — Community PR review & merge: verified strict invalid TTL boundary enforcement in core storage.

---

```text
"Simplicity is prerequisite for reliability." — Edsger W. Dijkstra
```
