## Exercise:


##### Question: How many orders were made by customer 7888, 1082, 12808, 9623


```python
SELECT COUNT(orderid)
FROM orders
WHERE customerid IN (7888, 1082, 12808, 9623)
```


##### Question: How many cities are in the district of Zuid-Holland, Noord-Brabant and Utrecht?


```python
SELECT COUNT(id)
FROM city
WHERE district IN ('Zuid-Holland', 'Noord-Brabant', 'Utrecht');
```