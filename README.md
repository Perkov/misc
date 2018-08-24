# Quering imported postgresql dump (.docx)


1. Converting .docx file to .txt (Sublime)
2. Importing .txt dump file with psql
3. Running psql
4. Making a query:
```
    select * from jsontest where(to_jsonb->>'b')::int =0 and(to_jsonb->>'c')::int =0;
```
5. Counting number of occurences which satisfy given conditions: 
```
    select count(*) from jsontest where(to_jsonb->>'b')::int =0 and(to_jsonb->>'c')::int =0;
```

STEPS 2-5

![](https://i.imgur.com/vC0pr7D.gif)

