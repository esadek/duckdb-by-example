# Limit and Offset

Select the first 10 rows from the `penguins` table:

```sql
SELECT *
FROM penguins
LIMIT 10;
```

Select the first 25% of rows from the `penguins` table:

```sql
SELECT *
FROM penguins
LIMIT 25%;
```

Select 10 rows from the `penguins` table, starting at position 5:

```sql
SELECT *
FROM penguins
LIMIT 10
OFFSET 5;
```
