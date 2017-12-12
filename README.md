# QServWindows (Stable)

Welcome to the QServWindows project page! Thanks to BudSpencer for porting the mod from Unix to Windows. 
The port had previously uncovered some GeoIP issues but they have all been fixed. GeoIP has been working
perfectly now. Also, the pban and ban systems have been fixed. Please report bugs on the issues page, thanks.

# How to run a server

1) [Download QServ](https://github.com/deathstar/QServWindows/archive/master.zip)
2) Unzip QServWindows-master.zip 
3) Open config/server-init.cfg with a text editor and configure the server
4) Forward ports 28785 and 28786 using UDP to the internal IP of the computer which QServ is hosted on [(more)](http://quadropolis.us/node/2525)
5) start QServWindows.exe 

You do not have to restart to change the configuration. Simply add the new modification in config/modifier.cfg, and then join the server, claim admin, and type #reloadconfig. All of the changes will be applied without having to restart the server.

# Known issues

- QServ system tray icon not visible
- #stats command accuracy division by 0 with one client invalid (not tested)



