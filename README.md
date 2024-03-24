# bike-rack-map

## Purpose
The main purpose of this repository is to create a record of the locations and details of bike racks around Dalhousie's Campuses.
The secondary purpose is to map bike racks in the Halifax Regional Municipality.

## Method
Locations of the bike racks are stored as points in a GeoJSON file named  `racks.geojson` file. The file is found here:
https://github.com/DalKingsBikeCentre/bike-rack-map/blob/main/racks.geojson

## To-do and wishlist:
- Formalize methodology and write instructions for future contributors
- Find contributors
- Data conversion:
  - Find or create a github workflow that will automatically convert the geojson files to KML/KMZ
- Create a Google Earth project and add data to it
- Create a webmap using something like Leaflet, Mapbox, etc...
