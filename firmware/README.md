# Firmware

Firmware config and keymap go here.

The current [Keeb docs](https://keeb.hackclub.com/docs/firmware) recommend **[RMK](https://rmk.rs/docs/user_guide/guide_overview.html)** (Rust-based) over QMK/KMK — it's what's actively supported for the Orpheus Pico build. If you'd rather use QMK/KMK, that still works on RP2040-based boards, but expect less direct guidance from the docs.

Steps: set up RMK CLI + Rust (or use GitHub Actions to build), configure keymap + matrix for the 65% layout, wire up OLED/encoder/RGB, compile, flash to the Orpheus Pico.
