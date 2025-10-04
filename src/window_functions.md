# Window Functions

Generate a `row_number` column to enumerate rows:

```sql
SELECT
  row_number() OVER (),
  *
FROM penguins;
```

Generate a `row_number` column to enumerate rows, ordered by `bill_length_mm`:

```sql
SELECT
  row_number() OVER (ORDER BY bill_length_mm),
  *
FROM penguins;
```
