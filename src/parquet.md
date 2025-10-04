# Parquet

Read a single Parquet file:

```sql
SELECT *
FROM 'my_file.parquet';
```

Read multiple Parquet files as a single table:

```sql
SELECT *
FROM read_parquet(['file1.parquet', 'file2.parquet']);
```

Read all Parquet files that match the glob pattern:

```sql
SELECT *
FROM 'my_files/*.parquet';
```

Write the results of a query to a Parquet file:

```sql
COPY (
  SELECT *
  FROM penguins
) TO 'penguins.parquet' (FORMAT parquet);
```
