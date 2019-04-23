# HOME and APPDATA

So, if you don't set something to override the HOME environment variable these are set to a default value:

HOME -- C:\Users\$USERNAME\AppData\Roaming
APPDATA -- C:\Users\$USERNAME\AppData\Roaming

because these directories are ensured to be available and follow you in the network.

# Colors
Color Tool from Microsoft is helpful.
https://github.com/Microsoft/console/releases/tag/1708.14008

# Development

## ldd equivalent
Git for Windows bash shell supports `ldd`.

If you have visual studio, `dumpbin /dependents` is the way to go apparently.

## Debug versus Release builds.
Builds are often debug by default which means the libraries created aren't portable to other machines. Look for a trailing `D` on the library depenencies.
`VCRUNTIME140D.dll` for example.

