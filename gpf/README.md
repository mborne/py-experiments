# geoplateforme

Examples using [IGN Geoplateforme](https://geoservices.ign.fr/) services (requires network access).

* [wms-bug-reproj](wms-bug-reproj.ipynb) : Compute a normal map from heights retrieved with the [WMS-R service](https://data.geopf.fr/wms-r/wms) and show the artifacts caused by reprojection/resampling (EPSG:3857 vs native Lambert 93 EPSG:2154). Images are written to `output/`.
