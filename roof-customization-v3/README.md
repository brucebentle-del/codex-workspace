# Raised, shallow snow — revision 3

The snow follows the reference with smaller rounded scallops, a shallow lower edge, and full rounded eave caps. It sits higher than revision 2 to expose the existing holly details. It blends back onto the roof rather than hanging in large drops. The original side-roof crown ornaments are retained. Each roof and its snow form one fused material part.

The set now includes the newly uploaded right roof. Scale, orientation, mounting locations, and underlying roof construction are retained, subject to the small numerical cleanup described below. STL does not encode units; keep the same import units as the originals.

## Files

- [Left roof, rev10](left_roof_rev10_inner_snow_flat_shallow_snow_v3.stl)
- [Right roof, rev10 mirrored](right_roof_rev10_inner_snow_flat_mirrored_shallow_snow_v3.stl)
- [Center roof, rev31](center_roof_rev31_front_seams_smooth_shallow_snow_v3.stl)
- [Center roof, rev30](center_roof_rev30_smooth_top_planes_shallow_snow_v3.stl)

The two center files are alternatives corresponding to the two uploaded center models. Choose one center version to print with the left and right roofs.

The right upload was verified against the left source: it has the same triangle connectivity under the reflection `x_right = 148 - x_left`, with matching vertex positions within 0.000008 model units. The v3 left snow was reflected using that same transformation to make a matched pair. The right STL was then exported, reloaded, and checked against the uploaded right source. `right-source-match.json` records this comparison.

## Previews

- [Center, front](center-front-v3.png)
- [Left, front](left-front-v3.png)
- [Right, front](right-front-v3.png)
- [Center, angled](center-angle-v3.png)

The previews use the saved STL geometry. White highlights the snow region for illustration. The STL files themselves have no colors, and retained portions of the original roof may appear gray in the previews.

## Validation and limits

All four exports were reloaded and verified as watertight, consistently wound meshes with positive total volume and one connected material part. Closed interior cavity boundaries are retained; these are not detached snow pieces. File hashes and mesh measurements are in `mesh-validation.json`.

Numerical seams and near-zero-thickness fragments from the unions were cleaned up. A bounded material expansion of 0.001137 model units per axis was used to resolve coincident surfaces. Original fitting surfaces were not voxel-remeshed. The original mounting-peg surface samples remain within 0.002 model units of the exports. Sampled underside surfaces remain within 0.020 model units; the largest deviations are small mirrored seams on the side roofs. These distances are millimeters if that is how the original files are imported.

`underside-validation.json` records the sample counts, observed distances, and acceptance tolerances (0.005 for mounting samples and 0.025 for underside samples). Distances above 0.003 were rechecked in double precision because single-precision closest-point searches over long, thin triangles can overstate the distance. These are sampled surface checks, not a physical fit test or an exhaustive dimensional certification.

The original hollow regions are reserved under the added snow. Exact clearance against a separate holly-trim part remains unverified because its STL has not been supplied. The existing roof details are visible in the front views. Slicing and physical printing have not been tested.

Earlier revisions remain in their own folders. Use this v3 folder for the revised shallow profile.
