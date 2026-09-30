# Knobby

A 9-key macropad with a rotary encoder, built for my editing shortcuts. Custom PCB and 3D-printed case.

Made for Half Life (warm-up project, design submission, Tier 1).

## Features

- 3x3 hot-swap key matrix (Cherry MX style)
- 1 rotary encoder with push button (volume, timeline scrub, zoom)
- Seeed XIAO RP2040 microcontroller, native USB
- Custom 2-layer PCB designed in KiCad
- 3D-printed two-part case
- Firmware: KMK (CircuitPython)

## Bill of materials

| Part | Qty | Approx. cost |
|------|-----|--------------|
| Seeed XIAO RP2040 | 1 | $6 |
| MX-style switches | 9 | $4 |
| MX hot-swap sockets | 9 | $2 |
| Keycaps | 9 | $4 |
| EC11 rotary encoder | 1 | $2 |
| 1N4148 diodes | 9 | $1 |
| Custom PCB | 1 | $8 |
| 3D-printed case | 1 | $0 |
| Screws and standoffs | 1 set | $1 |

Estimated total: about $28. Prices are estimates, to be confirmed in the final parts list.

## Key layout

```
[ 1 ] [ 2 ] [ 3 ]        Encoder: turn = scrub timeline
[ 4 ] [ 5 ] [ 6 ]                 press = play / pause
[ 7 ] [ 8 ] [ 9 ]
```

Default shortcuts (editing):

| Key | Action |
|-----|--------|
| 1 | Undo |
| 2 | Redo |
| 3 | Save |
| 4 | Cut / split |
| 5 | Copy |
| 6 | Paste |
| 7 | Zoom in |
| 8 | Zoom out |
| 9 | Export |

## Repo layout

```
/pcb        KiCad schematic and PCB files
/cad        Case models (STEP and STL)
/firmware   KMK keymap and config
/images     Schematic, PCB, and case renders
README.md
```

## Status

- [ ] Schematic
- [ ] PCB layout
- [ ] Case design
- [ ] Firmware keymap
- [ ] Parts list finalized
- [ ] Journal complete

## Build notes

Progress is logged in the project journal on Half Life.

## License

MIT
