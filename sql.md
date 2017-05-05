# General SQL

# Tools

## SQuireL
A SQL client for databases.
[Web Home](http://squirrel-sql.sourceforge.net/)

I dug a little and to look at the "schema" used to create something,
you can click on the `Source`tab in the `Objects` view.

# Database specific

## sqlite
Experimenting with a new db. Load it with `.open` and the you can do
`.tables` to see the list of tables that are available.

The trick I used to do to get column names (select * from x where
1=0;) does not work. However you can do

`PRAGMA table_info(<tablename>);`

and get a list of columns.


