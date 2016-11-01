# Quick notes.

Experimenting with a new db. Load it with `.open` and the you can do `.tables` to see the list of tables that are available. 

The trick I used to do to get column names (select * from x where 1=0;) does not work. However you can do

`PRAGMA table_info(<tablename>);`

and get a list of columns.


