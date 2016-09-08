# SQL 
## Sources

- O'Reilly *Learning SQL* book.

## Basics

SQL is not a procedural language; you describe what you want to retrieve and what needs to be accessed, but the best way to execute the query is decided on by the server; it chooses the *driving table* which is the starting point of the query optimization.

You can force the order with extensions to SQL on various platforms.

## Joins

### Cross Joins

You can join two tables without expressing any key-based
relationship. This will generate a *cartesian product* of the tables
which is every permutation of the items from the tables.

~~~
SELECT e.fname, e.lname, d.name
FROM employee e JOIN department d;
~~~

### Inner Joins

Here you describe how the two tables are related. Here the `dept\_id` entry in the `employee` table is a *foreign key* to the `department` table. Foreign keys serve as *bridges* between tables which allow for joins.

The following is an **inner join**; if the value exists for the `dept\_id` in one table and not the other, then the join fails for the rows containing that value and those rows are *excluded* from the result set.

If you want to include all rows from one table or the other regardless of match you have to use an **outer join**.

~~~
SELECT e.fname, e.lname, d.name
FROM employee e JOIN department d
    ON e.dept_id = d.dept_id;
~~~

or more explicitly

~~~
SELECT e.fname, e.lname, d.name
FROM employee e INNER JOIN department d
    ON e.dept_id = d.dept_id;
~~~

Most servers do an inner join by default if you don't specify.

If the columns have the same name between tables you use a `USING` subclause.

~~~
SELECT e.fname, e.lname, d.name
FROM employee e INNER JOIN department d
    USING (dept_id);
~~~

Multiple table joins look something like this

~~~
SELECT a.account_id, c.fed_id, e.fname, e.lname
FROM account a INNER JOIN customer c
    ON a.cust_id = c.cust_id
    INNER JOIN employee e
    ON a.open_emp_id = e.emp_id
WHERE c.cust_type_cd = 'B';
~~~
