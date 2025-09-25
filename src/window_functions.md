# Window Functions

Generate a `row_number` column to enumerate rows:

```sql
SELECT
  row_number() OVER (),
  *
FROM customers;
```

Generate a `row_number` column to enumerate rows, ordered by `created_at`:

```sql
SELECT
  row_number() OVER (ORDER BY created_at),
  *
FROM customers;
```
