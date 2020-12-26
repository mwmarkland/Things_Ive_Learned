# PowerShell
[Starting Powershell from Explorer](http://stackoverflow.com/questions/183901/how-to-start-powershell-from-windows-explorer)
Alt+D, `powershell` or `powershell_ise`
Alt-F, R (from Explorer)

And opposite, in powershell enter `ii .` to start an explorer window.

## Command Equivalents
`grep` => `Select-String` [ShellHacks](https://www.shellhacks.com/windows-grep-equivalent-cmd-powershell/)

`find` => `Get-ChildItem` There are many aliases `ls`, `dir`, `gc`. 
- Example: `gci -Path "C:\Users\"  -Recurse | where {$_.Name -like '*essential*'}`

`grep x *.md | cut -f1 -d':'` is equivalent to `Select-String "x" *.md | ForEach-Object {$_.ToString().split(":")[1]}`
The interesting thing with this one is that `Select-String` returns a `MatchInfo` object so you have to convert it to a string to be able to run `split` on it.

## Web Resources

### Learning

[Microsoft Virtual Academy -- Getting Started with PowerShell 3.0](https://mva.microsoft.com/liveevents/powershell-jumpstart)

[Windows PowerShell Survival Guide](http://social.technet.microsoft.com/wiki/contents/articles/183.windows-powershell-survival-guide.aspx)

[TutorialsPoint tutorial](https://www.tutorialspoint.com/powershell/index.htm)
