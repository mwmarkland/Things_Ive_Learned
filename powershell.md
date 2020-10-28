# PowerShell
[Starting Powershell from Explorer](http://stackoverflow.com/questions/183901/how-to-start-powershell-from-windows-explorer)
Alt+D, `powershell` or `powershell_ise`

And opposite, in powershell enter `ii .` to start an explorer window.

## Command Equivalents
`grep` => `Select-String` [ShellHacks](https://www.shellhacks.com/windows-grep-equivalent-cmd-powershell/)

`find` => `Get-ChildItem` There are many aliases `ls`, `dir`, `gc`. 
- Example: `gci -Path "C:\Users\"  -Recurse | where {$_.Name -like '*essential*'}`

## Web Resources

### Learning

[Microsoft Virtual Academy -- Getting Started with PowerShell 3.0](https://mva.microsoft.com/liveevents/powershell-jumpstart)

[Windows PowerShell Survival Guide](http://social.technet.microsoft.com/wiki/contents/articles/183.windows-powershell-survival-guide.aspx)
