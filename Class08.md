# SQL 
SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

## Relational databases 
A relational database represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns


### Select 
To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as queries
```
SELECT column, another_column, …
FROM mytable;

```
this will go to the table named "mytable" and bring the column "another_column"

### Queries with constraints  
```
SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;
``` 
so we get the data that we want of the table based  on a condition rather than just  briging the whole table (that in future might contain a lot of data to read through)

### Filtering and sorting Query results 

```
SELECT DISTINCT column, another_column, …
FROM mytable
WHERE condition(s);
```
DISTINCT keyword will blindly remove duplicate rows
