# CryoGARS · SnowEx Field Atlas

[Open the 3D Atlas](https://anantgahlaut.github.io/cryogars-atlas-viewer/)

Browser-ready research preview of LiDAR and UAVSAR observations across eight
SnowEx field sites. No installation or HDF5 download is required. A modern
WebGL-capable browser is needed; desktop viewing is recommended.

This repository distributes the **v1.0.05** viewer (2026-10-08), not the
full-resolution HDF5 archive or the development pipeline. The sampled display
grid differs from the archive's 3 m analysis grid. Read the product information
panels for methods and limitations before quantitative use.

GeoTIFF comparisons and PNG exports run in your browser. Imported files are not
uploaded to this website.

Created by Anant Gahlaut at [CryoGARS](https://github.com/cryogars), Boise State
University, with HP Marshall. Code is MIT licensed in the
[source repository](https://github.com/AnantGahlaut/cryogars-atlas), which also
rebuilds the full archive from NASA with `get_dataset.py`. Source observations
retain their original attribution and use requirements.

## v1.0.05 viewer

All eight explorers were exported from the corrected enrichment 3.3.0 archives,
covering 1,664 layers. Aspect now points downhill (it was reflected
north–south), terrain and canopy derivatives use the cleaned inputs, and radar
incidence uses the viewed side and projected flight heading. Snow depth,
vegetation height, elevation and all radar channels are unchanged. Viewer code
is unchanged from the previous update. See the
[rebuild record](https://github.com/AnantGahlaut/cryogars-atlas/blob/main/docs/reviews/2026-10-05-archive-rebuild-3.3.0.md).

Radar geometry remains approximate and other documented limitations still apply;
see the product notes and the
[design document](https://github.com/AnantGahlaut/cryogars-atlas/blob/main/docs/design.md).

Local-machine and cluster paths are redacted from public lineage records.
Original record and recipe digests are retained explicitly as pre-redaction
identities, not checksums of the redacted records. Scientific arrays and
application code are unchanged by publication packaging.
