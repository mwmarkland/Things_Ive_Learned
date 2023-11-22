# Windows Subsystem for Linux

## Cool things

- [Sharing directories/file systems between WSL instances](https://superuser.com/questions/1659218/is-there-a-way-to-access-files-from-one-wsl-2-distro-image-in-another-one/1659355#1659355)

## Notes on disk usage
if you're using Hyper-V & WSL2 your distro state virtual disk image might be wasting 100GB+ of storage space. by default the VHDX grows dynamically but does not shrink if stuff is deleted.

to fix, launch powershell as admin, then:

```
wsl --shutdown
cd %LOCALAPPDATA%\Packages\CanonicalGroupLimited.UbuntuOnWindows_....\LocalState
optimize-vhd -Path .\ext4.vhdx -Mode full
```
afterward, you can also update wsl to the pre-release version and enable sparse disks:
```
wsl --manage Ubuntu --set-sparse true
```
