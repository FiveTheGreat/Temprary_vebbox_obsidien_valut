CTE stands for Common Table Expression

**What is Common Table Expression in SQL ?**
	A Common Table Expression is liked a `named subquery`. It functions as a virtual table that only its main query can access. CTEs can help simplify, shorten, and organize your code.

A **common table expression**, or CTE, is a temporary named result set created from a simple `SELECT` statement that can be used in a subsequent `SELECT` statement. Each SQL CTE is like a **named query**, whose result is stored in a virtual table (a CTE) to be referenced later in the main query.

The best way to learn common table expressions is through practice. I recommend LearnSQL.com's interactive [Recursive Queries](https://learnsql.com/course/common-table-expressions/) course.

### CTE Help Simplify Queries
Learnig CTE below example:

Table Name : sales
![[Pasted image 20240809154446.png]]

Code:
```SQL
WITH highest AS(
	SELECT branch, data, MAX(unit_price) AS highest price 
	FROM sales GROUP BY branch, date
)SELECT 
	sales.*
```
