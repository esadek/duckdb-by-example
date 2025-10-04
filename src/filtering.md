# Filtering

Select all rows from the `penguins` table where the `species` is "Chinstrap":

```sql
SELECT *
FROM penguins
WHERE species = 'Chinstrap';
```

Select all rows from the `penguins` table where the `year` is 2007 or 2008:

```sql
SELECT *
FROM penguins
WHERE
  year = 2007
  OR year = 2008;
```

Select all rows from the `penguins` table where the `sex` includes "male" (case-sensitive):

```sql
SELECT *
FROM penguins
WHERE sex LIKE '%male%';
```

Select all rows from the `penguins` table where the `sex` includes "male" (case-insensitive):

```sql
SELECT *
FROM penguins
WHERE sex ILIKE '%male%';
```
