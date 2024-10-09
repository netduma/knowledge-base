---
title: Maximum Bandwidth Speeds on DumaOS 3
weight: 2
---

This guide will help you to maximise your bandwidth speeds in DumaOS. We recommend you **only** follow this guide if you believe your speeds are lower than they should be. For example, you usually get 100mbps download speed but you are getting 50mbps.

> Netduma R1 Owners: the maximum speed you can achieve on the Netduma R1 with all features enabled is around 200mbps. If you have higher speeds than this and are seeing around 200mbps on your Speedtest skip to Step 3

## Step 1: Test your speeds

Connect your PC or laptop to your router using an Ethernet cable (unless you are specifically testing wireless speed).

Now test your speed using a reliable website. **[Speedtest.net](http://www.speedtest.net/)** is highly recommended. 

We do not recommend you use your console to run a speedtest - they can often be unreliable.

If you speeds are at the amount you expected, you do not need to change anything. If they are lower than expected, keep reading this guide.

## Step 2: Check if the bottleneck is on your router

It's possible your lower speeds are because your Internet Provider is not servicing you fully. To easily check this, connect your PC or laptop to your **modem** using an Ethernet cable. Repeat the speed test.

If your speeds are low again, then your Internet Provider is the reason for lower speeds. We recommend you contact them directly to resolve this.

If your speeds are higher than your previous test, then continue reading.

## Step 3: Disable DumaOS QoS

The simplest way to check if your DumaOS settings are the reason for your lower speeds is to disable QoS. To do this, go on the DumaOS interface and navigate to **QoS**. On the **Congestion Control** panel, click the 'Burger' icon in the top left corner (three horizontal lines).

This will open up the Options for Congestion Control. Check the 'Disable QoS' option and click Proceed at the warning message. Your QoS has now been disabled.

Now repeat your Speedtest. 

If your speeds **returned to normal** then either your settings are not optimal for speeds, or you are using the Netduma R1 and you have speeds of over 200mbps. If this has happened, then you are either:

- **A Netduma R1 user trying to get speeds of over 200mpbs:** you can either disable QoS to achieve speeds of up to 600mbps-700mbps, or enable QoS to have lower speeds.
- **A Netduma R1 user aiming to get a speed lower than 200mbps:** keep reading this guide
- **A Nighthawk Pro Gaming User**: keep reading this guide

If your speeds **were still low** after disabling QoS but they are normal through your modem, then you have an obscure issue. We recommend you try the following:

- Set your modem to 'Modem mode' or 'Bridge Mode' (if it has the option). You will need to consult your Modem's user manual if you are not sure how to do this
- Disable IPv6 in your Network Settings on your DumaOS router
- If you use PPPoE to connect to the Internet, make sure this is entered into your modem, instead of your router
- Post on our support forum if the steps above did not work ([www.forum.netduma.com](http://www.forum.netduma.com))

## Step 4: Re-enable QoS and improve your DumaOS settings

You need to re-enable QoS. So navigate to **QoS**. On the ****Congestion Control**** panel, click the 'Burger' icon in the top left corner (three horizontal lines) and now uncheck the 'Disable QoS' option. Now do the following:

1. On Congestion Control, set the mode to 'Never'
2. On Bandwidth Allocation (also on the QoS page), click **Reset Distribution** on both the Download and Upload options
3. On Bandwidth Allocation, open the Options menu using the Burger icon, and make sure '**Share Excess'** is checked. You will need to do this on both the Download and Upload options
4. In Traffic Prioritization, remove any manual rules you added.

Now repeat the Speedtest. 

If your speeds **returned to normal** then you have achieved the objective of getting full speeds. However, your QoS is no longer setup optimally. We recommend you now configure this to get the best congestion elimination setup for your network. See this [Optimal QoS Setup](/docs/dumaos-3/qos/) guide to learn how

If your speeds **were still low** but they are normal through your modem, then you have an obscure issue. We recommend you try the following:

- Set your modem to 'Modem mode' or 'Bridge Mode' (if it has the option). You will need to consult your Modem's user manual if you are not sure how to do this
- Disable IPv6 in your Network Settings on your DumaOS router
- If you use PPPoE to connect to the Internet, make sure this is entered into your modem, instead of your router
- Post on our support forum if the steps above did not work ([www.forum.netduma.com](http://www.forum.netduma.com))
