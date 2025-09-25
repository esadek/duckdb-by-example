# Filtering

Select all rows from the `customers` table where the `city` is "Amsterdam":

```sql
SELECT *
FROM customers
WHERE city = 'Amsterdam';
```

Select all rows from the `customers` table where the `customer_id` is 6 or 7:

```sql
SELECT *
FROM customers
WHERE
  customer_id = 6
  OR customer_id = 7;
```

Select all rows from the `customers` table where the `first_name` includes "mark" (case-sensitive):

```sql
SELECT *
FROM customers
WHERE first_name LIKE '%mark%';
```

Select all rows from the `customers` table where the `first_name` includes "mark" (case-insensitive):

```sql
SELECT *
FROM customers
WHERE first_name ILIKE '%mark%';
```
