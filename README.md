# Quering imported (docx) postgresql dump


1. Converting .docx file to .txt (Sublime)
2. Importing .txt dump file with psql
3. Running psql
4. Making a query
```
    select * from jsontest where(to_jsonb->>'b')::int =0 and(to_jsonb->>'c')::int =0;
```




![Alt Text](https://i.imgur.com/fqv8hRw.gif)
