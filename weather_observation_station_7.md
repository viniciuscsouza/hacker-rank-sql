[Link to Challenge](https://www.hackerrank.com/challenges/weather-observation-station-7/)

```sql
SELECT DISTINCT CITY
    FROM STATION
    WHERE RIGHT(CITY, 1) IN ('A','E','I','O','U');
```
