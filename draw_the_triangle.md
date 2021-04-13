[Link to Challenge](https://www.hackerrank.com/challenges/draw-the-triangle/)

```sql
WITH RECURSIVE rnum(n)
    AS (SELECT 20
            UNION ALL
            SELECT n-1
            FROM rnum
            WHERE n > 1)
SELECT REPEAT('* ', n)
FROM rnum;
```
