## View apt history
```bash
grep " install " /var/log/apt/history.log
```

## Show disk size usage
```bash
du -hs /path/to/directory
du -hs /path/to/directory/*
```
https://askubuntu.com/questions/1224/how-do-i-determine-the-total-size-of-a-directory-folder-from-the-command-line

## Show running processes
```bash
ps aux | [more|less]
```
### Look up process by name
```bash
pgrep -u <username> <process_name|pattern>
```

## Configure Gnome
### Customize workspaces
```bash
gsettings set org.gnome.shell.window-switcher current-workspace-only true
gsettings set org.gnome.shell.app-switcher current-workspace-only true
gsettings set org.gnome.shell.extensions.dash-to-dock isolate-workspaces true
```
