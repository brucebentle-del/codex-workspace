# Scalloped rear snow edges — revision 4

These are earlier side roofs. The current [left and right v13 roofs](../roof-customization-v13/README.md) have matching snow, peppermint discs, and centered windows. The center remains [rev31 v12](../roof-customization-v12/README.md), pending a test print.

This revision keeps the shallow front snow profile from v3 and gives the roof-facing edge of each front snow band a rounded scalloped outline. Both sides of the ridge snow running from front to back are scalloped as well. The narrow groove across the upper front snow band has been filled and the join rounded.

The changes stay on the cosmetic snow and its contact with the roof. Scale, orientation, the forward snow lip, mounting positions, and the functional underside are preserved within the recorded export-cleanup tolerances. The right roof matches the left using the verified reflection in `right-source-match.json`.

## Download

- [Left roof, rev10](left_roof_rev10_inner_snow_flat_scalloped_snow_v4.stl)
- [Right roof, rev10 mirrored](right_roof_rev10_inner_snow_flat_mirrored_scalloped_snow_v4.stl)
- [Center roof, rev31](center_roof_rev31_front_seams_smooth_scalloped_snow_v4.stl)
- [Center roof, rev30 alternative](center_roof_rev30_smooth_top_planes_scalloped_snow_v4.stl)

Choose one center version to print with the left and right roofs. Keep the same import units as the originals; STL does not contain unit metadata.

## Previews

- [Center roof, top](center-top-v4.png)
- [Center roof, solid gray](center-top-solid-v4.png)
- [Center roof, front](center-front-v4.png)
- [Left roof, top](left-top-v4.png)
- [Right roof, top](right-top-v4.png)

The previews use the saved STL geometry. White in the colored views identifies the intended snow region. Each STL is one uncolored fused model.

## Checks and limits

`mesh-validation.json` records the exported mesh checks, file hashes, and construction details. `surface-validation.json` compares mounting surfaces and the functional underside with the original uploads, and the forward snow lip with the accepted v3 files. It also records the depth of the old front groove and the revised surface at the same probe positions.

The added groove fill sits above the roof surface. The rear snow is refined before shaping so the scallops have smooth curves. The cosmetic cap is resolved separately on a 0.25-model-unit grid, smoothed, and simplified before being fused to the protected v3 front and functional roof body. Export cleanup uses a 0.001-model-unit tolerance. These distances are millimeters if the originals are imported in millimeters.

Mounting and functional-underside checks use a tolerance of 0.01 model units. Forward-lip checks use 0.02; the largest measured forward-lip difference is about 0.0125 at a small side-roof crown seam affected by numerical cleanup. Closest-point results above 0.008 are rechecked in double precision to avoid numerical errors on long, thin triangles. These are sampled checks of the saved files. Physical slicing, printing, and clearance against any separate holly-trim STL have not been tested.

Earlier revisions remain in their own folders.
