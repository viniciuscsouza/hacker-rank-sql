[Link to Challenge](https://www.hackerrank.com/challenges/weather-observation-station-12/)

```sql
SELECT DISTINCT CITY
    FROM STATION
    WHERE RIGHT(CITY, 1) NOT IN ('A','E','I','O','U')
    AND LEFT(CITY, 1) NOT IN ('A','E','I','O','U');
```
