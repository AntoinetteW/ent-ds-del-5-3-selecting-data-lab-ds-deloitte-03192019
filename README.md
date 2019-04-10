
# Selecting Data - Lab


## Introduction 

NASA wants to go to Mars! Before they build their rocket, NASA needs to track information about all of the planets in the Solar System. In this lab, you'll practice querying the database with various SELECT statements. This will include selecting different columns, and employing other SQL clauses like WHERE to return the data desired.

## Objectives
You will be able to:
* Retrieve all the information from a table
* Retrieve a subset of records from a table using a `WHERE` clause
* Retrieve a subset of columns from a table

## Connecting to the Database

To get started, connect to the database titled `planets.db`. Don't forget to also make a cursor so that you can later execute your queries.


```python
#Your code here
```

## Selecting Data

Here's an overview of the planet's table you'll be querying.

|name   |color |num_of_moons|mass|rings|
|-------|-------|-------|-------|-------|
|Mercury|gray   |0      |0.55   |no     |
|Venus  |yellow |0      |0.82   |no     |
|Earth  |blue   |1      |1.00   |no     |
|Mars   |red    |2      |0.11   |no     |
|Jupiter|orange |67     |317.90 |no     |
|Saturn |hazel  |62     |95.19  |yes    |
|Uranus |light blue|27  |14.54  |yes    |
|Neptune|dark blue|14   |17.15  |yes    |

Write SQL queries for each of the statements below.

## Select just the name and color of each planet


```python
#Your code here
```

## Select all columns for each planet whose mass is greater than 1.00



```python
#Your code here
```

## Select the name and mass of each planet whose mass is less than or equal to 1.00


```python
#Your code here
```

## Select the name and color of each planet that has more than 10 moons


```python
#Your code here
```

## Select the planet that has at least one moon and a mass less than 1.00


```python
#Your code here
```

## Select the name and color of planets that have a color of blue, light blue, or dark blue


```python
#Your code here
```

## Summary

Congratulations! NASA is one step closer to embarking upon its mission to Mars. In this lab, You practiced writing select statements that query a single table to get specific information. You also used other clauses and specified column names to cherry pick the data we wanted to retrieve. 
