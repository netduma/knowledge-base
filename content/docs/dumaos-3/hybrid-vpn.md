---
title: Hybrid VPN on DumaOS 3
---

This guide will help you setup Hybrid VPN on your DumaOS powered router. 

## What is a VPN?

A virtual private network ('VPN') is used to mask your real IP addresses from the Internet. When a VPN connection is made, the VPN server replaces your real IP address with an IP address from the VPN server, keeping your home Internet connection secure.

## What does Hybrid VPN do?

Hybrid VPN is a router VPN Client solution that allows you to apply your VPN provider to any device in your home. You an also choose the games, ports or applications you do or do not want the VPN to be applied to. This means you can protect the devices or services that need it, without forcing the rest of your network to go through a VPN which is usually slower than a normal connection.

## INSTALLING HYBRID VPN

### 1. Update to the latest firmware

*Hybrid VPN is available on the latest firmware for Netduma R1, Netduma R2, Nighthawk XR500, XR450 and XR700.* 

1. Netduma R1: if you are signed up to the Open Beta, you will receive an email from [netduma@netduma.com](netduma@netduma.com) with the latest firmware and instructions. Please ask on our [forums](http://forum.netduma.com) if you have not signed up.
2. Nighthawk Users: Upgrade to the latest XR500 firmware by going to >Settings>Administration>Firmware Update and then clicking Check. The latest firmware may have already been installed, but if not, confirm you would like to proceed with the upgrade

### 2. Hybrid VPN Setup

Once the latest firmware is installed, click Hybrid VPN on the menu on the left. 

1. You will need an active VPN subscription to a provider with OpenVPN or Wireguard(most have this)
2. Toggle Enable so it is disabled (a black line appears, instead of red) 
3. Click **VPN Setup**
4. You can now either use PureVPN or HideMyAss for basic setup (if you have a subscription with them), or you can copy the OpenVPN config file from your VPN provider into the Advanced section
5. Enter your username and password that you have with your VPN provider. Be careful to do this accurately (note: some providers do not require a username or password. Leave this field blank if it's true for you
6. Now click **Enable** . It should now say 'Applying Settings' 
7. Once complete, the Status in the Information should change to 'Connected'. If it does not, please make sure you have entered your details correctly. If you cannot get it to work, please copy your VPN log and let us know on the **[forum](http://forum.netduma.com)** what your issue is, with your log pasted for us to read.
8. If it says connected, VPN is now enabled on your router **BUT** you need to choose the devices / services you want to apply the VPN to. 
9. To apply the VPN to a device, click Add Device on the right hand side and choose the device you want to enable your VPN on. After adding the device, the VPN will be fully enabled on this device.
10. NOTE: If your device is a console, the following options will be greyed out. This is normal, as ALL traffic from the console will go through VPN by default.
11. You can now decide whether you want to include or exclude a service or port range from the VPN. To do this, toggle the Mode between  'Do Not VPN these Services' and 'Only VPN these services'. Then click **Add Service** and choose either the service (mostly games) or the port range (by clicking Advanced) that you want to include or exclude from the VPN

### 3. Common Issues

1. If you have connected your VPN to a gaming device that you use in the Geo-Filter, you may need to restart your router after setting it up 
2. For some providers, details may show as N/A in the VPN Information table. If your VPN has connected you can ignore this.

Setting up a VPN is tricky, so if you get stuck, let let us know on the **[forum](http://forum.netduma.com)** what your issue is, with your log pasted for us to read.

[Click here for more Optimal Settings Guides](/docs/dumaos-3/)
