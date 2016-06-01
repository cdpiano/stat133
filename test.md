Process H1b Data.
======

## Get all the companies appeared in each year.

### Dependencies
* city.csv
* region.csv
* zipcode.csv
* h1b2002.csv, h1b2003.csv, ... , h1b2016.csv

### Instructions
1. Open terminal, run `python find_company.py`.
2. The number shown on screen represents the number of records that have been processed.
3. After done, all the companies will be stored in `company.csv` and all the invalid companies will be stored in `company_error.csv`.

## Process h1b record for each year.

### Dependencies
* city.csv
* region.csv
* zipcode.csv
* company.csv
* h1bxxxx.csv (xxxx represents year)

### Instructions
1. Open terminal, run `python updatexxxx.py`.
2. The number shown on screen represents the number of records that have been processed.
3. After done, all the updated h1b records will be stored in `resultxxxx.csv`, all the invalid records due to company error will be stored in `company_invalidxxxx.csv` and all the invalid records due to city error will be stored in `city_invalidxxxx.csv`
