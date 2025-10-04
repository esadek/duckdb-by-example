# Common Table Expressions

Create a CTE named `people` and use it in the main query:

```sql
WITH chinstrap_penguins AS (
  SELECT *
  FROM penguins
  WHERE species = 'Chinstrap'
)
SELECT *
FROM chinstrap_penguins;
```
