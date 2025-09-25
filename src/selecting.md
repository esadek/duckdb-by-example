# Selecting

Select all columns from the `customers` table:

```sql
SELECT *
FROM customers;
```

Select the `first_name` and `city` columns from the `customers` table:

```sql
SELECT
  first_name,
  city
FROM customers;
```

Select the first 10 rows from the `customers` table:

```sql
SELECT *
FROM customers
LIMIT 10;
```

Select all unique `city` values from the `customers` table:

```sql
SELECT DISTINCT city
FROM customers;
```

Select all columns except the `city` column from the `customers` table:

```sql
SELECT * EXCLUDE (city)
FROM customers;
```

Select all columns from the `customers` table, but replace `city` with `lower(city)`:

```sql
SELECT * REPLACE (lower(city) AS city)
FROM customers;
```
