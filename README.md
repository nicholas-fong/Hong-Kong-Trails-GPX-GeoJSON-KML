# Hong-Kong-Trails-GPX-Hiking
For hiking enthusiasts savvy with mobile devices and offline hiking apps. This repository hosts a complete set of unofficial high quality GPX tracks/routes for the 4 major hiking trails in Hong Kong SAR (MacLehose Trail 麥理浩徑 98 km, Hong Kong Trail 港島徑 45 km, Wilson Trail 衛奕信徑 76 km and Lantau Trail 鳳凰徑 67 km for a total of 286 km with over 24,000 route points). Use these files at your own risks.

Methodology used to generate these tracks:<br>
Using [Overpass](https://www.overpass-turbo.eu) query wizard to extract trails and export the result to [Java OpenStreetMap Editor](https://josm.openstreetmap.de/) to manually correct data inconsistencies and other errors. The cleaned up data is then converted to `GPX tracks`,`GPX routes` and `KML` using codes from [geoJSON-gpx-convert](https://github.com/nicholas-fong/geoJSON-gpx-convert). The elevation of the trails is derived from NASA's Advanced Spaceborne Thermal Emission and Reflection Radiometer `ASTER` Global Digital Elevation Model `GDEM` GeoTIFF geospatial metadata based on the GPS coordinates of the trails, using codes from [gpx-add-SRTM](https://github.com/nicholas-fong/gpx-add-SRTM)

To visualize: download a GeoJSON file and drop it in [geojson.io](https://geojson.io).`GPX track` and `GPX route` are both hosted in this repository because some devices/hiking apps work better with `GPX track` and others work better with `GPX route`. `KML` version of the trails are hosted in this repository for visualization with `Google Earth` or `Google My Maps` or import to MAPS.ME app.

Mobile phone version of Google Maps, despite its popularity in vehicle navigatioin and "offline mode", IMHO it is not designed to be used with GPX/KML for hiking navigation (perhaps in the future). Examples of good offline hiking apps are `Locus Map` (Andorid) and `Komoot`, `MAPS.ME` (Andorid and iOS). If you use `Garmin` handheld GPS, simply import the GPX hiking trails to your handheld.

Due to the length and difficulties of the full trails, hiking trails are divided into sections/stages. Consult [Wikipedia](https://en.wikipedia.org/wiki/List_of_hiking_trails_in_Hong_Kong) or [Enjoy Hiking website](https://www.hiking.gov.hk) for trail heads and how to get there. Some segments of the trails have no transportation, no shelters, no food, no water and no mobile phone coverage.

`Government sites` The Agriculture, Fisheries and Conservation Department `AFCD` 漁農自然護理署 of Hong Kong SAR's [Enjoy Hiking website](https://www.hiking.gov.hk) is an excellent starting point for planning a hike. The Country and Marine Parks Authority `CMPA` 郊野公園及海岸公園管理局 of Hong Kong SAR operates and maintains the trails.
The Office of the Communications Authority `OFCA` 通訊事務管理局辦公室 of Hong Kong SAR publishes [PDF trail maps](https://www.ofca.gov.hk/en/consumer_focus/guide/safety/country_parks/coverage_survey/digital_map/index.html) with estimated mobile phone signal coverage. It is prudent to print a backup paper map especially for long hikes just in case GPS technology devices go badly during the hike. 

Carrying a fully charged battery power bank can prevent the situation of depleted phone battery.
