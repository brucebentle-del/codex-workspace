# Center rev31 — smooth transitions and rounded tips (v5)

This earlier revision contains the rev31 center roof. The current touchup is [rev31 v6](../roof-customization-v6/README.md).

- Smooth roof planes replace the rough remnants beside both sides of the lengthwise snow ridge. The snow contact blends into the roof.
- The rear snow termination rounds down over the final 7 model units and meets the existing rear edge, removing the cut-face rim without increasing roof depth.
- Both front snow tips round over with fuller, convex ends. The snow extends approximately 1.6 model units farther outward at each tip; overall width is approximately 245.1 model units.
- Original scale, orientation, mounting geometry, underside, front decoration, and the approved main front snow profile are retained. The intentionally rounded tips are excluded from the front-profile comparison.

Center file:

- [Center rev31](center_roof_rev31_front_seams_smooth_smooth_roof_rounded_tips_v5.stl)

Use this with the existing [left roof v4](../roof-customization-v4/left_roof_rev10_inner_snow_flat_scalloped_snow_v4.stl) and [right roof v4](../roof-customization-v4/right_roof_rev10_inner_snow_flat_mirrored_scalloped_snow_v4.stl).

## Previews

These solid-gray renders use the exported rev31 mesh. They show geometry without decorative color assignments.

- [Rear view](center-rear-v5.png)
- [Rear ridge close-up](center-rear-detail-v5.png)
- [Left front tip](center-left-tip-v5.png)
- [Right front tip](center-right-tip-v5.png)
- [Front view](center-front-v5.png)

## Validation

The saved STL was reloaded and checked for a watertight mesh, consistent winding, positive volume, and one connected material part. Mesh hashes and bounds are recorded in [mesh-validation.json](mesh-validation.json).

Surface samples compare the original mounting surfaces and functional underside within 0.01 model units, and the v4 main front snow lip and front decoration within 0.02 model units. Bare-roof probes on both sides of the ridge must be within 0.005 model units of their fitted planes. Cross-section checks reject secondary ridges above 0.04 model units. Results and sample counts are in [surface-validation.json](surface-validation.json).

Local connectivity repair separates coincident vertex fans at sub-print precision where needed. The model body was not globally remeshed. These are mesh and surface checks; physical printing and assembly have not been tested.

STL stores no units or color. Import using the same unit convention as the original files.
