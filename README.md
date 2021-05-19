# GeoNames-MySQL

V 3.0 Shell Script for importing geonames.org data dumps into a MySQL database.

Usage: geonames_script.sh -a "action"

Where "action" can be: 
  
- **download-data** Downloads the last packages of data available in GeoNames. An additional parameter with a download directory should be used.
- **create-db** Creates the mysql database structure with no data.
- **create-tables** Creates the tables in the current database. Useful if we want to import them in an exsiting db.
- **import-dumps** Imports geonames data into db. A database is previously needed for this to work.
- **drop-db** Removes the db completely.
- **truncate-db** Removes geonames data from db.
    
Reference the <a href="https://download.geonames.org/export/dump/readme.txt" target="_blank">ReadMe</a> file.

You find the dump files <a href="https://download.geonames.org/export/dump/" target="_blank">here</a>

Postal codes are available as a separate download <a href="https://download.geonames.org/export/zip/" target="_blank">here</a>
