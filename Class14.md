# Database Normalization

Database normalization is a process used to organize a database into tables and columns.
By limiting a table to one purpose you reduce the number of duplicate data contained within your database. This eliminates some issues stemming from database modifications.

## Reasons for Database Normalization
1. to minimize duplicate data
2. minimize or avoid data modification issues
3. simplify queries.

### Data Duplication and Modification Anomalies
1. It increases storage and decrease performance.
2. It becomes more difficult to maintain data changes.

### Insert Anomaly
There are facts we cannot record until we know information for the entire row. 

### Update Anomaly
 If we don’t update all rows, then inconsistencies appear.