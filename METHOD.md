# Methodology used to generate these hiking tracks:<br>
Use [Overpass](https://www.overpass-turbo.eu) query wizard to extract nodes, e.g. in the query wizard box: name ~ "MacLehose Trail" 

Save (export) the output as `GeoJSON`

Open [Java OpenStreetMap Editor](https://josm.openstreetmap.de/) to manually correct data inconsistencies:
<br>remove overlapping/duplicated/extraneous paths and objects
<br>change direction of paths to be consistent (follow sign post from n to n+1)
<br>join segments that are disjointed
<br>merge all small segments into one complete path (e.g. GeoJSON: one LineString, GPX: one track segment or one route)
<br>optimize (reduce) the number of nodes

The cleaned up data is saved as `GeoJSON` and then converted to `GPX tracks`,`GPX routes` and `KML` using code from [geoJSON-gpx-convert](https://github.com/nicholas-fong/geoJSON-gpx-convert). 

The elevation profile of the trails is added using code from [gpx-add-SRTM](https://github.com/nicholas-fong/gpx-add-SRTM)