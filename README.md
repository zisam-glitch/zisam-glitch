<div align="center">

<a href="https://github.com/zisam-glitch">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=38BDF8&center=true&vCenter=true&random=false&width=650&lines=Hi%2C+I'm+zisam+shaikh+%F0%9F%91%8B;Systems+%26+Concurrency+Engineer;Zero-Dependency+Runtimes+in+Rust%2C+Go%2C+TypeScript;Maintainer+of+the+kvdock+Engine+Suite" alt="Typing SVG" />
</a>

<br />

[![Developer Program Member](https://img.shields.io/badge/GitHub-Developer_Program_Member-181717?style=for-the-badge&logo=github&logoColor=white)](https://docs.github.com/developers/overview/github-developer-program)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zisamshaikh7@gmail.com)

<p align="center">
  <b>Architecting low-latency runtime primitives, zero-dependency cores, and concurrent storage engines.</b>
  <br />
  Active contributor to foundational open source across <b>Rust</b>, <b>Go</b>, <b>TypeScript</b>, <b>Swift</b>, and <b>Kotlin</b>.
</p>

---

### 🛠️ Languages & Systems Architecture

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Swift_6-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white" alt="WebAssembly" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

</div>

---

## ⚡ Flagship Projects: `kvdock` Ecosystem

`kvdock` is a universal, zero-dependency key-value and caching engine engineered natively across five languages to provide unified semantics, thread safety, and deterministic eviction policies.

| Repository | Language / Stack | Architecture & Key Features | CI / Status |
| :--- | :--- | :--- | :---: |
| **[kvdock](https://github.com/zisam-glitch/kvdock)** | `TypeScript` `Node.js` | Zero-dependency core, pluggable memory/fs adapters, sub-millisecond LRU eviction, full dual ESM/CJS build. | [![CI](https://github.com/zisam-glitch/kvdock/actions/workflows/ci.yml/badge.svg)](https://github.com/zisam-glitch/kvdock/actions) |
| **[kvdock-rs](https://github.com/zisam-glitch/kvdock-rs)** | `Rust` `Edition 2024` | Thread-safe `KVDock<A>`, zero-dependency core, mutex-guarded $O(1)$ LRU with monotonic `Instant` TTL expiration. | [![CI](https://github.com/zisam-glitch/kvdock-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/zisam-glitch/kvdock-rs/actions) |
| **[kvdock-go](https://github.com/zisam-glitch/kvdock-go)** | `Go 1.27` | Concurrent generic `Get[T]`, `Set[T]`, `GetOrSet[T]`, container/list LRU, atomic telemetry & metrics. | [![CI](https://github.com/zisam-glitch/kvdock-go/actions/workflows/ci.yml/badge.svg)](https://github.com/zisam-glitch/kvdock-go/actions) |
| **[kvdock-swift](https://github.com/zisam-glitch/kvdock-swift)** | `Swift 6.3` | Actor-isolated concurrency, `StorageAdapter` protocol, monotonic `ContinuousClock` TTL enforcement. | [![CI](https://github.com/zisam-glitch/kvdock-swift/actions/workflows/ci.yml/badge.svg)](https://github.com/zisam-glitch/kvdock-swift/actions) |
| **[kvdock-kt](https://github.com/zisam-glitch/kvdock-kt)** | `Kotlin 2.4` `JVM` | Thread-safe generic caching, access-order `LinkedHashMap` $O(1)$ LRU eviction, atomic operational telemetry. | [![CI](https://github.com/zisam-glitch/kvdock-kt/actions/workflows/ci.yml/badge.svg)](https://github.com/zisam-glitch/kvdock-kt/actions) |

---

## 🔬 Upstream Open Source Contributions

Targeting root causes with minimal diffs, zero AI signatures, and reproducible test suites:

```text
Ecosystem Contributions Summary:
├── [Rust] BurntSushi/memchr
│   └── PR #244: fix(neon): correct shift in all_zeros_except_least_significant (Fixes #219)
├── [TypeScript] DefinitelyTyped/DefinitelyTyped
│   └── PR #75860: [react] Add command and commandFor attributes to ButtonHTMLAttributes (Fixes #74664)
└── [TypeScript] sindresorhus/type-fest
    └── feat/partial-on-undefined: Add PartialOnUndefined utility type for precise object definitions
```

- **[BurntSushi/memchr #244](https://github.com/BurntSushi/memchr/pull/244)**: Fixed 64-bit Neon movemask bitshift in `all_zeros_except_least_significant` to properly zero lower lanes for $n \ge 1$.
- **[DefinitelyTyped/DefinitelyTyped #75860](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/75860)**: Added native WHATWG Invoker Commands API attributes (`command`, `commandfor`) to React `ButtonHTMLAttributes`.
- **[kvdock #31](https://github.com/zisam-glitch/kvdock/pull/31)**: Reviewed and merged community contribution verifying strict invalid TTL boundary handling in core storage.

---

## 📊 Activity & Contribution Stream

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zisam-glitch/zisam-glitch/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/zisam-glitch/zisam-glitch/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake" src="https://raw.githubusercontent.com/zisam-glitch/zisam-glitch/output/github-contribution-grid-snake.svg" width="97%" />
</picture>

<br /><br />

<img src="https://github-readme-stats.vercel.app/api?username=zisam-glitch&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zisam-glitch&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="48%" alt="Top Languages" />

<br />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=zisam-glitch&theme=tokyonight&hide_border=true" width="97%" alt="GitHub Streak" />

</div>

---

## 🏆 GitHub Developer Profile & Achievements

<div align="center">

| Achievement | Status | Description |
| :--- | :---: | :--- |
| **Developer Program Member** | 🎖️ Active | Registered member of the official GitHub Developer Program. |
| **Quickdraw** | ⚡ Unlocked | Closed an issue or pull request within 5 minutes of opening. |
| **YOLO** | 🚀 Unlocked | Merged pull request directly into default branch without review. |
| **Pair Extraordinaire** | 👥 Unlocked | Co-authored commits on merged pull requests. |
| **Pull Shark** | 🦈 Active | Merged pull requests across open-source repositories. |

</div>

---

<div align="center">

```text
"Simplicity is prerequisite for reliability." — Edsger W. Dijkstra
```

*Built with precision by [@zisam-glitch](https://github.com/zisam-glitch)*

</div>
