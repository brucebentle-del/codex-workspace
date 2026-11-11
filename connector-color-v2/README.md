# Raised front candy-cane connector (color v2)

V2 converts the red spiral on the approved **front connector rev85** from color-only bands into real raised geometry. The Candy Red bands project approximately **0.8 mm** above the recessed White Silk surface. The Champagne attachment rail and tabs retain the approved fit geometry.

## 3MF downloads

- [Front connector rev85 with raised red spiral](https://raw.githubusercontent.com/brucebentle-del/codex-workspace/refs/heads/main/connector-color-v2/front_candy_cane_rev85_raised_color_v2.3mf)
- [Unchanged flat rear connector rev86](https://raw.githubusercontent.com/brucebentle-del/codex-workspace/refs/heads/main/connector-color-v1/flat_rear_connector_rev86_champagne_v1.3mf)

Keep both models at 100% scale in millimeters. In Bambu Studio, map Champagne Silk, White Silk, and Candy Red Silk to the corresponding AMS slots.

![Raised connector preview](connector-raised-color-preview-v2.png)

![Raised spiral close-up](raised-spiral-detail-v2.png)

## Geometry

- Nominal red-band relief: **0.8 mm**
- Measured maximum relief: **0.7997 mm**
- Spiral pitch: **39.15 mm**
- Height: **156.6 mm**, unchanged
- Rear attachment extent: **23.5 mm**, unchanged
- Approved source bounds: `139.0…173.0 × -17.0…23.5 × 0…156.6 mm`
- Raised bounds: `138.201…173.796 × -17.800…23.5 × 0…156.6 mm`

The increased X and front-Y extents belong only to the visible rounded spiral relief. The attachment rail, tabs, rear depth, top plane, and bottom plane remain in their approved locations.

## Color mapping

- **Candy Red Silk PLA** (`#D71920`): raised spiral bands and red end pattern
- **White Silk PLA** (`#F7F5EE`): recessed bands and white end pattern
- **Champagne Silk PLA** (`#C89A6B`): attachment rail and tabs

## Validation

- One fused, watertight, consistently wound, positive-volume solid
- Standard 3MF Core 1.0 archive with Materials Extension
- Explicit material assignment on every triangle
- 3MF reopens with **0 mm** bounds error and **0 mm³** volume error

See [3mf-validation-report.json](3mf-validation-report.json) for the source checksum, exact dimensions, material counts, and reopen checks.
