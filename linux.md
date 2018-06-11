## Ubuntu
Finding the version: `lsb_release -a`

## CentOS/RHEL

`yum groupinstall "X Window System" "Desktop" "Desktop Platform" "Fonts"`

### /boot full of too many old kernels
[stack-overflow](https://unix.stackexchange.com/questions/105026/boot-partition-is-almost-full-in-centos#105029)

Edit `/etc/yum.conf` and set `installonly_limit=2` (was 5 on the box I was on).
Install `yum-utils`: `yum install yum-utils`.
Do the oldkernel cleanup: `package-cleanup --oldkernels --count=2`

## RPM
rpm: Find out what files are in my rpm package

Use following syntax to list the files for already INSTALLED package:
`rpm -ql package-name`

Use following syntax to list the files for RPM package:
`rpm -qlp package.rpm`

## apt
List installed packages: `apt list --installed`
List available updates: `apt-get -u upgrade`
List repositories: `apt-cache policy`
Search for a package by name or description: `apt-cache seach keyword`

`aptitude` essentially runs on the same libraries as apt-get and provides some better interfaces.

[`wajig`](https://wiki.debian.org/Wajig) is even better!

## Ubuntu/Debian
`sudo apt-get install xorg openbox`

