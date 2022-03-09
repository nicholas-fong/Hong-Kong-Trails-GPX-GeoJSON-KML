# Hong-Kong-Trails-GPX-Hiking
For hiking enthusiasts savvy with mobile devices and offline hiking apps. This repository hosts a complete set of GPX tracks/routes for the 4 major hiking trails in Hong Kong SAR (Hong Kong Trail 港島徑 45 km, Lantau Trail 鳳凰徑 67 km, MacLehose Trail 麥理浩徑 98 km, Wilson Trail 衛奕信徑 12 km + 64 km).

Methodology used to generate these tracks:<br>
Using [Overpass](https://www.overpass-turbo.eu) query wizard to extract nodes and export the output (in osm format) to [JOSM](https://josm.openstreetmap.de/) to manually correct data inconsistencies and other errors. The cleaned up data is exported as GeoJSON and then converted to GPX tracks or GPX routes or KML using [geoJSON-gpx-convert](https://github.com/nicholas-fong/geoJSON-gpx-convert). The elevation profile of the trails is derived from NASA's Advanced Spaceborne Thermal Emission and Reflection Radiometer `ASTER` Global Digital Elevation Model `GDEM` GeoTIFF geospatial metadata based on the GPS coordinates of the trail nodes, using [gpx-add-SRTM](https://github.com/nicholas-fong/gpx-add-SRTM)

To visualize the GPX tracks/routes on a desktop, I use [GPXSee](www.gpxsee.org). Both GPX tracks and routes are available because some devices or hiking apps work better with `GPX track` and others work better with `GPX route`. `KML` version of the 4 major hiking trails are also hosted in this repository for visualization on `Google Earth` or `Google My Maps`.

Mobile phone version of Google Maps, despite its popularity in vehicle navigatioin and "offline mode", IMHO it is not designed to use with GPX/KML for hiking navigation, perhaps in the future. Examples of offline hiking apps are `Locus Map` (Andorid) and `Komoot` (Andorid and iPhone). If you use `Garmin` handheld GPS, simply import the GPX hiking trails to your handheld. Be sure to bring a fully charged battery power bank and charging cable for your phone.

Due to the length and difficulties of the full trails, hiking trails are divided into sections (e.g. for day hikes). Consult Wikipedia or https://www.hiking.gov.hk for various trail heads and how to get there. Beware and be prepared, even in densely populated Hong Kong SAR, some segments of the trails are remote i.e. no transportation, no shelters, no food or water and no mobile phone coverage.

The Agriculture, Fisheries and Conservation Department `AFCD` 漁農自然護理署 of Hong Kong SAR created a "Enjoy Hiking" website https://www.hiking.gov.hk, it is an excellent starting point. The Country and Marine Parks Authority `CMPA` 郊野公園及海岸公園管理局 of Hong Kong SAR operates and maintains the trails.
The Office of the Communications Authority `OFCA` 通訊事務管理局辦公室 of Hong Kong SAR publishes trail maps with mobile phone coverage information (in PDF). It is prudent to bring a backup paper map especially for long hikes just in case technology goes badly during the hike. https://www.ofca.gov.hk/en/consumer_focus/guide/safety/country_parks/coverage_survey/digital_map/index.html
