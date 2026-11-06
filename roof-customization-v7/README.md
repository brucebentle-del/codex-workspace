# Center rev31 — peppermint and snow-join touchup (v7)

This is an earlier version. The current [rev31 v8](../roof-customization-v8/README.md) reduces the peppermint by 25% and restyles the sign to match the reference.

This revision starts from rev31 v6. It smooths the two creases on the raised snow shoulders where the front drift meets the ridge, and adds the peppermint disc at the front gable peak. The snow scallops and the previously rounded front tips are retained.

## Download

[Download the fused rev31 STL](https://github.com/brucebentle-del/codex-workspace/raw/refs/heads/main/roof-customization-v7/center_roof_rev31_peppermint_smooth_snow_v7.stl)

This is one closed, fused material part. Rev31 is the only center version in the current downloads. The left and right roofs remain at v4: [left](../roof-customization-v4/left_roof_rev10_inner_snow_flat_scalloped_snow_v4.stl), [right](../roof-customization-v4/right_roof_rev10_inner_snow_flat_mirrored_scalloped_snow_v4.stl).

## Peppermint

The disc is 46 model units across (46 mm at the original millimeter import scale), centered on the gable, with a 2.5-unit rounded rim and eight curved spiral arms raised 0.65 units above its front face. Its back overlaps the snow peak and is Boolean-fused into the same solid. The disc faces forward and naturally covers the small peak area behind its attachment.

Scale and orientation of the roof are unchanged. The added peppermint raises the model's top to Z = 146 and brings the frontmost point to Y = -31.249 model units. Full dimensions and placement are in [peppermint-dimensions.json](peppermint-dimensions.json).

## Previews

These renders use the actual exported mesh. Red and white on the peppermint illustrate painting; STL does not store colors. The rest of the model is shown in gray.

- [Front view with peppermint paint guide](center-front-paint-guide-v7.png)
- [Peppermint close-up and paint guide](peppermint-paint-guide-v7.png)
- [Solid-gray close-up of the two smoothed snow joins](junction-closeup-v7.png)

## Validation

The saved STL reloads as a watertight mesh with consistent winding, positive volume, and one connected material part. The peppermint has a positive volume overlap with the snow, rather than a surface-only contact. Mesh hash, bounds, and construction measurements are in [mesh-validation.json](mesh-validation.json).

Saved-file surface comparisons check the original mounting surfaces and functional underside within 0.01 model units. The lower front snow lip and front decoration outside the new disc attachment are compared with v6 within 0.02 model units. Exposed roof-plane probes must remain within 0.005 model units. Independent cross-sections measure the reduction in sharp changes of slope on the two raised shoulders. Results, sample counts, and both the shoulder and whole-transition measurements are in [surface-validation.json](surface-validation.json).

These are mesh and geometry checks; physical printing and assembly have not been tested. Import with the same unit convention as the original files.
