# Limit and Offset

Select the first 10 rows from the `customers` table:

```sql
SELECT *
FROM customers
LIMIT 10;
```

Select the first 25% of rows from the `customers` table:

```sql
SELECT *
FROM customers
LIMIT 25%;
```

Select 10 rows from the `customers` table, starting at position 5:

```sql
SELECT *
FROM customers
LIMIT 10
OFFSET 5;
```
