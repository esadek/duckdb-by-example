# CSV

Read a CSV file and auto-infer options:

```sql
SELECT *
FROM 'penguins.csv';
```

Read a CSV file from a URL and auto-infer options:

```sql
SELECT *
FROM 'http://blobs.duckdb.org/data/penguins.csv';
```

Read a CSV file with custom options:

```sql
SELECT *
FROM read_csv('http://blobs.duckdb.org/data/penguins.csv', nullstr = 'NA');
```
