# Project notes for the AI

This is a Rust project (toolchain stable-x86_64-pc-windows-gnu, no Visual Studio).
- Run: `cargo run`
- Add a crate: `cargo add <name>`. Avoid crates that need a C/C++ compiler, CMake or Visual Studio.
- Window apps use eframe/egui with `default-features = false, features = ["default_fonts", "glow"]`.

This school computer cannot install software. Use only the portable tools on PATH and keep every file inside this folder.
