[Link to Challenge](https://www.hackerrank.com/challenges/weather-observation-station-9/)

```sql
SELECT DISTINCT CITY
    FROM STATION
    WHERE LEFT(CITY, 1) NOT IN ('A','E','I','O','U');
```
