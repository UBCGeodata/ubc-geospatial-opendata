UBC Okanagan Locations 
=======================

Datasets
--------
### ubco_buildings_full
 - An export of the buildings data as stored in our geodatabase. In general, a building is defined by a distinct buliding envelope, construction material, or construction form.
### ubco_buildings_simple
 - a simplified, flattened version of the data with address, alias and main entrance information.
### ubco_address_full
 - The geocode/address dataset for UBC Vancouver
 - This is based on the [BC Physical Address Exchange Schema](https://github.com/bcgov/api-specs/blob/master/geocoder/BCAddressExchangeSchema.md)
### ubco_address_mailing
 - A CSV only dataset that has simplified fields and only mailing addresses.



Files Provided
--------------
* Data on git are geojson and csv (text) only. File geodatabase download [here](https://maps.gis.ubc.ca/data/ubco/ubco_locations.gdb.zip).
* FGDB is UTM11N(ESPG:26911), geojson is LL84(ESPG:4326).
* csv data has lat/long columns.

Metadata
--------
* there is a CSV data dictionary in the metadata folder with a list of attributes.

License
-------
* This data is made available under the Public Domain Dedication and License v1.0 whose full text can be found at: [http://www.opendatacommons.org/licenses/pddl/1.0/](http://www.opendatacommons.org/licenses/pddl/1.0/)