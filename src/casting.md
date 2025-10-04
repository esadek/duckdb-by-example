# Casting

Cast the `bill_length_mm` column to `VARCHAR`:

```sql
SELECT CAST(bill_length_mm AS VARCHAR)
FROM penguins;
```

Cast the `body_mass_g` column to `DOUBLE`:

```sql
SELECT body_mass_g::DOUBLE
FROM penguins;
```
