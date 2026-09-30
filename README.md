# FDFPV Yellowstone data

Terrain tiles and map data for the Yellowstone map of
[FDFPV](https://fdflabs.github.io/fdfpv/), a 100 by 100 km piece of
Yellowstone National Park at real scale. The simulator fetches these
files at run time; this repository is served as a static site for that.
FDFPV and this data repository are made by [fdflabs.com](https://fdflabs.com).

The format is the contract in the simulator's `docs/YELLOWSTONE-PLAN.md`,
and `manifest.json` lists every file with its checksum. The files are
built by `tools/yellowstone/` in the simulator's repository
(github.com/fdflabs/fdfpv); do not edit them by hand.

## Sources and licences

- Elevation: USGS 3D Elevation Program (3DEP) 1/3 arc second DEM, via
  The National Map. Public domain, a work of the US Government.
- Rivers, streams and lakes: USGS NHDPlus High Resolution. Public domain.
- Land cover: NLCD 2021, MRLC. Public domain.
- Place names: USGS Geographic Names Information System. Public domain.
- Roads and boardwalks: NPS national roads and trails, and US Census
  TIGER/Line outside the park. Public domain.
- Geyser eruption intervals: NPS, Yellowstone geyser eruption data.
  Public domain.
- Thermal features: the Yellowstone thermal feature inventory as
  published by the Yellowstone Research Coordination Network, Montana
  State University (rcn.montana.edu), whose locations and types come
  from the Yellowstone National Park thermal inventory and the USGS.
  Credited here with thanks; that database states no licence of its own.

Each source's download URL, publication date, retrieval time and
checksum are in `manifest.json`.
