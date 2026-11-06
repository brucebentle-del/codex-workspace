# Center rev31 — clean gable, lush holly, and ribbon bow (v9)

This revision removes the visible old holly remnants near the snow edge and under the peppermint. The new holly is fuller and deeper, with a wider, thicker backing and overlapping clusters of larger folded leaves. The bow has broader ribbon loops, a raised knot, and longer fishtail ends.

The v8 lettering, cream sign field, 34.5-unit peppermint, roof scale, and mounting geometry are retained. Rev31 is the only center version in current downloads.

## Download

[Download the fused rev31 STL](https://github.com/brucebentle-del/codex-workspace/raw/refs/heads/main/roof-customization-v9/center_roof_rev31_lush_holly_ribbon_bow_v9.stl)

The left and right roofs remain at v4: [left](../roof-customization-v4/left_roof_rev10_inner_snow_flat_scalloped_snow_v4.stl), [right](../roof-customization-v4/right_roof_rev10_inner_snow_flat_mirrored_scalloped_snow_v4.stl).

## Previews

These renders use the exported mesh. Colors illustrate painting; the STL stores geometry without colors.

![Front painting guide](center-front-paint-guide-v9.png)

- [Holly and bow close-up with painting guide](sign-paint-guide-v9.png)
- [Unpainted sign, holly, and bow geometry](sign-solid-v9.png)

## What changed

The legacy raised holly is cleared back to the facade using a separate snow-only protection solid. The cleanup is checked on the bare gable before the new garland is added, so the old fragments are removed rather than covered. The inspection compares 2,123 formerly visible legacy-relief locations. Results are in [holly-cleanup-validation.json](holly-cleanup-validation.json).

The garland uses 161 larger leaves, compared with 116 in v8, arranged in overlapping layers and clusters around the berries. The backing is 4.4–6.8 model units wide and 2.9 deep, replacing the earlier 2.4-unit round stem. The green relief has more material and greater depth, with the backing placed behind the leaves so their shapes remain visible.

The bow is approximately 23.3 units wide and 22.7 high, with 2.3-unit ribbon bands, a raised central knot, and 16.5-unit tails ending in fishtail notches. Full decoration dimensions are in [sign-dimensions.json](sign-dimensions.json). Units are millimeters when imported at the same millimeter scale as the original roof.

## Validation

The saved STL reloads as watertight, with consistent winding, positive volume, and one connected material part. Hash, bounds, and construction measurements are in [mesh-validation.json](mesh-validation.json).

Saved-file surface comparisons check the original mounting surfaces and functional underside within 0.01 model units, and retained snow, lettering, and peppermint surfaces within 0.02. Snow samples exclude the peppermint and enlarged bow attachments. Exposed roof-plane probes must stay within 0.005. The 34.5-unit peppermint diameter is measured from the saved mesh. Results and sample counts are in [surface-validation.json](surface-validation.json).

The retained lettering uses Berkshire Swash by Brian J. Bonislawsky / Astigmatic under the [SIL Open Font License](BerkshireSwash-OFL.txt). Physical printing and assembly have not been tested. Import using the same units as the original files.
