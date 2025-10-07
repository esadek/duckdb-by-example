# TSV

Read a TSV file:

```sql
SELECT *
FROM read_csv('penguins.tsv', delim = '\t');
```

Write a table to a TSV file:

```sql
COPY penguins TO 'penguins.tsv' (DELIMITER '\t');
```
