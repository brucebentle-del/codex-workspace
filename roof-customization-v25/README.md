# Center rev31 — reinforced ribbon tails and attached holly (v25)

This revision addresses the two print defects found in the v12 test print. The two downward ribbon tails now contain concealed solid support cores that close the small terminal holes and overlap the original ribbon. Their visible folded faces and V-shaped ends are retained. The recessed left and right bow loops are unchanged.

A concealed 3.1 mm contact layer now follows the complete holly footprint. It overlaps both the facade and the existing leaves, stems, and berries, closing the air gap under the garland while preserving the visible leaf shapes.

## Download

- [Center rev31 v25 STL](https://raw.githubusercontent.com/brucebentle-del/codex-workspace/refs/heads/main/roof-customization-v25/center_roof_rev31_solid_ribbon_tails_anchored_holly_v25.stl)
- [Unchanged left roof v24](https://raw.githubusercontent.com/brucebentle-del/codex-workspace/refs/heads/main/roof-customization-v24/left_roof_rev10_center_style_snow_peppermint_v24.stl)
- [Unchanged right roof v24](https://raw.githubusercontent.com/brucebentle-del/codex-workspace/refs/heads/main/roof-customization-v24/right_roof_rev10_center_style_snow_peppermint_v24.stl)

The STL uses millimeters and is one fused, watertight part.

## Previews

The previews show the exported STL in one neutral material.

![Center roof](center-front-solid-v25.png)

- [Reinforced ribbon-tail detail](ribbon-tail-detail-v25.png)
- [Holly-to-facade contact detail](holly-contact-detail-v25.png)

## Validation

[Mesh validation](mesh-validation.json) records the source and finished checksums, 1,789,884 triangles, watertightness, consistent winding, and one positive connected component.

[Contact validation](contact-validation.json) measures positive overlap between the new holly backing and both the v12 roof body and green holly construction. It also measures positive overlap between the concealed tail supports, the roof body, and the original bow. The supports stop below Z=87 mm, outside the retained upper loop reference zone.

[Print-fix dimensions](print-fix-dimensions.json) record the 3.1 mm holly contact depth and the concealed ribbon-support placement. Physical printing remains the final verification step.
