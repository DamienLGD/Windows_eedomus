# Windows_eedomus

Plugin to control your Windows computer with your Eedomus (Wake on lan, shutdown, sleep, restart)  
You have to install [Airytec](http://www.airytec.com/en/switch-off/get.aspx) and configure it (web interface and windows firewall)

## Configure Airytec

Go in your systray

![systray](https://image.noelshack.com/fichiers/2018/02/7/1515934344-capture-d-ecran-2018-01-13-a-16-18-27.png)

Right click on your systray icon, click on options

![systray_clic](https://image.noelshack.com/fichiers/2018/02/7/1515934344-capture-d-ecran-2018-01-13-a-16-21-21.png)

Activate web interface

![options](https://image.noelshack.com/fichiers/2018/02/7/1515934344-capture-d-ecran-2018-01-13-a-16-18-38.png)

## Configure Windows firewall 

by default, the firewall doesn't accept connection on the port you have configure before, you have to create a rule for that.

Go to advanced settings

![firewall](https://image.noelshack.com/fichiers/2018/02/7/1515934347-capture-d-ecran-2018-01-14-a-13-37.png)

Create a new rule

![firewallrule](https://image.noelshack.com/fichiers/2018/02/7/1515934346-capture-d-ecran-2018-01-14-a-13-45-39.png)

Choose port rule

![portforwarding](https://image.noelshack.com/fichiers/2018/02/7/1515934346-capture-d-ecran-2018-01-13-a-16-33-44.png)

Add the port you have chosen before

![port8000](https://image.noelshack.com/fichiers/2018/02/7/1515934858-capture-d-ecran-2018-01-14-a-13-59-25.png)

Authorize

![autoriser](https://image.noelshack.com/fichiers/2018/02/7/1515934346-capture-d-ecran-2018-01-13-a-16-34-08.png)




