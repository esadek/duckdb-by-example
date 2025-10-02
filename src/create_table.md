# Create Table

Create a table from a CSV file:

```sql
CREATE TABLE penguins AS
  SELECT *
  FROM 'http://blobs.duckdb.org/data/penguins.csv';
```
