---
title: How can you get your game supported in DumaOS quicker?
weight: 12
---

If you’ve got a game or service you really want supported in DumaOS, you may have already reached out to us via social media or our support forum. Unfortunately, it’s a very time-consuming process to capture data and classify it for DumaOS.

Fortunately, we’ve recently created a new tool that automates a massive part of this process, making it far quicker for us to ultimately get a game or service supported quicker.

If you’re a PC user, you can capture your own data and send it in to us. We can then run this capture through our new tool and if the data is good, we can then get this support in DumaOS!

To do this, you’ll first need to download [Wireshark](https://www.wireshark.org/download.html).

Before we go ahead and capture some game data, we need to make sure we don’t capture any other traffic, otherwise this will make the capture harder to analyse.

To do this, **close everything you can that’s running on your PC, such that the only thing the PC will be doing is running Wireshark and the game/service you’re capturing. Make especially sure that nothing is downloading. If you don’t do this, the capture will be useless.**

In addition to this, **make sure you can quickly launch your game/service of choice**. This may mean having the .exe file on your desktop, or perhaps have the service you launch it through already loaded up (i.e Steam, Battle.net, etc).

Now, complete the below steps in order:

1. Open Wireshark
2. Select either Wi-Fi or Ethernet, whichever connection type you’re using
3. Click ‘Start capturing packets’ 
4. Launch the game/service of choice quickly after
5. Play the game or use the service for a **few minutes**
6. Go back to Wireshark and click ‘Stop capturing packets’
7. Hit ‘File’ then ‘Save as’ and name the file appropriately, then save it.

**To give us the best possible chance at identifying unique game traffic,please repeat the capture a few times. If you can provide between 2-5 captures of the same traffic, that would be ideal.**

Once done, please email your packet captures to [netduma@netduma.com](mailto:netduma@netduma.com) with context as to what game it is. 

If the capture is too large or you'd rather send via a different medium (Google Drive, DropBox, WeTransfer, etc), just send an email with a link to the capture.

We’ll let you know how we get on analysing the capture.

## To Capture Mobile Phone Games

Wireshark is not available on mobile, so you need to connect your mobile phone to a wireless network that you will create on your PC. Wireshark will then capture the data on your phone through your PC

Using a Windows PC to Wireshark a Mobile Device:

1. Click on the start button and then type

```text
cmd
```

- Do not press enter. On the start menu, Command Prompt will appear at the top, right click and click ‘Run as administrator’.

- If prompted by User Account Control, click yes or allow.

- In the Command Prompt window that appears type:

```text
netsh wlan show drivers
```

- Press enter and look for “Hosted network supported”  if it says no then you do not have an up to date network adapter and will need to find a PC that does or use a MAC PC if possible. If is says yes then continue the guide

- Type:

```text
netsh wlan set hostednetwork mode=allow ssid= key=
```

- After ssid= type a unique name that will be your WiFi SSiD through your PC. After key= give a password you want to use for the wifi. It should be 8 characters or more. It should look something like this:

```text
netsh wlan set hostednetwork mode=allow ssid=WiFiTest key=hello123
```

- Press enter.

- After that type:

```text
netsh wlan start hostednetwork
```

1. and press enter. If you have completed it all correctly it will look like the picture below.

2. Now open Windows 10 Control Panel.

3. Choose Network and Sharing Center.

4. On the left pane of Network and Sharing Center window, click the link Change Adapter Settings.

5. This will open up Network Connections.

6. Right click on the ethernet adapter & go to Properties and then the Sharing tab

7. Select the checkbox which asks you to Allow other network users to connect through this computer’s Internet connection then use the drop down menu and select the the “Local Area Connection *10”

8. Now connect to the the Wi-Fi SSID you made earlier on the mobile that you will use to play the game.

Now head back to the top of the article and complete steps 1-7
