# Search for packages
`apt-cache search <re>`

# Installed packages
`apt list --installed`

`aptitude search '~i!~M'`
This will show expressly installed packages, not those installed as dependencies.

## Other ways:

`dpkg --get-selections | grep -v deinstall`
