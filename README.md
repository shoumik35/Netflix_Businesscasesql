# Netflix Movies and Tv shows Data analysis using SQL
![Netflixlogo](https://github.com/shoumik35/Netflix_Businesscasesql/blob/main/Netflixlogo.png)

## Schema
```sql 
DROP TABLE IF Exists netflix;
CREATE TABLE netflix (show_id Varchar(15),
type Varchar(10),
title Varchar(150),
director Varchar(208),	
casts Varchar(1000),	
country Varchar(150),	
date_added Varchar(50),	
release_year INT,	
rating	Varchar(10),
duration Varchar(15),	
listed_in Varchar(100),	
description Varchar(250)
);
