# Database Lab: Insert, Update, and Delete Data in a Database

## Objective
Insert rows into a table
Update rows in a table
Delete rows from a table
Import rows from a database backup file

## Sample Query
To configure the terminal to access all required tools and resources.
```sql
sudo su
cd /home/ec2-user/
```
To connect to the database instance.
```sql
mysql -u root --password='re:St@rt!9'

To insert rows into the country table
```sql
INSERT INTO world.country VALUES ('IRL','Ireland','Europe','British Islands',70273.00,1921,3775100,76.8,75921.00,73132.00,'Ireland/Éire','Republic',1447,'IE');

INSERT INTO world.country VALUES ('AUS','Australia','Oceania','Australia and New Zealand',7741220.00,1901,18886000,79.8,351182.00,392911.00,'Australia','Constitutional Monarchy, Federation',135,'AU');
JOINs were tricky at first. The key is understanding how tables relate to each other using foreign keys.
## Reflection
To insert rows into the country table
INSERT INTO world.country VALUES ('IRL','Ireland','Europe','British Islands',70273.00,1921,3775100,76.8,75921.00,73132.00,'Ireland/Éire','Republic',1447,'IE');

INSERT INTO world.country VALUES ('AUS','Australia','Oceania','Australia and New Zealand',7741220.00,1901,18886000,79.8,351182.00,392911.00,'Australia','Constitutional Monarchy, Federation',135,'AU');
JOINs were tricky at first. The key is understanding how tables relate to each other using foreign keys.

### screenshot
![inserting data into a data table](https://github.com/user-attachments/assets/94f18e58-7416-450f-b8b0-f4d6164480d9)
![Uploading update rows in table.jpg…]()
![delete rows from a table](https://github.com/user-attachments/assets/af71550f-aa13-4dd0-a090-7404032024a7)
![Import data using an SQL file](https://github.com/user-attachments/assets/b5d3bf52-8509-4f1d-a61e-fc0ad13e5852)
