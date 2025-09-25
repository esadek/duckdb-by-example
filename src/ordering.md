# Ordering

Select all columns from the `customers` table, ordered by `city` (ascending):

```sql
SELECT *
FROM customers
ORDER BY city;
```

Select all columns from the `customers` table, ordered by `city` (descending):

```sql
SELECT *
FROM customers
ORDER BY city DESC;
```

Select all columns from the `customers` table, ordered by `country` then `city`:

```sql
SELECT *
FROM customers
ORDER BY country, city;
```
