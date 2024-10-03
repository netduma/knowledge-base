---
title: How to test your Internet Ping
---

In this guide we'll be utilising a program called 
PingPlotter to test your connection quality. This can be used to find 
out if you have an issue with your Internet Provider, and to test that 
QoS is working effectively.

1. Download PingPlotter [here.](https://www.pingplotter.com/download)
2. Type
   an IP or website that is close to your location into the target address
   bar. For this test we're using bbc.co.uk as we're located in the UK. 
   The most popular option is usually Google (e.g. Google.com, 
   Google.co.uk, Google.fr etc.)
3. Keep the interval at 2.5 seconds then press enter on your keyboard or click the green Play button. 

![DyPmu0MsGzupgertiIuIj6M24mYmHuQFMg.jpg](howtotestyourinternetping\DyPmu0MsGzupgertiIuIj6M24mYmHuQFMg.jpg)

Fig1. - Ready to ping BBC.

We
 want to focus on the bottom graph rather than the top half of the 
program. The results you get here will be your base ping. That is the 
ping you have before you do anything on the internet. In Fig2 below, the
 base ping is around 16-17ms. If when doing this test it is not as 
stable as Fig2 then this could indicate an issue with your ISP & we 
would recommend contacting them with the proof you've gathered from 
these tests. Equally, if thick red vertical lines are appearing this 
represents packet loss on your line. So again, contact your Internet 
Provider with this data if this is happening.

![O2QW8bRfbJ2wI0dDzN7miskLgXUEzIrYyg.jpg](howtotestyourinternetping\O2QW8bRfbJ2wI0dDzN7miskLgXUEzIrYyg.jpg)

Fig2. - Idle Connection showing Base Ping

The
 next step is to repeat the test but this time by saturating the 
connection as much as possible by doing multiple downloads, watching HD 
videos etc.

You may then get something that looks like 
this or even worse. This is your connection when it is congested, as you
 can see it is very unstable:

![x209u6b_njc-Qx2E1F45ncWVAAijc3L2Tw.jpg](howtotestyourinternetping\x209u6b_njc-Qx2E1F45ncWVAAijc3L2Tw.jpg)

Fig3. - Saturated connection.

You can see the ping in real time, the ping numbers are listed to the left of the graph.

Here is another example, this time with severe packet loss as well:

![f3jWcLfwE1r.png](howtotestyourinternetping\f3jWcLfwE1r.png)

Fig4 shows the same saturated connection as Fig3 but it us using Anti-Bufferbloat set to 'Always' and at 70% each way:

![z41R-9zT4RZf10PZQ0FazS5xDCpE27RlVg.jpg](howtotestyourinternetping\z41R-9zT4RZf10PZQ0FazS5xDCpE27RlVg.jpg)

Fig4. - Saturated Connection with Anti-Bufferbloat Active.

You can see it is very stable and very close to the base line ping of Fig2 even when saturating the network. 

---

If
 you have performed this test and you are still experiencing ping spikes
 during congestion (but pre-congestion everything is fine), then your 
settings may be incorrect. PLease contact our support team at 
forum.netduma.com for assistance.

If after correct 
settings are applied, then the cause is almost certainly not your 
router, but is instead probably one of the following: :

- The ethernet cable connecting your modem to the router
- The Modem
- The line from your ISP (Internet Service Provider)

The
 ethernet cable being used to connect your modem to the router may be 
old and therefore inconsistent with the data it's transferring. It also 
may not be the right type depending on your speeds. In order to make 
sure this is not the case we recommend using at least Cat5e ethernet 
cables. Replace the one you have currently with a different one - 
preferably new. Then you should try the PingPlotter test again to see if
 the spikes have subsided similar to Fig2/4.

If the 
cable is not the issue then it could be the modem. There are modems that
 include an Intel PUMA 6 based CPU, these are known to cause lag spikes 
even when the connection is idle. Make sure that your modem does not 
include this CPU by looking up the technical specifications of your 
modem online. If it doesn't include this CPU that is great, if it is an 
old modem consider replacing it for the best performance.

If
 you are still getting the issue then you will need to connect your ISP 
and provide them with evidence in the form of screenshots of the 
PingPlotter tests that are done when directly connected to the modem - 
they will blame the router otherwise. Hopefully they will be able to 
assist you from there.
