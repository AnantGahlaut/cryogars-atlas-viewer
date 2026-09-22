# CryoGARS · SnowEx Field Atlas

[Open the 3D Atlas](https://anantgahlaut.github.io/cryogars-atlas-viewer/)

Browser-ready research preview of LiDAR and UAVSAR observations across eight
SnowEx field sites. No installation or HDF5 download is required. A modern
WebGL-capable browser is needed; desktop viewing is recommended.

This repository distributes the September 22, 2026 viewer update, not the full-resolution
HDF5 archive or the development pipeline. The sampled display grid differs from
the archive's 3 m analysis grid. Read the product information panels for methods
and limitations before quantitative use.

GeoTIFF comparisons and PNG exports run in your browser. Imported files are not
uploaded to this website.

Created by Anant Gahlaut at [CryoGARS](https://github.com/cryogars), Boise State
University. Source observations retain their original attribution and use
requirements. A project code license has not yet been selected.

## Current viewer update

All eight explorers were freshly exported from the existing archives and validated,
covering 1,664 layers. The update includes expanded product notes and methods,
Detail-based Cells averaging, Smooth mode, live stored/shown validity explanations,
coherence-mask fraction/binary controls with an adjustable cutoff, and corrected
radar dates, flight-line labels, angle units and stretch descriptions.

Scientific archives were not repaired in this update. Historical aspect still
has a north/south reflection; circular display averaging does not correct that
stored convention. Derivative-input, approximate incidence/height-reference and
archive-metadata limitations remain documented in the product notes. Backup-dependent
archive repairs and the final scientific archive release are pending.

Local-machine paths are redacted from public lineage records. Original record and
recipe digests are retained explicitly as pre-redaction identities, not checksums
of the redacted records. Scientific arrays and application code are unchanged by
publication packaging.
