# procmod

Composable runtime game instrumentation primitives for Rust. Process memory, pattern scanning, function hooking, struct mapping, and overlay rendering - each as a focused, independent crate that composes cleanly with the others.

The existing Rust landscape for game modding is fragmented: stale crates, C FFI wrappers, platform-locked tools, and abandoned frameworks. procmod fills the gaps with pure-Rust, well-tested, well-documented crates that work together but don't depend on each other unnecessarily.

## Crates

| Crate | Test | Version | Description |
|-------|------|---------|-------------|
| [`procmod-core`](https://github.com/procmod/procmod-core) | ![test](https://github.com/procmod/procmod-core/actions/workflows/test.yml/badge.svg) | [![crates.io](https://img.shields.io/crates/v/procmod-core)](https://crates.io/crates/procmod-core) | Cross-platform process memory read/write |
| [`procmod-scan`](https://github.com/procmod/procmod-scan) | ![test](https://github.com/procmod/procmod-scan/actions/workflows/test.yml/badge.svg) | [![crates.io](https://img.shields.io/crates/v/procmod-scan)](https://crates.io/crates/procmod-scan) | Pattern and signature scanning with SIMD acceleration |
| [`procmod-layout`](https://github.com/procmod/procmod-layout) | ![test](https://github.com/procmod/procmod-layout/actions/workflows/test.yml/badge.svg) | [![crates.io](https://img.shields.io/crates/v/procmod-layout)](https://crates.io/crates/procmod-layout) | Struct mapping with pointer chain traversal via derive macros |
| [`procmod-hook`](https://github.com/procmod/hook) | ![test](https://github.com/procmod/hook/actions/workflows/test.yml/badge.svg) | [![crates.io](https://img.shields.io/crates/v/procmod-hook)](https://crates.io/crates/procmod-hook) | Inline function hooking and detouring |
| [`procmod-overlay`](https://github.com/procmod/overlay) | ![test](https://github.com/procmod/overlay/actions/workflows/test.yml/badge.svg) | [![crates.io](https://img.shields.io/crates/v/procmod-overlay)](https://crates.io/crates/procmod-overlay) | Game overlay rendering with transparent click-through windows |

---

This ecosystem is an experiment in AI-maintained open source. All crates are autonomously built, tested, and refined by AI with human oversight. Regular audits, thorough test coverage, continuous refinement. The emphasis is on high quality, rigorously tested, production-grade code - not a toy experiment.
