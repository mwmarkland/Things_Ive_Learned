# HOME and APPDATA

So, if you don't set something to override the HOME environment variable these are set to a default value:

HOME -- C:\Users\$USERNAME\AppData\Roaming
APPDATA -- C:\Users\$USERNAME\AppData\Roaming

because these directories are ensured to be available and follow you in the network.

# SSH
`c:\Users\$USERNAME\.ssh`: the place for the config

# Windows Terminal
[Starting from explorer](https://blog.mzikmund.com/2020/01/tip-launch-windows-terminal-quickly-from-file-explorer/)

# Colors
Color Tool from Microsoft is helpful.
https://github.com/Microsoft/console/releases/tag/1708.14008

# Printing
## How to clear the spooler and reset.
```
net stop spooler
del /F /S /Q %systemroot%\system32\spool\printers
net start spooler
```
# Development

## WSL Stuff
Resetting underlying service if you get a blank window: `Get-Service LxssManager | Restart-Service` or `wsl --shutdown`

Setting up VSCode connection, type `code .` in the WSL window to get the server stuff installed.

## ldd equivalent
Git for Windows bash shell supports `ldd`.

If you have visual studio, `dumpbin /dependents` is the way to go apparently.

## Visual Studio
### Debug versus Release builds.
Builds are often debug by default which means the libraries created aren't portable to other machines. Look for a trailing `D` on the library depenencies.
`VCRUNTIME140D.dll` for example.

Also when you are setting up options for builds via the preferences menus it is easy to setup stuff for the wrong build type or wrong target (or both) you have to be careful to make sure the preferences pane matches what you really want to target.

### Linking issues.
A function name with `__impl_` mangled to it means it has been marked with dllimport and is expected to come from a DLL.

# Various useful commands
`driverquery`
`sfc \scannow`: *System File Checker*
`netsh wlan show profile`
`systeminfo`
