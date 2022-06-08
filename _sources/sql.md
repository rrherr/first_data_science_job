# Learn SQL

Here's a list of 5 hands-on SQL tutorials, and comics that explain the concepts for each topic!

## Introduction

### What is SQL?

[Simple English Wikipedia](https://simple.wikipedia.org/wiki/Structured_Query_Language) explains well:

> Structured Query Language (SQL) is a language used to view or change data in databases. The statements used in this language are called SQL queries. 
> 
> This is a simple SQL Query which is used to show all values stored in column named 'my_column' from the data table named 'my_table'.
> 
> ```sql
> SELECT my_column FROM my_table;
> ```

### Why learn SQL?

I agree with this [advice from Vicki Boykis](https://vickiboykis.com/2022/01/09/git-sql-cli/):

> Learn SQL first. You absolutely cannot do any data work until you are able to get data from a source. ...
> 
> Let’s forget about the fancy stuff: 80-90% of the tech industry runs on traditional relational databases ... Once you know how to speak SQL, you can speak to any of them.
> 
> SQL is also hands-down the easiest language for beginners to learn ...

### How to debug SQL queries

Write and debug SQL one step at a time. Follow this [great advice](https://dataschool.com/how-to-teach-people-sql/debugging-sql-0-rows-returned/):

> Whenever you get a result you do not expect in SQL take a second and break down the query into smaller bits. Remove or comment clauses out one by one to find where the query stopped making sense. To comment out a part of your SQL query ... all you do is add two dashes in front of a line of SQL.
>
> ```sql
> SELECT *
> FROM facebook
> --WHERE "# of Friends" > 1000
> ```
>
> This concept of breaking queries into small pieces also works when you are initially creating the query. Start with a query that only contains SELECT, FROM, and LIMIT. Then layer on each additional SQL clause 1 at a time and run it to see if there are any issues. While this practice is slow you are much less likely to run into an issue in your query that you don’t know the cause of.


## 1. SQL Bolt

<table>
  <thead>
    <tr>
      <th>Do exercises</th>
      <th>Read comics</th>
    </tr>
  </thead>
<tr>
<td>
      
  [Introduction to SQL](https://sqlbolt.com/lesson/introduction "Introduction to SQL")  
  [SQL Lesson 1: SELECT queries 101](https://sqlbolt.com/lesson/select_queries_introduction "SQL Lesson 1: SELECT queries 101")

</td>
<td>

  [getting started with SELECT](https://wizardzines.com/comics/getting-started-select/)
  
</td>
</tr>

<tr>
<td>
  
  [SQL Lesson 2: Queries with constraints (Pt. 1)](https://sqlbolt.com/lesson/select_queries_with_constraints "SQL Lesson 2: Queries with constraints (Pt. 1)")  
  [SQL Lesson 3: Queries with constraints (Pt. 2)](https://sqlbolt.com/lesson/select_queries_with_constraints_pt_2 "SQL Lesson 3: Queries with constraints (Pt. 2)")

</td>
<td>
  
  [WHERE](https://wizardzines.com/comics/where/)
  
</td>
</tr>

<tr>
<td>
  
  [SQL Lesson 4: Filtering and sorting Query results](https://sqlbolt.com/lesson/filtering_sorting_query_results "SQL Lesson 4: Filtering and sorting Query results")  
  [SQL Review: Simple SELECT Queries](https://sqlbolt.com/lesson/select_queries_review "SQL Review: Simple SELECT Queries")
  
</td>
<td>
  
  [ORDER BY and LIMIT](https://wizardzines.com/comics/order-by-limit/)
  
</td>
</tr>
 
<tr>
<td>
  
  [SQL Lesson 6: Multi-table queries with JOINs](https://sqlbolt.com/lesson/select_queries_with_joins "SQL Lesson 6: Multi-table queries with JOINs")  
  [SQL Lesson 7: OUTER JOINs](https://sqlbolt.com/lesson/select_queries_with_outer_joins "SQL Lesson 7: OUTER JOINs")
  
</td>
<td>
  
  [my rules for simple JOINs](https://wizardzines.com/comics/joins/)  
  [INNER JOIN and LEFT JOIN](https://wizardzines.com/comics/inner-left-join/)  
  [SQL example: LEFT JOIN + GROUP BY](https://wizardzines.com/comics/example-join/)
  
</td>
</tr>

<tr>
<td>
  
  [SQL Lesson 8: A short note on NULLs](https://sqlbolt.com/lesson/select_queries_with_nulls "SQL Lesson 8: A short note on NULLs")
  
</td>
<td>
  
  [NULL: unknown or missing](https://wizardzines.com/comics/null-unknown-missing/)  
  [NULL surprises](https://wizardzines.com/comics/null-surprises/)  
  [questions to ask about your data](https://wizardzines.com/comics/questions-to-ask/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL Lesson 9: Queries with expressions](https://sqlbolt.com/lesson/select_queries_with_expressions "SQL Lesson 9: Queries with expressions")

</td>
<td>
  
  [SELECT](https://wizardzines.com/comics/select/)  
  [WHERE](https://wizardzines.com/comics/where/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL Lesson 10: Queries with aggregates (Pt. 1)](https://sqlbolt.com/lesson/select_queries_with_aggregates "SQL Lesson 10: Queries with aggregates (Pt. 1)")

</td>
<td>
  
  [GROUP BY](https://wizardzines.com/comics/group-by/)  
  [SQL example: LEFT JOIN + GROUP BY](https://wizardzines.com/comics/example-join/)  
  [SQL: ways to count](https://wizardzines.com/comics/ways-to-count/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL Lesson 11: Queries with aggregates (Pt. 2)](https://sqlbolt.com/lesson/select_queries_with_aggregates_pt_2 "SQL Lesson 11: Queries with aggregates (Pt. 2)")

</td>
<td>
  
  [HAVING](https://wizardzines.com/comics/having/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL Lesson 12: Order of execution of a Query](https://sqlbolt.com/lesson/select_queries_order_of_execution "SQL Lesson 12: Order of execution of a Query")
  
</td>
<td>
  
  [SELECT queries start with FROM](https://wizardzines.com/comics/sql-query-order/)
  
</td>
</tr>
</table>

## 2. Select Star SQL

<table>
  <thead>
    <tr>
      <th>Do exercises</th>
      <th>Read comics</th>
    </tr>
  </thead>

<tr>
<td>
  
  [Select Star SQL](https://selectstarsql.com/frontmatter.html)  
  [Chapter 1: Beazley's Last Statement](https://selectstarsql.com/beazley.html)
  
</td>
<td>
  
  [getting started with SELECT](https://wizardzines.com/comics/getting-started-select/)  
  [SELECT](https://wizardzines.com/comics/select/)  
  [WHERE](https://wizardzines.com/comics/where/)  
  [single quote your strings](https://wizardzines.com/comics/single-quote/)
  
</td>
</tr>
  
<tr>
<td>
  
  [Chapter 2: Claims of Innocence](https://selectstarsql.com/innocence.html)
  
</td>
<td>
  
  [SQL: ways to count](https://wizardzines.com/comics/ways-to-count/)  
  [NULL: unknown or missing](https://wizardzines.com/comics/null-unknown-missing/)  
  [NULL surprises](https://wizardzines.com/comics/null-surprises/)  
  [CASE](https://wizardzines.com/comics/case/)
  
</td>
</tr>
  
<tr>
<td>
  
  [Chapter 3: The Long Tail](https://selectstarsql.com/longtail.html)
  
</td>
<td>
  
  [GROUP BY](https://wizardzines.com/comics/group-by/)  
  [HAVING](https://wizardzines.com/comics/having/)  
  [SELECT queries start with FROM](https://wizardzines.com/comics/sql-query-order/)  
  [ORDER BY and LIMIT](https://wizardzines.com/comics/order-by-limit/)  
  [subqueries](https://wizardzines.com/comics/subqueries/)
  
</td>
</tr>
  
<tr>
<td>
  
  [Chapter 4: Execution Hiatuses](https://selectstarsql.com/hiatuses.html)
  
</td>
<td>
  
  [my rules for simple JOINs](https://wizardzines.com/comics/joins/)  
  [INNER JOIN and LEFT JOIN](https://wizardzines.com/comics/inner-left-join/)  
  [SQL example: LEFT JOIN + GROUP BY](https://wizardzines.com/comics/example-join/)  
  [questions to ask about your data](https://wizardzines.com/comics/questions-to-ask/)

</td>
</tr>

</table>


## 3. Mode intermediate tutorial

<table>
  <thead>
    <tr>
      <th>Do exercises</th>
      <th>Read comics</th>
    </tr>
  </thead>

<tr>
<td>
  
  [SQL for Data Analysis: Tutorial Introduction - Mode](https://mode.com/sql-tutorial/introduction-to-sql/)  
  [Using SQL in Mode | Basic SQL - Mode](https://mode.com/sql-tutorial/sql-in-mode/)  
  [Putting it together | Intermediate SQL - Mode](https://mode.com/sql-tutorial/intro-to-intermediate-sql/)  
  [SQL Aggregate Functions | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-aggregate-functions/)  
  [SQL COUNT | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-count/)  
  [SQL SUM | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-sum/)
  
</td>
<td>
  
  [SQL: ways to count](https://wizardzines.com/comics/ways-to-count/)  
  [single quote your strings](https://wizardzines.com/comics/single-quote/)
  
</td>
</tr>
  
<tr>
<td>
    
  [SQL MIN/MAX | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-min-max/)  
  [SQL AVG | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-avg/)  
  [SQL GROUP BY | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-group-by/)
  
</td>
<td>
  
  [GROUP BY](https://wizardzines.com/comics/group-by/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL HAVING | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-having/)
  
</td>
<td>
  
  [HAVING](https://wizardzines.com/comics/having/)  
  [SELECT queries start with FROM](https://wizardzines.com/comics/sql-query-order/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL CASE | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-case/)
  
</td>
<td>
  
  [CASE](https://wizardzines.com/comics/case/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL DISTINCT | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-distinct/)
  
</td>
<td>
  
  [SQL: ways to count](https://wizardzines.com/comics/ways-to-count/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL Joins | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-joins/)  
  [SQL INNER JOIN | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-inner-join/)  
  [SQL Outer Joins | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-outer-joins/)  
  [SQL LEFT JOIN | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-left-join/)  
  [SQL RIGHT JOIN | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-right-join/)  
  [SQL Joins Using WHERE or ON | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-joins-where-vs-on/)  
  [SQL FULL OUTER JOIN | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-full-outer-join/)  
  [SQL UNION | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-union/)  
  [SQL Joins with Comparison Operators | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-join-comparison-operators/)  
  [SQL Joins on Multiple Keys | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-joins-on-multiple-keys/)  
  [SQL Self Joins | Intermediate SQL - Mode](https://mode.com/sql-tutorial/sql-self-joins/)
  
</td>
<td>
  
  [my rules for simple JOINs](https://wizardzines.com/comics/joins/)  
  [INNER JOIN and LEFT JOIN](https://wizardzines.com/comics/inner-left-join/)  
  [SQL example: LEFT JOIN + GROUP BY](https://wizardzines.com/comics/example-join/)  
  [NULL: unknown or missing](https://wizardzines.com/comics/null-unknown-missing/)  
  [NULL surprises](https://wizardzines.com/comics/null-surprises/)  
  [questions to ask about your data](https://wizardzines.com/comics/questions-to-ask/)
  
</td>
</tr>

</table>


## 4. Mode advanced tutorial

<table>
  <thead>
    <tr>
      <th>Do exercises</th>
      <th>Read comics</th>
    </tr>
  </thead>

<tr>
<td>
  
  [Leveling up | Advanced SQL - Mode](https://mode.com/sql-tutorial/intro-to-advanced-sql/)  
  [SQL Data Types | Advanced SQL - Mode](https://mode.com/sql-tutorial/sql-data-types/)  
  [SQL Date Format | Advanced SQL - Mode](https://mode.com/sql-tutorial/sql-datetime-format/)  
  [Data Wrangling with SQL | Advanced SQL - Mode](https://mode.com/sql-tutorial/data-wrangling-with-sql/)  
  [Using SQL String Functions to Clean Data | Advanced SQL - Mode](https://mode.com/sql-tutorial/sql-string-functions-for-cleaning/)

</td>
<td>
  
  [SELECT](https://wizardzines.com/comics/select/)  
  [COALESCE](https://wizardzines.com/comics/coalesce/)
  
</td>
</tr>
  
<tr>
<td>
  
  [Writing Subqueries in SQL | Advanced SQL - Mode](https://mode.com/sql-tutorial/sql-sub-queries/)
  
</td>
<td>
  
  [subqueries](https://wizardzines.com/comics/subqueries/)
  
</td>
</tr>
  
<tr>
<td>
  
  [SQL Window Functions | Advanced SQL - Mode](https://mode.com/sql-tutorial/sql-window-functions/)
  
</td>
<td>
  
  [window functions](https://wizardzines.com/comics/window-functions-intro/)  
  [OVER() assigns every row a window](https://wizardzines.com/comics/over-assigns-window/)  
  [SQL example: get the time between baby feedings](https://wizardzines.com/comics/example-baby-feedings/)
  
</td>
</tr>
  
<tr>
<td>
  
  [Performance Tuning SQL Queries | Advanced SQL - Mode](https://mode.com/sql-tutorial/sql-performance-tuning/)
  
</td>
<td>
  
  [how indexes make your queries fast](https://wizardzines.com/comics/indexes/)  
  [EXPLAIN](https://wizardzines.com/comics/explain/)
  
</td>
</tr>
  
<tr>
<td>
  
  [Pivoting Data in SQL | Advanced SQL - Mode](https://mode.com/sql-tutorial/sql-pivot-table/)
  
</td>
<td>
  
  [subqueries](https://wizardzines.com/comics/subqueries/)  
  [SQL: ways to count](https://wizardzines.com/comics/ways-to-count/)
  
</td>
</tr>

</table>


## 5. SQL Bolt continued

<table>
  <thead>
    <tr>
      <th>Do exercises</th>
    </tr>
  </thead>

<tr>
<td>
  
[SQL Lesson 13: Inserting rows](https://sqlbolt.com/lesson/inserting_rows "SQL Lesson 13: Inserting rows")  
[SQL Lesson 14: Updating rows](https://sqlbolt.com/lesson/updating_rows "SQL Lesson 14: Updating rows")  
[SQL Lesson 15: Deleting rows](https://sqlbolt.com/lesson/deleting_rows "SQL Lesson 15: Deleting rows")  
[SQL Lesson 16: Creating tables](https://sqlbolt.com/lesson/creating_tables "SQL Lesson 16: Creating tables")  
[SQL Lesson 17: Altering tables](https://sqlbolt.com/lesson/altering_tables "SQL Lesson 17: Altering tables")  
[SQL Lesson 18: Dropping tables](https://sqlbolt.com/lesson/dropping_tables "SQL Lesson 18: Dropping tables")  
  
</td>
</tr>
</table>
