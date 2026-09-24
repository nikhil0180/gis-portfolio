# Nikhil Bandla - GIS Portfolio

**[nikhil0180.github.io/gis-portfolio](https://nikhil0180.github.io/gis-portfolio/)**

An interactive portfolio site built around six geospatial analysis projects - spatial statistics, network and accessibility modeling, climate risk mapping, land readjustment planning, and urban green infrastructure research. Features a 3D globe tour (Three.js), live project story panels, and an embedded ArcGIS Instant App.

## Projects

| Project | Focus |
|---|---|
| [Sea Level Rise Impact Assessment, Miami Beach](https://nikhil0180.github.io/gis-portfolio/files/miami-sea-level-rise/miami-files.html) | 3D climate risk modeling - 9,469 buildings tagged by first year of NOAA-projected inundation |
| [Pedestrian Park Accessibility, Chicago](https://nikhil0180.github.io/gis-portfolio/files/chicago-park-accessibility/chicago-files.html) | Network Analyst service areas vs. Euclidean buffers - straight-line methods overstate access by 59% |
| [Urban Tree Canopy & Heat, New York City](https://nikhil0180.github.io/gis-portfolio/files/nyc-tree-canopy/nyc-files.html) | NDVI, land surface temperature, and spatial regression (OLS, spatial lag/error, GWR) |
| [Park Accessibility & Spatial Equity, The Bronx](https://nikhil0180.github.io/gis-portfolio/files/bronx-park-accessibility/bronx-files.html) | Buffer analysis intersected with census tracts to surface an environmental justice gap |
| [Land Pooling & Town Planning Schemes, Hyderabad](https://nikhil0180.github.io/gis-portfolio/files/land-pooling/land-pooling-files.html) | Multi-criteria site selection (DELPHI technique) for a land pooling development plan |
| [Urban Green Spaces, Saidabad, Hyderabad](https://nikhil0180.github.io/gis-portfolio/files/urban-green-spaces-thesis/thesis-files.html) | B.Tech thesis measuring green space provision against national planning norms |

## Repo structure

- `index.html` - main site: hero, about, project cards, 3D globe tour
- `files/miami-sea-level-rise/` - images, PDFs, and the project's own files page
- `files/chicago-park-accessibility/`
- `files/nyc-tree-canopy/`
- `files/bronx-park-accessibility/`
- `files/land-pooling/`
- `files/urban-green-spaces-thesis/`

Each project folder is self-contained: its source images, its report/presentation PDFs, and an `*-files.html` page that displays them, linked from the project's "View Project" button on the main site.

## Stack

Tailwind CSS, Three.js (3D globe), GSAP (ScrollTrigger), ArcGIS Instant App (embedded), ArcGIS Pro / Network Analyst, Python (GeoPandas, PySAL), R (spdep, tmap)

Static site, deployed via GitHub Pages.
