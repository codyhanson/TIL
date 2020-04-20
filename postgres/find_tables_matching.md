4/20/2020
# Today I learned how to find tables that match a certain pattern


```
SELECT table_schema, table_name
FROM information_schema.tables
WHERE table_name ilike '%findme%'
```
