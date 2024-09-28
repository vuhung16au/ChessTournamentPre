# Add backup option

Modify the program so that, 

when run with argument "--backup", we will backup the current database to FidePlayers-YYYYMMDD.sqlite

# Add CSV export option

Modify the program so that, 

when run with argument "--export-csv", we will export the current database to FidePlayers-YYYYMMDD.csv

# Add CSV import option

Modify the program so that, 

when run with argument "--import-csv 'filename.csv'", we will import all the players data from 'filename.csv' and append them to the database 

# Show data 

Modify the program so that, 

when run with argument "--show-data", we will print the current database into the console

# Generate random data 

modify the app so that, when run with arg "--gen-random-data -N", we will generate N random Fide player data and append to the database. 

# Generate a test cas 

Add an arg "--test". When run with this arg. It will 

``` 
--init-db 
--add-kyanh
--gen-random-data 10
--show-data
--import-csv FirstData.csv
--export-csv
--backup
```

# Add sort options 

```
Add sort options: 

/list_players?sort_by=RatingStandard&order=asc
/list_players?sort_by=RatingStandard&order=desc


Add sort options: 
/list_players?sort_by=RatingACFStandard&order=asc
/list_players?sort_by=RatingACFStandard&order=desc
``` 