---
weight: 6
title: Ping Assist
---

This guide will help you setup Ping Assist on your DumaOS powered router. 

## What is Ping Assist?

Ping Assist is an add-on to the Geo-Filter. It allows low ping hosts to connect to you even if they are outside your Geo-Filter limit, helping you to quickly find high quality, low ping games.

## Ping Assist Setup

> Ping Assist is available on the latest firmware for Netduma R1, R2 and the Nighthawk XR500, XR450 and XR700

1. **R1 and R2 Users:** Upgrade to the latest Netduma R1/R2 firmware. 
2. **Nighthawk Users**: Upgrade to the latest firmware by going to >Settings>Administration>Firmware Update and then clicking Check. The latest firmware may have already been installed, but if not, confirm you would like to proceed with the upgrade
3. After the upgrade has complete, click on the Geo-Filter
4. In the Device Panel, make sure you have at least one device in Filtering Mode
5. Expand the Geo-Filter Map options. This is in the top left corner of the Geo-Filter Map panel (three horizontal lines)
6. Now set your Ping Assist value. We recommend between 30ms to 50ms. For example, if you set it to 30ms, anything with a ping less than this value will be allowed through your Geo-Filter no matter where they are located in the world
7. You can then decide if you want to enable **Fast Search.** Enabling Fast Search makes Ping Assist work much faster, which should make finding games quicker. However, this may occasionally mean you allow a connection that is above your Ping Assist limit.
8. Now play your favourite game.

> Note: if you are playing Black Ops 4, we always recommend rebooting your game after making Geo-Filter changes. There's a crucial network check the game does at bootup. So if you're not getting the lobbies you like, reboot the game and it should be better the next time.*

To use Ping Assist as a Ping Filter, follow this guide: [DumaOS Optimal Settings Guide: Using Ping Assist as a Ping Filter : NETDUMA](/docs/dumaos-3/using-ping-assist-as-a-ping-filter/)  

## Troubleshooting

On rare occasions, Ping Assist may block connections below the threshold.
This is usually due to the netcode of the game. If this happens, restart
your game and it should work great the next time

[Click here for more Optimal Settings Guides](/docs/dumaos-3/)
