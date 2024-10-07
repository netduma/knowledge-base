---
title: Prioritising Traffic on DumaOS 3
weight: 4
---

Using QoS, you can prioritize time-sensitive traffic (such as gaming) on your network. When configured properly, your gaming will remain smooth even while other people in your house are streaming or downloading.

The Congestion Control (Anti-Bufferbloat) slider will essentially reduce your bandwidth, which on its own would be useless, but when combined with Traffic Prioritization, it becomes a powerful tool.

It may seem counter-intuitive to reduce your bandwidth when you're attempting to reduce your ping, but it makes sense when you understand why we're doing it. Somewhere along the line between your router and the server you're trying to connect to, there will be a bottleneck where traffic is having to queue. This means that traffic is being delayed because of a factor outside of your home, and therefore outside of your control.

The idea behind Congestion Control (Anti-Bufferbloat) is that, by reducing your bandwidth slightly, the bottleneck moves from outside of your home to inside your home. Now that the bottleneck is on your router, you can manipulate the queue of traffic, moving the most important (time-sensitive) traffic to the front.

So, in order to have the best QoS setup, you need to use Congestion Control (Anti-Bufferbloat) and Traffic Prioritization together. The first step is to add your gaming device to Traffic Prioritization using the correct profile. If you're using a games console, use the Games Console profile. If it's a PC, choose the specific game you're playing. If your game is not present, contact Netduma Support for advice.

You have to be careful to prioritize as little as possible, because the more you prioritize, the less effective it will be.

In the Congestion Control (Anti-Bufferbloat) side menu, you need to enter your maximum bandwidth values. These may have been automatically detected when you first set up your router. If not, you should set them to the highest bandwidth that you've ever been able to get on your connection. This should be the speed you get when your network is totally idle, and at a non-peak time of day.

Now for the Congestion Control (Anti-Bufferbloat) sliders. We recommend starting them at 70% and using Auto-Enable. Using the Auto-Enable function means that your bandwidth will not be reduced until a video game is being played. With this setup, try playing a game and see if your ping is good. If you find that your ping begins to rise, try reducing the sliders by 5-10%. Eventually you'll find the 'sweet spot', which is the highest point on the sliders that your ping is consistently stable, even when other devices on the network are flooding the connection.
