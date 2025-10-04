# Ordering

Select all columns from the `penguins` table, ordered by `bill_length_mm` (ascending):

```sql
SELECT *
FROM penguins
ORDER BY bill_length_mm;
```

Select all columns from the `penguins` table, ordered by `bill_length_mm` (descending):

```sql
SELECT *
FROM penguins
ORDER BY bill_length_mm DESC;
```

Select all columns from the `penguins` table, ordered by `species` then `bill_length_mm`:

```sql
SELECT *
FROM penguins
ORDER BY species, bill_length_mm;
```
