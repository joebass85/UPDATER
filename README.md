# UPDATER
DEBIAN-UBUNTU-MINT-RASPBIAN UPDATER. Ubuntu Version 18.04 and later.

This is a bash script that:
```
updates repos 
upgrades the system 
removes any orphaned dependencies 
clears the apt cache 
lists and packages that need upgraded
```
### `WARNING:` The apt autoremove andautoclean commands run automatically by default.

You also have to make the script executable for your system. By default, the permissions are set to read/write only. 
This can be done with `sudo chmod +X up`

Place the script in either the `$HOME/bin` or `/usr/bin` directories.
