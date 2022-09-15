

----



## Shope Creek Trail System



>[Direct Link](https://waterlevelmedium.github.io/ShopeCreek_Pyle/)


### Introduction



- This Web Map depicts the longest loop in the Shope Creek Trail System in Asheville, NC. Used primarily by mountain bikers, this trail includes a number of features and steep downhill sections. I chose this trail system as I frequented it upon opening of the gravel access road in 2012.

---------
- **This Web Map consists of:**
  - A leaflet tile layer using an aerial image as the background
  - A  polyline representing the trail system, including an inner hiking route.
  - Four Leaflet circle features representing break points in the trail, i.e., junctions, features.
  - A single Leaflet marker representing the parking area.
  - A text box fixed to the bottom of the page that includes links to sources for the geoJson data and USGS Aerial Imagery tile layer, as well as brief descriptions of the trail system's use.
  - A title box fixed to the upper left corner.
  - A interactive button that hides the text box.

- **Data Sources and tools used include:**
  - [USGS Topographic Imagery Tile Layer](https://basemap.nationalmap.gov/arcgis/rest/services/USGSImageryTopo/MapServer/tile/{z}/{y}/{x})
  - [Hike WNC ](https://www.hikewnc.info/trailheads/shope-creek/) provides the trail system in downloadable segments. Also includes brief background. Data is mirror in sister-site [Mountain Bike WNC](https://www.mtbikewnc.com/).
  - QGIS to merge segments into single polyline, then exported as GeoJson data to 'mergedShope.js'.
  - 'mergedShope.js' was then copied to 'route.js' with citations added, and added to the map to be interpreted as geoJson data in variable 'myRoute'.
  - [Leaflet](https://leafletjs.com/SlavaUkraini/) documentation and tutorials were used extensively, as well as the [GitHub CheatSheet](https://education.github.com/git-cheat-sheet-education.pdf) used to monitor changes and troubleshoot issues with the script.

-------
*River Pyle 2022*
