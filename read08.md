
# SQL
- is A Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

![](https://www.tutorialrepublic.com/lib/images/sql-illustration.png)

## Relational databases
- A relational database represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.

- By learning SQL, the goal is to learn how to answer specific questions about this data, like "What types of vehicles are on the road have less than four wheels?" or "How many models of cars does Tesla produce?", to help us make better decisions down the road.

- statements, which are often colloquially refered to as queries. A query in itself is just a statement which declares what data we are looking for, where to find it in the database, and optionally, how to transform it before it is returned.

- EX:
1. Select query for a specific columns SELECT column, another_column, … FROM mytable;

2. Select query for all columns SELECT * FROM mytable

### NOTE:
- Each database has its own supported set of mathematical, string, and date functions that can be used in a query, which you can find in their own respective docs.

## Filtering and sorting Query results:
- We can specify one or more than one column in the ORDER BY clause. The columns and their sorting order must be separated by comma (,). We can specify different sorting orders for the individual column. For example, if you want to sort the first column in ascending order and second column in descending order,
- Another clause which is commonly used with the ORDER BY clause are the LIMIT and OFFSET clauses, which are a useful optimization to indicate to the database the subset of the results you care about. 
- SELECT DISTINCT column_name prevents duplicate column values
- use ORDER BY to sort results with ABC, alphabetical, ASC/DESC, ascending/descending
- use LIMIT to limit the number of rows returned
- use OFFSET to specify where to begin counting rows from

![](https://s33046.pcdn.co/wp-content/uploads/2020/07/sort-and-filter-order-by-on-expression-624x346.png)


## OUTER JOINS:
Depending on how you want to analyze the data, the INNER JOIN we used last lesson might not be sufficient because the resulting table only contains data that belongs in both of the tables.

![](https://dotnettutorials.net/wp-content/uploads/2019/06/c-users-pranaya-pictures-left-outer-join-in-linq-.png)

## Tables
- You can create a new table using the CREATE TABLE statement as shown below:

### CREATE TABLE IF NOT EXISTS 
```
- ( mytable 
    column DataType TableConstraint DEFAULT default_value,
    another_column DataType TableConstraint DEFAULT default_value,
    …
    );
    ```
- The structure of the new table is defined by its table schema, which defines a series of columns. Each column has a name, the type of data allowed in that column, an optional table constraint on values being inserted, and an optional default value. If by any chance there was already a table with the same name, the SQL implementation will usually throw an error, so to suppress the error and skip creating a table if one exists, you can use the IF NOT EXISTS clause.

----------------------------------------


[Table Of Content](https://github.com/omarXzain/301-reading-notes)

Just like you would like you to create new tables, you can also remove entire tables using the DROP TABLE statement (you can also add IF EXISTS to this statement as well).
