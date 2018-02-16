# IL_HYDRO_ISLANDS <img src="https://slu-dss.github.io/img/gisLogoSm.png" align="right" />
## Mississippi River in Illinois

[![](https://img.shields.io/badge/extent-Madison%20and%20St.%20Clair%20Counties,%20IL-red.svg)](https://github.com/slu-openGIS/IL_HYDRO_Mississippi/)
[![](https://img.shields.io/badge/category-physical%20geography-orange.svg)](https://github.com/slu-openGIS/IL_HYDRO_Mississippi/)
[![](https://img.shields.io/github/release/slu-openGIS/IL_HYDRO_Mississippi.svg?label=version)](https://github.com/slu-openGIS/IL_HYDRO_Mississippi/releases)
[![](https://img.shields.io/github/last-commit/slu-openGIS/IL_HYDRO_Mississippi.svg)](https://github.com/slu-openGIS/IL_HYDRO_Mississippi/commits/master)
[![](https://img.shields.io/github/repo-size/slu-openGIS/IL_HYDRO_Mississippi.svg)](https://github.com/slu-openGIS/IL_HYDRO_Mississippi/)

### Abstract
The Census TIGER hydrology data is released by county, so bodies of water that lie between jurisdictions end up split. This shapefile contains data on the extent of the Mississippi River in Madison and St. Clair counties for the length of the City of St. Louis. These data can be previewed interactively using the [`.geoJSON` file in this repository](https://github.com/slu-openGIS/IL_HYDRO_Mississippi/blob/master/geoJSON/IL_HYDRO_Mississippi.geoJSON).

### Use with R
The [`gateway` package](https://github.com/slu-openGIS/gateway) can be used to download and import these data as a simple feature object:

```r
city <- gateway::gw_get_repo("IL_HYDRO_Mississippi")
```

## About the SLU DSS
### The openGIS Project
The openGIS Project is a faculty-student collaboration at SLU organized by [Christopher Prener, Ph.D.](mailto:chris.prener@slu.edu}). The goal of the project is to produce publicly available spatial data about the St. Louis region.

### About the SLU Data Science Seminar
The [SLU Data Science Seminar](https://slu-dss.githb.io) (DSS) is a collaborative, interdisciplinary group at Saint Louis University focused on building researchers’ data science skills using open source software. We currently host seminars focused on the programming language R. The SLU DSS is co-organized by [Christina Gacia, Ph.D.](mailto:christina.garcia@slu.edu), [Kelly Lovejoy, Ph.D.](mailto:kelly.lovejoy@slu.edu@slu.edu), and [Christopher Prener, Ph.D.](mailto:chris.prener@slu.edu}). You can keep up with us here on GitHub, on our [website](https://slu-dss.githb.io), and on [Twitter](https://twitter.com/SLUDSS).

### About Saint Louis University
[Saint Louis University](http://wwww.slu.edu) is a Catholic, Jesuit institution that values academic excellence, life-changing research, compassionate health care, and a strong commitment to faith and service. Founded in 1818, the University fosters the intellectual and character development of more than 13,000 students on two campuses in St. Louis and Madrid, Spain. Building on a legacy of nearly 200 years, Saint Louis University continues to move forward with an unwavering commitment to a higher purpose, a greater good.
