# Project 01 — Face / Pocket / Contour

## Software
Fusion 360

## Setup
- Units: mm
- Work coordinate: Stock top

## Tool
- Type: Flat end mill
- Diameter: 3 mm
- Tool length selected to safely reach pocket depth

## Material
Training material (learning setup)

## Toolpaths

### Face
- Purpose: Stock leveling
- Stepover: ~60%
- Direction: Both ways

### Pocket
- Strategy: 2D Pocket
- Stepdown: 1 mm
- Entry: Ramp
- Stock to leave: 0
- Conservative parameters used intentionally for safe learning

### Contour
- Strategy: 2D Contour
- Multiple depths enabled
- Finish pass: 0.2–0.3 mm
- Climb milling

## Simulation
- Full toolpath simulation completed
- Tool, holder, and stock visibility enabled
- No collisions detected

## Notes
Small stepdown and conservative parameters were used intentionally to minimize tool load and reduce the risk of tool breakage during learning.