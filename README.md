# Light Overlay (F7) for Horizon

A native Rust mixin port of **Light Overlay** and **MiniHUD Light Level Overlay (F7)** for [Horizon](https://github.com/horizon-rust/horizon) (Minecraft: Java Edition 26.3), created by **CayMac**.

## Features (1:1 Java Mod Parity)

- **Instant `F7` Toggle Keybind:** Press `F7` at any time during gameplay to toggle the 3D mob-spawn light overlay on or off.
- **Color-Coded Spawn Safety:**
  - **Red (`X` / `0`):** Hostile mobs can spawn **at any time** (Block Light `<= threshold` and Sky Light `<= threshold`, e.g. caves or roofed areas).
  - **Yellow (`X` / `0`):** Hostile mobs can spawn **at night or during thunderstorms** (Block Light `<= threshold` and Sky Light `> threshold`).
  - **Green (`1`–`15`):** Safe from hostile mob spawns (optional in Numbers mode).
- **3 Display Modes:**
  - **Crosses (`X`):** Classic 3D `X` markers rendered directly on the top surface of spawnable blocks.
  - **Numbers (`0`–`15`):** Crisp 3D vector numbers rendered flat on block tops.
  - **Crosses + Numbers:** Combines both `X` markers and block light level numbers.
- **Configurable Scan Radius & Threshold:** Supports `8`, `12`, `16`, or `20` block radius and both Modern (`Block Light == 0`) and Legacy (`Block Light <= 7`) spawn thresholds.

## License

MIT — Copyright (c) 2026 CayMac
