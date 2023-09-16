# ubc-geospatial-opendata
UBC geospatial open data 'portal'

A github repository to host UBC's operational/wayfinding geospatial data.
- Locations: Bulidings, addresses, campus services, food outlets and other point of interest data.
- Landscape: Soft and hard landscape. Trees, lawn areas, water features, etc.

Why GitHub?
-----------
* GitHub is used most often to host/manage code for version control and collaboration. 
* But it also previes geojson files, and so makes geospatial data browsable, viewable and downloadable.
* Information about using GitHub: [here](https://guides.github.com/activities/hello-world/)

### Viewing data in the repositories
* GitHub uses [Leaflet](http://leafletjs.com/) to display any geojson file.
* You can click on any .geojson file and it will display as a map, allowing you to click on features and review their attributes.
* For example: [UBC Vancouver Buildings](https://github.com/UBCGeodata/ubc-geospatial-opendata/blob/master/ubcv/locations/geojson/ubcv_buildings_simple.geojson)
* CSV files can also be previewed within github: [UBC Vancouver Mailing Addresses](https://github.com/UBCGeodata/ubc-geospatial-opendata/blob/master/ubcv/locations/csv/ubcv_address_mailing.csv)

### Downloading data
* You can get the whole repository of data by clicking on the green 'Clone or download' button on the right of page.

For only a single type of data: 
* Navigate to the location of the data you are interested in.
*  For example  ubc-geospatial-opendata > ubcv > locations > csv > ubcv_address_mailing.csv 
* For a text file (like .geojson or .csv), you can right-click on the 'download' or 'raw' button and choose 'save link as'.
