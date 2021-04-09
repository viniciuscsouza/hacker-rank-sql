[Link to Challenge](https://www.hackerrank.com/challenges/weather-observation-station-8/)

```sql
SELECT DISTINCT CITY
    FROM STATION
    WHERE RIGHT(CITY, 1) IN ('A','E','I','O','U')
    AND LEFT(CITY, 1) IN ('A','E','I','O','U');
```
