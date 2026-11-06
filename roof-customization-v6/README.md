# Center rev31 — snow touchup (v6)

This is an earlier version. The current [rev31 v7](../roof-customization-v7/README.md) adds the fused peppermint and smooths the two snow-join creases.

This revision contains **rev31 only**. It starts from the fused v5 center roof and touches up the cosmetic snow.

- The uneven lower edge on the left side of the ridge snow now follows the smoother opposite side, while retaining the scallops.
- The old upper join across the front snow drift is blended into a continuous surface.
- Both front tips are faired into smoother rounded ends without adding more overlapping caps.

The roof structure, mounting surfaces, underside, front lettering, holly decoration, and lower front snow lip are preserved within the measured tolerances. Original scale and orientation are retained. Import with the same units as the source STL.

## Download

[Download center rev31 STL](https://github.com/brucebentle-del/codex-workspace/raw/refs/heads/main/roof-customization-v6/center_roof_rev31_smooth_snow_v6.stl)

The left and right roofs remain at v4: [left](../roof-customization-v4/left_roof_rev10_inner_snow_flat_scalloped_snow_v4.stl), [right](../roof-customization-v4/right_roof_rev10_inner_snow_flat_mirrored_scalloped_snow_v4.stl).

## Previews

The solid-gray previews use the actual exported rev31 mesh.

- [Top view showing both sides of the ridge and the front join](center-top-v6.png)
- [Front view](center-front-v6.png)
- [Left tip close-up](center-left-tip-v6.png)
- [Right tip close-up](center-right-tip-v6.png)

## Checks

The saved STL reloads as a watertight mesh with consistent winding, positive volume, and one connected material part. Its hash, bounds, and export details are in [mesh-validation.json](mesh-validation.json).

Independent surface samples compare the original mounting surfaces and functional underside within 0.01 model units, and the v5 front decoration and lower snow lip within 0.02 model units. Exposed roof-plane probes must stay within 0.005 model units. Cross-sections compare the two ridge sides and measure the reduction in the front join's sharp change of slope. Measurements and sample counts are in [surface-validation.json](surface-validation.json).

The upper front snow and tips are intentionally reshaped. Local fairing details are in [fairing.json](fairing.json). Export simplification is bounded to 0.001 model units. Physical printing and assembly have not been tested.
