# Keeb

![Hack Club](https://img.shields.io/badge/Hack%20Club-Keeb-ec3750?style=flat-square&logo=hackclub&logoColor=white)
![Status](https://img.shields.io/badge/status-in%20progress-yellow?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

A custom 65% mechanical keyboard, designed from scratch — PCB, case, and plate — for [Hack Club's Keeb](https://keeb.hackclub.com), a you-ship-we-ship program.

Built by **Ansar** ([@werquuzxc](https://github.com/werquuzxc)).

## About

This repo documents the full build of my keyboard: schematic and PCB design in KiCad, a 3D-printable case modeled in Onshape, and firmware to bring it to life. Hack Club provides a parts grant (switches, keycaps, cable); the PCB, case, and plate are designed by me.

**Spec:**

| | |
|---|---|
| Layout | 65% |
| Microcontroller | [Orpheus Pico](https://orpheuspico.hackclub.com/) |
| Switches | MX-style, linear |
| Extras | 0.91" OLED, EC11 rotary encoder, per-key RGB (SK6812 MINI-E) |
| Case | Rectangular, slight typing angle, 3D-printed |
| Firmware | [RMK](https://rmk.rs/) |

## Progress

- [x] GitHub repo set up
- [ ] - [x] Layout & parts planned
- [ ] - [ ] PCB designed in KiCad
- [ ] - [ ] Case designed in Onshape
- [ ] - [ ] Firmware written and flashed
- [ ] - [ ] Built, tested, and submitted

- [ ] See `docs/roadmap.md` for the full timeline and `docs/build-log.md` for the day-by-day journal.

- [ ] ## Parts List

- [ ] Full sourcing notes in `docs/bom.md`.

- [ ] | Part | Qty | Notes |
- [ ] |---|---|---|
- [ ] | Orpheus Pico | 1 | Microcontroller |
- [ ] | MX-style linear switches | 68 | 65% layout |
- [ ] | Through-hole 1N4148 diodes | 68 | One per switch, for the key matrix |
- [ ] | Stabilizers | ~5 | Spacebar, shifts, backspace, enter |
- [ ] | White blank DSA keycaps | 68 | |
- [ ] | 0.91" OLED display | 1 | Pin order GND-VCC-SCL-SDA, PCB footprint must match |
- [ ] | EC11 rotary encoder | 1 | |
- [ ] | SK6812 MINI-E LED | 68 | Per-key RGB |
- [ ] | M3x16mm screws | 6 | Case assembly |
- [ ] | M3x5x4mm heatset inserts | 6 | Pressed into 3D-printed case |
- [ ] | USB-C cable | 1 | Provided in grant |

- [ ] ## Repo Structure

- [ ] keeb/
- [ ] - README.md
- [ ] - LICENSE
- [ ] - docs/ (build journal, BOM, roadmap)
- [ ] - pcb/ (KiCad project: schematic, layout, Gerbers)
- [ ] - case/ (Onshape exports, STL/STEP files for the case and plate)
- [ ] - firmware/ (RMK config and keymap)

- [ ] ## Build Log

- [ ] Progress is journaled with photos every 1-4 hours of work in `docs/build-log.md`, per the Keeb docs.

- [ ] ## License

- [ ] MIT (see LICENSE) - hardware design files (PCB/case) are shared as-is for anyone who wants to remix this build.

- [ ] ---

- [ ] Built for Hack Club Keeb (https://keeb.hackclub.com) - Docs (https://keeb.hackclub.com/docs)
