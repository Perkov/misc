# Quering imported (docx) postgresql dump


1. Converting .docx file to .txt (Sublime)
2. Importing .txt dump file with psql
3. Running psql
4. Making a query
```
select * from jsontest where(to_jsonb->>'b')::int =0 and(to_jsonb->>'c')::int =0;
```




![Alt Text](blob:https://imgur.com/333dd610-13b0-4885-b874-75829846f375)
