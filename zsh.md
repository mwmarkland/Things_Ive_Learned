#zsh
## Websites

[Home](http://www.zsh.org/)
[Oh My Zsh!](http://ohmyz.sh/)

## Mac
### MacPorts
To set MacPorts' zsh as default login shell, run:

`sudo chpass -s /opt/local/bin/zsh $USER`

To be able to switch default shells to or from zsh without superuser
privileges, add it to `/etc/shells`:
```
sudo sh -c 'echo /opt/local/bin/zsh >> /etc/shells'
```
