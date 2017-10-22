# frms-data-populator

Calling should be something like:

//Export from database to CSV
java -jar frms-data-populator export ./companies.csv

//Import from CSV to database
java -jar frms-data-populator import ./companies.csv


Note: When import from CSV's to database, they need to be placet in root where the file is and names need to be as folows:
companies.csv
events.csv
users.csv
