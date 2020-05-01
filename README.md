# Minecraft app for YunoHost

NOT WORKING ATM!


Minecraft Server

- [Yunohost project](https://yunohost.org)
- [Minecraft website](https://www.minecraft.net/)

![](https://www.cziplee.com/journal/wp-content/uploads/2015/06/Minecraft-Banner.png)


[![Install Minecraft with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=minecraft)

### Installing guide :

 1. App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/minecraft_ynh
         
For admin the server use minecraft console or rcon is open on 25575 with your password.

### Rcon Clients :
- https://github.com/Tee7even/RCONClient (in java)
- https://github.com/Tiiffi/mcrcon/releases (in c)

### Start / Stop / Restart / Status Minecraft :

- ```systemctl start minecraft```
- ```systemctl stop minecraft```
- ```systemctl restart minecraft```
- ```systemctl status minecraft```

### Location :

The folder of yours servers is : ```/home/yunohost.app/```

### Supported Servers :
 
1. Minecraft (Vanilla)
2. Spigot
3. CraftBukkit (by Spigot)
4. BungeeCord
5. Paper
 
### Upgrade this package:

        $ sudo yunohost app upgrade minecraft -u https://github.com/YunoHost-Apps/minecraft_ynh

