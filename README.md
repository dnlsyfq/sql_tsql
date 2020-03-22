# TSQL

```
SELECT TOP 10 *
  FROM tags
  ORDER BY Count DESC;
```

Sqlite equivalent
```
SELECT *
FROM tags
ORDER BY Count DESC
LIMIT 10;
```
---

# Data StackExchange 

[Stack Exhange Data Explorer](https://data.stackexchange.com/stackoverflow/query/new) uses TSQL for query.

Chose designated table on the right and proceed query in the editor.
```
SELECT * 
FROM Posts
WHERE CreationDate LIKE '%2019%'
;
```