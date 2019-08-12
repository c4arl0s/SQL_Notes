# SQL_Notes
SQL_Notes

# ALTER TABLE lets you add columns to a table in a database

``` sql
ALTER TABLE table_name
ADD column_name datatype;
```

# AND is an operator that combines two conditions. Both conditions must be true for the row to be included in the result set

``` sql
SELECT column_name(s)
FROM table_name
WHERE column_1 = value_1
  AND column_2 = value_2;
```
# AS is a keyword in SQL that allows you to rename a column of table using an alias.

``` sql
SELECT column_name AS 'Alias'
FROM table_name;
```

# AVG() is an aggregate function that returns the average value for a numeric column.

``` sql
SELECT AVG(column_name)
FROM table_name;
```

# The BETWEEN operator is used to filter the result set within a certain range. The values can be numbers, text or dates.

``` sql
SELECT column_name(s)
FROM table_name
WHERE column_name BETWEEN
      value_1 AND value_2;
```




