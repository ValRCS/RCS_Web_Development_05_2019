# How would we store a hitcounter?
* http://justintadlock.com/web-design/counter
## What possible problem(s) would be with such a solution?

# Databases

## SQL

* https://www.w3schools.com/sql/sql_intro.asp
* https://sqlzoo.net/
* http://www.mysqltutorial.org/basic-mysql-tutorial.aspx

# # SQL - Structured Query Language
Domain-specific language used in programming and designed for managing data held in a relational database management system (RDBMS)

# History
* Set Theory
* Edgar F. Cobb Relation Model 1970 (later https://en.wikipedia.org/wiki/Codd%27s_12_rules)
* Normalforms (Informally, a relational database relation is often described as "normalized" if it meets third normal form. Most 3NF relations are free of insertion, update, and deletion anomalies.)
* ACID (Atomicity, Consistency, Isolation, Durability) 
* Future




* CREATE
* INSERT
* UPDATE
* DELETE

* SELECT

(In general programming CRUD (Create,Read,Update,Delete))

### SELECT DISTINCT column_list

### FROM table_list

###   JOIN table ON join_condition
  
### WHERE row_filter

### ORDER BY column

### LIMIT count OFFSET offset

### GROUP BY column

### HAVING group_filter

* Use ORDER BY clause to sort the result set
* Use DISTINCT clause to query unique rows in a table
* Use WHERE clause to filter rows in the result set
* Use LIMIT OFFSET clauses to constrain the number of rows returned
* Use INNER JOIN or LEFT JOIN to query data from multiple tables using join.
* Use GROUP BY to get the group rows into groups and apply aggregate function for each group.
* Use HAVING clause to filter groups

# sample database Chinook
# fork at https://github.com/ValRCS/chinook-database

![CHINOOK STRUCTURE](img/sqlite-sample-database-color.jpg)

## Chinook sample database tables
### There are 11 tables in the chinook sample database

*  employees table stores employees data such as employee id, last name, first name, etc. It also has a field named ReportsTo to specify who reports to whom.
*  customers table stores customers data.
*  invoices & invoice_items tables: these two tables store invoice data. The invoices table stores invoice header data and the invoice_items table stores the invoice line items data.
*  artists table stores artists data. It is a simple table that contains only artist id and name.
*  albums table stores data about a list of tracks. Each album belongs to one artist. However, one artist may have multiple albums.
*  media_types table stores media types such as MPEG audio file, ACC audio file, etc.
*  genres table stores music types such as rock, jazz, metal, etc.
*  tracks table store the data of songs. Each track belongs to one album.
*  playlists & playlist_track tables: playlists table store data about playlists. Each playlist contains a list of tracks. Each track may belong to multiple playlists. The relationship between the playlists table and tracks table is many-to-many. The playlist_track table is used to reflect this relationship.

## SQLite using browser
* https://sqliteonline.com/

## Connecting to MySQL in PHP
* https://secure.php.net/manual/en/mysqlinfo.api.choosing.php


## Connecting into SQLite in PHP
http://www.sqlitetutorial.net/sqlite-php/

# SQL Exercises

* https://www.w3schools.com/sql/sql_exercises.asp
* https://www.w3resource.com/sql-exercises/
* https://sqlbolt.com/
* https://www.hackerrank.com/challenges/revising-the-select-query/problem


## NoSQL

* https://www.3pillarglobal.com/insights/exploring-the-different-types-of-nosql-databases
* https://www.sitepoint.com/sql-vs-nosql-differences/
