# Image manifest

All images used by the README are final.

## Schematics — rendered from the KiCad source in this repo

| File | Source |
|------|--------|
| `transmitter-schematic.png` | `hardware/transmitter/transmitter.kicad_sch` |
| `receiver-schematic.png` | `hardware/receiver/receiver.kicad_sch` |

## Simulation plots — exported from LTspice

Stored under [`../../simulations/results/`](../../simulations/results/):
`transmitter_biased_voltage_output.png`, `transmitter_led_drive_current.png`,
`response_optimal_8.2pF.png` (from `simulations/transmitter.asc` and
`simulations/receiver.asc`).

## Photographs and captures

| File | Shows |
|------|-------|
| `hero.png` | 3D-printed transmitter and receiver enclosures |
| `concept-audio-photo.png` | Rejected concept: still image encoded as audio (SSTV pattern) |
| `composite-video-output.png` | Composite Video (CVBS) analog output connector |
| `system-architecture.png` | End-to-end signal pipeline block diagram |
| `transmitter-scope.png` | LTspice/scope — biased video signal driving the laser |
| `receiver-scope.png` | LTspice/scope — recovered signal / frequency response |
