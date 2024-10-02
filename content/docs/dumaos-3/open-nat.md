---
title: Open NAT
weight: 10
---

Having an Open NAT type is ideal in order to prevent issues with connecting to friends and other players. Your NAT type has no impact on your lag or ping.

## How to test NAT type on PlayStation 4 and 5

Go to Settings > Network > View Connection Status. If you have NAT type 1 or NAT type 2 you have an open NAT.

- NAT type 2 means you’re connected behind another router e.g. Modem > Router > Playstation.

- NAT type 1 is also an open NAT but on a single modem/router setup e.g. Modem/Router combo > Playstation.

## How to test NAT type on Xbox One and Series S/X

Go to Settings > Network > Network Settings > Test NAT Type. The Xbox will display an Open, Moderate or Strict NAT.

If you don't have an Open NAT then follow the instructions below.

## UPnP

By default, UPnP will be enabled. UPnP will automatically forward any ports required for your devices and games when you are using them. You should keep this enabled in most cases.

## Port Forwarding

UPnP will open all the necessary ports automatically for you in most cases.

However in some circumstances you may need to open ports manually. This will help you achieve an Open NAT when gaming or allow access to a specific service. You should research the required ports that need to be opened for the specific game and console you are playing.

The options you will need to fill in are:

- **Rule Name** - We recommend that you name your port forwarding rule something descriptive for future reference (e.g. Xbox CoD).

- **Start Port** - If the ports you need to open are in a range (e.g. 1 - 10) you would type the first port in that range here. If you need for forward only one port, this number should be the same as ‘End Port’.

- **End Port** - If the ports you need to open are in a range you would type the last port in that range here. If you only need to open one port, this number should be the same as ‘Start Port’.

- **Protocol** - You can choose between TCP, UDP or both. You should be able to find out which option you need to select here online.

- **IP Address** - This is the device that you are forwarding ports for. You can check the Device Manager for the IP of the device you want to port forward and input this here.

## DMZ

If you still don’t have an open NAT even though all the required ports have been forwarded, you may need to use DMZ on your ISP Modem or on your DumaOS powered router.

First check if the Modem/Router has Modem or Bridge Mode as this is preferable over DMZ mode.

To put your DumaOS powered router into the DMZ of your ISP Modem, first navigate to System Information. On the Internet Status panel, highlight the number next to ‘WAN IP Address’ and copy it. Next, head to the interface of your ISP Modem and go to the Security / Firewall Settings. You should see a box labelled ‘DMZ IP Address’. Paste the WAN IP Address into this box and make sure DMZ is enabled. You have now successfully put your router into DMZ mode.

If this step does not work you can put your games console into the DMZ of your router. (This option is not available on the Netduma R1.) To do this, first find the IP address of your console. You can check this on the Device Manager R-App, or alternatively you can find this in Network Settings on your console. Next, navigate to Settings > WAN Setup on your DumaOS powered router and type the IP address of your console into the DMZ text box, then click apply at the bottom of the page. You have now successfully put your console into the DMZ of your router.

## Geo-Filter

If you still find you don’t have an open NAT after these steps, it is possible that your NAT type has been misread due to the Geo-Filter incorrectly blocking NAT servers. To check this, set your Geo-Filter device to Spectating Mode instead of Filtering Mode or delete the device from the Geo-Filter Devices panel and check your console Internet status.

If you have an open NAT after disabling the Geo-Filter, make sure you only enable the Geo-Filter once you have reached the multiplayer menu of the game from now on.

## CG-NAT

Carrier Grade NAT, CG-NAT, Large-Scale NAT or LSN is an extension of Network Address Translation (NAT) and can cause NAT issues in many online games, resulting in 'Moderate' or 'Strict' NAT being reported in-game.

Before we check to see if we have CG-NAT, we first need to find our WAN IP. Google What's my IP' and note down the IP.

To detect if you have CG-NAT in Windows, connect your PC/Laptop directly to your modem and complete the following steps:

1. Open a Command Prompt by hitting Win key + R, then type *cmd* and hit Enter.
2. In the Command Prompt that appears, enter the command `tracert <your wan IP>` and hit Enter
3. If there is one line in the response, you do not have CG-NAT.
4. If there are two lines in the response, you are either still connected to your DumaOS router, orhave CG-NAT and should contact your ISP.

## Still not able to achieve an open NAT?

If you have tried every step in this section and cannot get an open NAT, contact Netduma support on forum.netduma.com.
