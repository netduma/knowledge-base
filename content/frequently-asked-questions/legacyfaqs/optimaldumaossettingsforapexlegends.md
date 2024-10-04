---
title: Legacy Guide - Optimal DumaOS settings for Apex Legends
---

> This guide is for DumaOS 3. If you are on DumaOS 4, the instructions may not be applicable.

You can use the Geo-Filter to guarantee you only play on your favourite server location in Apex Legends. This guide will help you to setup your Geo-Filter optimally for Apex Legends:

**<u><span>Background</span></u>**

Apex Legends uses Dedicated Servers to host your game. They are located all around the world. The game may give you a nearby server with a low ping, but it can not guarantee this. For example, when many players are online, it will prioritize giving you an available server quickly rather than the server with the best possible ping. This is true even when you try to use the Data Center selector in the bootup screen. 

But with the DumaOS Geo-Filter, you can guarantee that you play on the same server every time, ensuring you always play with a consistent, low ping. (See a demonstration video here: 

**<u><span>Server Locations</span></u>**

Here are the server locations in Apex Legends, including the region that Respawn consider them to be in:

![tSWWx5x6RuNUUn4HqY6v9Y99JJx2TRQ7xg.jpg](optimaldumaossettingsforapexlegends\tSWWx5x6RuNUUn4HqY6v9Y99JJx2TRQ7xg.jpg)

**<u>Setup Guide</u>**

1. Access DumaOS from a computer. On a Nighthawk Pro Gaming router, go to [routerlogin.net](http://routerlogin.net). On a Netduma R1, go to [192.168.88.1](http://192.168.88.1) 
2. Default login details are **admin** and **password** *(in English)*
3. Go to the Geo-Filter
4. In the Geo-Filter Map options, click **Flush Cloud**-wait about 45 seconds for this to complete. If you own a Netduma R1, a message will probably appear that says "The operation is taking longer than expected. Please briefly wait before using this R-App." Don't worry if you see this, just click OK and wait a further 15 seconds. The new Cloud will have installed in the background
   
   ![oo_bi6cpNY6N0tq5PfqwRQnYVyPZlweqZg.png](optimaldumaossettingsforapexlegends\oo_bi6cpNY6N0tq5PfqwRQnYVyPZlweqZg.png)
5. Make sure Strict Mode and Auto Ping Host are enabled. If you do not usually use [Ping Assist](http://support.netduma.com/support/solutions/articles/16000087579), leave it disabled (at 0ms). If you like to use Ping Assist, we recommend you set it to 30ms.
6. If playing on a **C****onsole**, add your PS4 or Xbox One to the Geo-Filter Device panel. Then proceed to step 8 of this guide
7. If playing on a **PC**, follow [this guide](http://support.netduma.com/support/solutions/articles/16000092094-how-to-add-your-gaming-pc-to-the-dumaos-geo-filter) to add your PC
8. Set the Geo-Filter Mode to **Filtering Mode** (it should have defaulted to this)
9.  Set your home location and distance around the region you want to play in (refer to the Map above for the different regions)
10. Now search for a game. The Geo-Filter will block any servers outside of your range, ensuring you always get a low ping, nearby server every time you play. 

We hope you enjoy using the Geo-Filter to Dominate Lag in Apex Legends. If you would want to optimise your connection even further, see all our [Optimal Settings Guides for DumaOS](http://support.netduma.com/support/solutions/folders/16000090646)

**<u><span>Troubleshooting</span></u>**

**Q: I cannot search for a game after blocking servers, what should I do?**

A: It is common when using the Geo-Filter to see this screen:

![ZYxKtAMUJNUSJ1Sb2GHzdi5x1EUpyhp2xw.jpg](optimaldumaossettingsforapexlegends\ZYxKtAMUJNUSJ1Sb2GHzdi5x1EUpyhp2xw.jpg)

This happens when you block distant servers on multiple occasions in a single gaming session (usually four or more times). When this happens, Respawn assumes you have a connection problem so it forces you to restart your game. So you need to restart your game and you can then continue as normal.

To reduce the frequency of this screen appearing, we recommend you don't make your Geo-Filter radius too small - try to at least cover the server region you want to play in (see the Server Map above to see your region).

**Q: I cannot join the pre-game Home lobby  / I see the message "Attempting Connection"**

A: If you get this please reattempt to join the lobby. This can sometimes happen because the Geo-Filter blocks Authentication servers we have not yet whitelisted. We will be improving our Whitelist to include more authentication servers to minimise this issue, but for now please just reattempt to join the lobby. If this does not work, please restart the game

![aCbdm-S2PEeeGrcNUpDcroFtAsNYs2e5Mw.png](optimaldumaossettingsforapexlegends\aCbdm-S2PEeeGrcNUpDcroFtAsNYs2e5Mw.png)

**Q: What are the rectangles with white rings around them?**

 These are "Authentication" servers used by the game to allow you to connect to the home lobby. They are not used to host your actual game. You can ignore these when they appear in the Map

![YNgoTG7dTz3XjQZNJNpK-DxMA9UUKyjmtw.png](optimaldumaossettingsforapexlegends\YNgoTG7dTz3XjQZNJNpK-DxMA9UUKyjmtw.png)

**Q: I think a server is in the wrong location on the Map**

This can sometimes happen because accurately placing every connection in the world is nigh-on impossible. But we can correct any mislocations with your help. Please let us know on our forum in this thread (read the first post so you know what to provide): [Geo-Filter Server Location Improvements - Feature Ideas &amp; Improvements for DumaOS - Netduma Forum](https://forum.netduma.com/topic/28284-reporting-mislocated-geo-filter-servers/) 

 * If you are playing on PC double check your PC can handle the video settings you are using. Windows backgrounds such as moving wallpapers used with Wallpaper Engine may cause additional lag.
