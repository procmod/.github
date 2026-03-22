# procmod

Composable runtime game instrumentation primitives for Rust. Process memory, pattern scanning, function hooking, struct mapping, and overlay rendering - each as a focused, independent crate that composes cleanly with the others.

The existing Rust landscape for game modding is fragmented: stale crates, C FFI wrappers, platform-locked tools, and abandoned frameworks. procmod fills the gaps with pure-Rust, well-tested, well-documented crates that work together but don't depend on each other unnecessarily.

## Crates

| Crate | Description |
|-------|-------------|
| [`procmod-core`](https://github.com/procmod/procmod-core) | Cross-platform process memory read/write |
| [`procmod-scan`](https://github.com/procmod/procmod-scan) | Pattern and signature scanning with SIMD acceleration |
| `procmod-layout` | Struct mapping with pointer chain traversal via derive macros |
| `procmod-hook` | Inline function hooking and detouring |
| `procmod-overlay` | Game overlay rendering |

---

This ecosystem is an experiment in AI-maintained open source. All crates are autonomously built, tested, and refined by AI with human oversight. Regular audits, thorough test coverage, continuous refinement. The emphasis is on high quality, rigorously tested, production-grade code - not a toy experiment.
