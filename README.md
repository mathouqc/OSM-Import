# OSM Import

## Wiki pages + Data source

Import wiki page: [Canada Building Import OSM Wiki page](https://wiki.openstreetmap.org/wiki/Canada_Building_Import)

Buildings source wiki page: [Canada - The Open Database of Buildings OSM Wiki page](https://wiki.openstreetmap.org/wiki/Canada_-_The_Open_Database_of_Buildings)

Buildings source shapefile: [The Open Database of Buildings (source shapefile)](https://www.statcan.gc.ca/en/lode/databases/odb)
(Using `ODB_Quebec.zip`)

## Steps

### QGIS

1. On QGIS, extract the buildings in the working area

2. Add `building=residential` and `building=shed` tags based on shape area

3. Export selected buildings with the new tags as a shapefile

### JOSM

1. Open JOSM, install `opendata` plugin

2. Open the exported shapefile (using `opendata` plugin)

3. Check all buildings for misalignments, wrong tags, and then press `q` to orthogonalize it ([OrthogonalizeShape](https://josm.openstreetmap.de/wiki/Help/Action/OrthogonalizeShape))

4. Copy buildings from the shapefile layer to the OSM data layer

## Others

https://www.openstreetmap.org/user/MathouQC%20Import