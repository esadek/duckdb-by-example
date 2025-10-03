# Aggregation

Select the sum of the `amount` column:

```sql
SELECT sum(amount)
FROM sales;
```

Select the sum of the `amount` column, grouped by `country`:

```sql
SELECT
  country,
  sum(amount)
FROM sales
GROUP BY country;
```
