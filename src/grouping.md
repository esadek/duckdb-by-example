# Grouping

Count the number of entries in the `customers` table for each `first_name`:

```sql
SELECT
  first_name,
  count(*)
FROM customers
GROUP BY first_name;
```
