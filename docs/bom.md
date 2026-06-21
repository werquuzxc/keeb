# Bill of Materials - Keeb (65%, Orpheus Pico)

Per Hack Club Keeb's Grants model (https://keeb.hackclub.com/docs/kit-contents): instead of shipping a fixed kit, Hack Club gives a grant against this BOM. Buy the cheapest reliable source for each part.

| Part | Qty | Notes | Source |
|---|---|---|---|
| Orpheus Pico | 1 | Microcontroller, RP2040-based | https://orpheuspico.hackclub.com/ |
| MX-style linear switches | 68 | 65% layout key count | https://www.aliexpress.us/item/3256802192387196.html |
| Through-hole 1N4148 diodes | 68 | One per switch, needed for the row/column key matrix | https://www.aliexpress.com/w/wholesale-diode-1n4148.html |
| Stabilizers | ~5 | For spacebar (6.25u), both shifts, backspace, enter | - |
| White blank DSA keycaps | 68 | | - |
| 0.91 inch OLED display | 1 | Pin order GND-VCC-SCL-SDA, PCB footprint must match | https://www.aliexpress.us/item/2251832650376908.html |
| EC11 rotary encoder | 1 | 15/20mm | https://www.alibaba.com/product-detail/EC11-rotary-15-20mm-Meihua-Bing_1600985459709.html |
| SK6812 MINI-E LED | 68 | Per-key RGB; $5.55 if ordered as a full reel | https://www.lcsc.com/product-detail/C5149201.html |
| M3x16mm screws | 6 | Case top/bottom assembly | - |
| M3x5x4mm heatset inserts | 6 | Pressed into 3D-printed bosses with a soldering iron | https://www.aliexpress.us/item/2255800046543591.html |
| USB-C cable | 1 | Provided in the grant | - |

## Notes

- Quantities assume a standard ~68-key 65% layout (alphas, modifiers, arrow cluster, a few nav keys). Adjust if the final layout sketch changes.
- - Footprints/symbols for most of these parts already exist in default KiCad libraries or marbastlib (https://github.com/ebastler/marbastlib); fall back to SnapEDA (https://www.snapeda.com/) or Component Search Engine (https://componentsearchengine.com/) if not.
  - - 3D models for case design: check GrabCAD (https://grabcad.com/library) before modeling parts from scratch.
    - - Keep the BOM as cheap as possible, Hack Club explicitly asks for this, and other parts can be self-sourced if cheaper.
