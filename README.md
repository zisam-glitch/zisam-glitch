# Zisam Shaikh

Systems & Infrastructure Engineer · Author of [kvdock](https://github.com/zisam-glitch/kvdock)  
[Email](mailto:zisamshaikh7@gmail.com) · [LinkedIn](https://linkedin.com) · [Documentation](https://zisam-glitch.github.io/kvdock/)

---

### Focus
Architecting zero-dependency runtimes, thread-safe memory models, and deterministic storage primitives. Primary maintainer of the `kvdock` cross-language ecosystem across Rust, Go, TypeScript, Swift, and Kotlin.

---

### ⚡ Flagship Project: `kvdock`
A universal, zero-dependency key-value and caching engine engineered natively across five languages with unified semantics, strict thread safety, and deterministic eviction.

| Runtime | Language / Target | Architecture | Status |
| :--- | :--- | :--- | :---: |
| [**kvdock**](https://github.com/zisam-glitch/kvdock) | `TypeScript` `Node.js` | Zero-dependency core, pluggable storage fleet (20+ adapters), stampede protection | [![npm](https://img.shields.io/npm/v/kvdock.svg?style=flat-square)](https://www.npmjs.com/package/kvdock) [![CI](https://github.com/zisam-glitch/kvdock/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock/actions) |
| [**kvdock-rs**](https://github.com/zisam-glitch/kvdock-rs) | `Rust 2024` | Zero-dependency core, mutex-guarded $O(1)$ LRU, monotonic `Instant` TTL | [![CI](https://github.com/zisam-glitch/kvdock-rs/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock-rs/actions) |
| [**kvdock-go**](https://github.com/zisam-glitch/kvdock-go) | `Go 1.27` | Concurrent generic `Get[T]`, container/list LRU, atomic operational telemetry | [![CI](https://github.com/zisam-glitch/kvdock-go/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock-go/actions) |
| [**kvdock-swift**](https://github.com/zisam-glitch/kvdock-swift) | `Swift 6.3` | Actor-isolated concurrency, monotonic `ContinuousClock` TTL enforcement | [![CI](https://github.com/zisam-glitch/kvdock-swift/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock-swift/actions) |
| [**kvdock-kt**](https://github.com/zisam-glitch/kvdock-kt) | `Kotlin / JVM` | Thread-safe generic caching, access-order `LinkedHashMap` $O(1)$ LRU | [![CI](https://github.com/zisam-glitch/kvdock-kt/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/zisam-glitch/kvdock-kt/actions) |

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
