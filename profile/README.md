# amigo-labs

Personal organization for projects around **Rust, TypeScript, and performance**.

## Repositories

| Repository | Description | Stack |
|---|---|---|
| **[amigo-downloader](https://github.com/amigo-labs/amigo-downloader)** | Fast, modular download manager with a responsive web UI, a TypeScript plugin system, and native apps. Multi-chunk parallel downloads, built-in extractors, Usenet (NZB/NNTP/yEnc), Click'n'Load, REST + WebSocket API, single self-updating binary. | Rust · Svelte 5 · Tauri v2 |
| **[amigo-native](https://github.com/amigo-labs/amigo-native)** | Rust-powered native Node.js packages — native-performance replacements for common JS utilities. | Node.js · Rust · napi-rs · MIT |
| **[amigo-fineliner](https://github.com/amigo-labs/amigo-fineliner)** | Image editor with a Rust core — layers, 12 blend modes in linear light, multi-format codecs (PNG/JPEG/WebP/BMP/GIF/TIFF), undo/redo, Svelte 5 UI over a WASM boundary. | Rust · WASM · Svelte 5 |
| **[amigo-pincel](https://github.com/amigo-labs/amigo-pincel)** | A pixel-art editor for the web. | Rust · WASM |
| **[amigo-trommel](https://github.com/amigo-labs/amigo-trommel)** | TypeScript-native game-audio authoring tool. Sample-based voices, a Strudel pattern system. DSP runs in Rust; JS only triggers voices. | Svelte 5 · Rust/WASM · QuickJS-NG · Tauri v2 |
| **[amigo-engine](https://github.com/amigo-labs/amigo-engine)** | Pixel-art game engine with a built-in editor, AI asset generation, and algorithmic chiptune music. | Rust · ECS · wgpu · TidalCycles |
| **[amigo-metropolis](https://github.com/amigo-labs/amigo-metropolis)** | Browser-based arena strategy-action game — a mechanics homage to the *Precinct Assault* mode of *Future Cop: L.A.P.D.* (1998), reusing none of the original's IP. One deterministic lockstep simulation drives solo, couch-splitscreen, and online 1v1 play. | TypeScript |

## Common stack

- **Core / performance** — Rust, compiled to WASM for the web and natively for desktop
- **Frontend** — Svelte 5 + Tailwind, PWA-first
- **Desktop** — Tauri v2
- **Native bindings** — napi-rs (Node.js), QuickJS-NG via rquickjs (embedded JS)
- **Build** — SWC for TypeScript, Cargo workspaces

---

*7 public repositories · Last updated July 2026*
