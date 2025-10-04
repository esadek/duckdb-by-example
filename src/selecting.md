# Selecting

Select all columns from the `penguins` table:

```sql
SELECT *
FROM penguins;
```

Select the `species` and `island` columns from the `penguins` table:

```sql
SELECT
  species,
  island
FROM penguins;
```

Select the first 10 rows from the `penguins` table:

```sql
SELECT *
FROM penguins
LIMIT 10;
```

Select all unique `species` values from the `penguins` table:

```sql
SELECT DISTINCT species
FROM penguins;
```

Select all columns except the `island` column from the `penguins` table:

```sql
SELECT * EXCLUDE (island)
FROM penguins;
```

Select all columns from the `penguins` table, but replace `species` with `lower(species)`:

```sql
SELECT * REPLACE (lower(species) AS species)
FROM penguins;
```
