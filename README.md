# Photomap
A Leaflet map that reads data from Google Sheets.  

Created as assignment 10 for [GEOG 4046](https://geog4046.github.io).  

Each row in the sheet will appear as a marker on the map. When the marker is clicked, a popup will appear showing information about the location, taken from the columns of the spreadsheet.  

This script assumes the Google Sheet has the following columns. This is a sample map showing 7 points of interest around Paris, France. 

https://erinvoisin-sketch.github.io/photomap/  

Column name | Description
:-----------|--------------------------------------------------------------
name        | A short name for the location, to appear as the popup title |
description | A sentence or two describing the location in more detail    |
lat         | Latitude in decimal degrees                                 |
long        | Longitude in decimal degrees                                |
pic_url     | The URL to an image that will be displayed in the popup     |
