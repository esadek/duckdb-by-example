# Grouping

Count the number of entries in the `penguins` table for each `species`:

```sql
SELECT
  species,
  count(*)
FROM penguins
GROUP BY species;
```
