# Roadmap

Start date: 2026-06-21. Dates are estimates, adjust as you go, and keep build-log.md updated regardless of how the schedule shifts.

## 1. GitHub Repo - done

- [x] Repo created, public, structure in place (2026-06-21)

## 2. Planning - done

- [x] Layout decided: 65%, Orpheus Pico, MX linear switches
- [x] Extras decided: 0.91" OLED, EC11 encoder, per-key RGB (SK6812 MINI-E)
- [x] Case shape decided: rectangular, slight typing angle
- [x] BOM drafted (2026-06-21)

## 3. PCB Design in KiCad - 2026-06-22 to 2026-07-05

- [ ] Install KiCad + marbastlib
- [ ] Place schematic symbols: RaspberryPi_Pico, SW_Push, MX_stab, 1N4148
- [ ] Lay out the 65% key matrix + diodes
- [ ] Wire rows/columns to the Pico
- [ ] Add stabilizers for 2u+ keys
- [ ] Add mounting holes (tray mount)
- [ ] Annotate schematic
- [ ] Assign footprints (Pico, diodes, switches, stabilizers, OLED, encoder, LEDs)
- [ ] Route PCB (0.79375mm grid, one layer per axis, USB hanging off the edge)
- [ ] Export Gerbers + drill file, zip, commit alongside .kicad_pcb/.kicad_sch

## 4. Case Design in Onshape - 2026-07-06 to 2026-07-12

- [ ] Set up Onshape education account
- [ ] Export PCB as STEP from KiCad, import into Onshape
- [ ] Sketch bottom profile + extrude base
- [ ] Add walls
- [ ] Cut switch holes (14x14mm, 19.05mm spacing, linear pattern)
- [ ] Cut USB-C port opening
- [ ] Add screw mounts for M3 heatset inserts
- [ ] Model top plate (optional)
- [ ] Export STL for printing; STEP if anyone wants to remix

## 5. Firmware - 2026-07-13 to 2026-07-19

- [ ] Set up RMK (https://rmk.rs/docs/user_guide/guide_overview.html) (recommended by Keeb docs, Rust-based, modern) + Rust toolchain
- [ ] Configure keymap + matrix for the 65% layout
- [ ] Wire up OLED, EC11 encoder, and per-key RGB in firmware
- [ ] Build and flash to the Orpheus Pico
- [ ] Test every key, the encoder, the OLED, and RGB

## 6. Submit & Assembly - 2026-07-20 to 2026-08-02

- [ ] Order parts against the grant BOM
- [ ] Solder switches, diodes, OLED, encoder, LEDs
- [ ] 3D print case + plate, press in heatset inserts
- [ ] Assemble, flash final firmware, test
- [ ] Final photos + journal entries in build-log.md
- [ ] Submit via the Keeb submission form (https://forms.hackclub.com/t/iKhxEp4gL9us)
