# objective
Insert, Update, and Delete Data in a Database
## Concepts Covered
Insert rows into a table
Update rows in a table
Delete rows from a table
Import rows from a database backup file

## Sample command
To insert rows into the country table.
```sql
INSERT INTO world.country VALUES ('IRL','Ireland','Europe','British Islands',70273.00,1921,3775100,76.8,75921.00,73132.00,'Ireland/Éire','Republic',1447,'IE');

INSERT INTO world.country VALUES ('AUS','Australia','Oceania','Australia and New Zealand',7741220.00,1901,18886000,79.8,351182.00,392911.00,'Australia','Constitutional Monarchy, Federation',135,'AU');

To delete ALL rows from the country table,
SET FOREIGN_KEY_CHECKS = 0;
DELETE FROM world.country;

## Reflection
Database design is about reducing duplication and organizing data to match real-world relationships.
