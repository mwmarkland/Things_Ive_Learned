# Reference
[A Great Vim Cheat Sheet](http://vimsheet.com/)
# Basics


`j` - down
`k` - up
`l` - left
`h` - right
`0` - start of line.
`$` - end of line.
`gg` - go to the top of file.
`G` - go to the bottom of the file.

`x` - delete character under cursor.
`X` - delete previous character (i.e. backspace)
`r` - replace character under cursor.
`dd` - delete line
`i` - insert mode
`:e` - edit new file
`yy` - yank (copy) a line
`p` - paste

`<num>gg` - goto line <num>

Remember you can add numbers to repeat the command for so many lines.



# File tabs
`:tabe` - open in new tab.
`:tabc` - close current tab.
`:tab[tT]` - next/prev tab.

# Edit :e
`:e <filename` open a file in the directory that vim was started in.
`:e .` - gives a file listing you can select a file from.

# Reindent a file.

`ggVG=`
