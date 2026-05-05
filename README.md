# SQL Lab Assessment

## Project Overview
This project demonstrates SQL querying skills using Python and SQLite across three different databases. The lab covers fundamental and advanced SQL operations for data retrieval, filtering, and analysis.

## Databases Used

### 1. data.sqlite (Northwinds Company)
Employee and order data for the fictional Northwinds Company.

**Skills demonstrated:**
- Basic SELECT queries
- Column aliasing with `AS`
- `CASE` statements for data transformation
- String functions (`LENGTH`, `SUBSTR`)
- Aggregate functions (`SUM`, `ROUND`)
- Date formatting with `STRFTIME`

### 2. planets.db (Solar System Planets)
Planetary data including moons, mass, and color.

**Skills demonstrated:**
- `WHERE` clause filtering
- Comparison operators (`<=`, `>=`)
- Logical operators (`AND`)
- Pattern matching with `LIKE`
- `LENGTH()` function

### 3. dogs.db (Fictional Dogs)
Data about famous fictional dog characters.

**Skills demonstrated:**
- Filtering with binary flags
- `BETWEEN` operator
- `ORDER BY` (ASC/DESC)
- `LIMIT` clause
- Subqueries for multi-step sorting

### 4. babe_ruth.db (Babe Ruth Statistics)
Babe Ruth's baseball career statistics by year and team.

**Skills demonstrated:**
- `COUNT(DISTINCT)` for unique values
- `SUM()` for totals
- `AVG()` for averages
- `GROUP BY` for aggregation
- `HAVING` for filtering grouped results

## Key SQL Concepts Covered

| Concept | Description |
|---------|-------------|
| `SELECT` | Retrieve columns from a table |
| `WHERE` | Filter rows based on conditions |
| `AS` | Alias columns or tables |
| `CASE` | Conditional logic in queries |
| `ORDER BY` | Sort results (ASC/DESC) |
| `LIMIT` | Restrict number of returned rows |
| `GROUP BY` | Group rows for aggregation |
| `HAVING` | Filter grouped results |
| `LIKE` | Pattern matching with wildcards |
| `BETWEEN` | Range filtering |
| `LENGTH()` | String length function |
| `SUBSTR()` | Extract substring |
| `SUM()`, `AVG()`, `COUNT()` | Aggregate functions |
| `ROUND()` | Round numeric values |
| `STRFTIME()` | Format date values |

## Technologies Used
- Python 3
- Pandas
- SQLite3
- Jupyter Notebook
