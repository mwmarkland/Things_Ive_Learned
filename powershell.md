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

`which` -> `Get-Command`-> [Stack Overflow](https://stackoverflow.com/questions/11242368/test-if-executable-is-in-path-in-powershell)

## Useful commands
### Archives
[How to zip and unzip files using Powershell](https://www.howtogeek.com/670314/how-to-zip-and-unzip-files-using-powershell/)
Expand a zipped directory/file: `Expand-Archive -Force C:\path\to\archive.zip C:\where\to\extract\to`
- Looks like there is a `Compress-Archive` also.
- Looks like there is a `tar` command also.

## Tips/Hints
### Convert EBCDIC to ASCII
  $Buffer = Get-Content $SourceFileName -Encoding byte
  $Encoding = [System.Text.Encoding]::GetEncoding("IBM037")
  $String = $Encoding.GetString($Buffer)

Could probably pipe GetString into `clip` and then past into Notepad perhaps? Can send to VSCode by piping into `code -`.

## Calling an executable with spaces in path
`& "C:\Program Files\Adobe\Acrobat DC\Acrobat\Acrobat.exe" .\4_Ls_Retrospective_Template.pdf`

### Select-String line limit
By default `Select-String` will limit the size of the output line to match the console size even if you are piping it into something else. Here is an example that gets around that.

`Select-String "cpassx" .\PASCAL_VM_7.6_VM_compiler_scan.20240522.txt |Select-Object -ExpandProperty line | code -`

## Web Resources

### Learning

[Microsoft Virtual Academy -- Getting Started with PowerShell 3.0](https://mva.microsoft.com/liveevents/powershell-jumpstart)

[Windows PowerShell Survival Guide](http://social.technet.microsoft.com/wiki/contents/articles/183.windows-powershell-survival-guide.aspx)

[TutorialsPoint tutorial](https://www.tutorialspoint.com/powershell/index.htm)
