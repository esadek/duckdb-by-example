# Common Table Expressions

Create a CTE named `people` and use it in the main query:

```sql
WITH people AS (
  SELECT 'Mark' AS first_name
)
SELECT *
FROM people;
```
