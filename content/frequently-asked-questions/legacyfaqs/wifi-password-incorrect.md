---
title: I've received my new Netduma R2 but the WiFi password doesn't work
---

You've received your new Netduma R2 router but when you try to connect a device to the WiFi it says the password is incorrect, fear not, we've got you covered. *Please note we are looking into the issue so that this can be fixed.*

**<u>Ethernet Cable Method (Easiest)</u>**

If you have a PC/laptop that has an ethernet port then you can simply connect an ethernet cable from your PC/laptop to one of the LAN ports on the R2.  

**<u>Password Conversion Method (Easy)</u>**

If you do not have an ethernet cable then we can convert your incorrect password into the correct password.

On the underside of your router take the password that you have, for example:

**012345678910111**  

then split the password up into sets of three, for example:  
**012 345 678 910 111**  

Then increment every third digit by 1, except for the one in the fourth set, so it becomes:  
**013 346 679 910 112**  

Then take the spaces out and you are left with the correct password for WiFi: 

**013346679910112**   

**<u><span>Connecting the R2 Upstream of your ISP router (Medium)</span></u>**

If you do not have an ethernet cable and the password conversion isn't working then we can cleverly wire the R2 in a certain way so that you can access the interface through your ISP router WiFi. You may not have internet while you complete this method. *Please note if you have a pure modem (no WiFi) or a router without a WAN port then you cannot use this method.*

1. Disconnect the R2 from your ISP router
2. Connect the R2 LAN port to your ISP router WAN/internet port
3. Connect via WiFi to the ISP router
4. Complete the setup wizard
5. Reboot the R2 and wait 2 minutes
6. Re-connect the R2 and ISP router according to the setup guide  

**<u>Connected?</u>**

In case you need a reminder, once you have successfully connected to the router either via WiFi or ethernet then you can access the R2 interface by entering 192.168.77.1 in the URL bar of your web browser. Once there you may be asked for login details which are by default:  

Username: admin  
Password: password  

Once you've logged in you will see the Setup Wizard, complete this and you should have access to the full interface where you can truly start to enjoy your new router!

If you have any issues with the subject matter explained here or with anything else we're always happy to help on [forum.netduma.com](https://forum.netduma.com)
