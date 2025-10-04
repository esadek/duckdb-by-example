# Aggregation

Select the average of the `bill_length_mm` column:

```sql
SELECT avg(bill_length_mm)
FROM penguins;
```

Select the maximum of the `bill_length_mm` column, grouped by `species`:

```sql
SELECT
  species,
  max(bill_length_mm)
FROM penguins
GROUP BY species;
```
