# One-File Game Base (HTML + WASM-ready)

This is a **single-file HTML game foundation** with:
- Fullscreen `<canvas>` + HiDPI scaling
- Fixed timestep loop (smooth physics)
- Keyboard + pointer/touch input
- Web Audio API for simple SFX
- LocalStorage saves
- **WASM hook** for high-performance simulation
- Inline README for quick reference

## Quick Start
1. Open `index.html` in your browser to run the demo.
2. Edit `index.html` directly — all code is inside.
3. To add WASM:
   - Compile your `.wasm` from Rust/C/C++.
   - Base64 encode it.
   - Paste into the `WASM_BASE64` variable in `index.html`.

## Development Tips
- Use a local HTTP server for testing (e.g. `python -m http.server`).
- Keep the WASM<->JS interface minimal and batch data where possible.
- Procedural generation over large assets to keep file small.

## License
MIT — use freely, modify, and share.
