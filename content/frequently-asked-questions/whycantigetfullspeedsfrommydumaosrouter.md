---
title: Why can't I get full speeds from my DumaOS router?
---

This article details a few reasons why you might not be seeing your full ISP network speeds through your DumaOS powered router.

## Check wired devices

If
 you're seeing lower speeds on Wi-Fi devices, run a third-party speed 
test (speedtest.net). Make sure this is on a device that's connected to 
the DumaOS router via ethernet (wired). 

If
 you're seeing full speeds on wired devices, the problem may just be 
that you're too far from the router or there are too many obstructions 
between you and the router (Walls, Floors, Ceilings, etc).

If
 your Wi-Fi devices are still seeing very low speeds even right next to 
the router, or wired devices are also seeing low speeds, continue 
through the article.

## Check all devices are connected to the DumaOS router

If
 only some of your devices are connected to DumaOS, but other devices on
 the network are still connected upstream of the DumaOS router, we would
 expect DumaOS to see reduced speeds as the upstream router has to 
evenly divide bandwidth between it's connected devices.

The optimal network configuration for DumaOS would be for all devices on the network to be connected behind the DumaOS router.

![ndXZlps9IKcTdd9rMPiDCoFrRhuWhd3MEA.png](whycantigetfullspeedsfrommydumaosrouter\ndXZlps9IKcTdd9rMPiDCoFrRhuWhd3MEA.png)

## Disable QoS

The
 first thing to check is QoS. If disabling QoS fixes the problem, that 
tells us that QoS is limiting bandwidth to ensure that DumaOS has total 
control over the network and important traffic can be appropriately 
prioritised.

To Disable QoS, first login to your DumaOS interface:

1. For Netgear, go to **192.168.1.1** OR [**routerlogin.net**](https://routerlogin.net) in your browser. For an R1 or an R2, go to **192.168.88.1** (R1) or **192.168.77.1** (R2) in your browser. 
2. Login with your credentials
3. Go to **QoS**
4. Click the three-line menu in top left corner of **Congestion Control (Anti-Bufferbloat for older versions)**
5. Tick **Disable QoS**
6. Run a third-party speed test (speedtest.net) from a device connected via ethernet (Not WiFi)

If
 the speed-test results are back to full ISP speeds, we know the drop in
 speeds is just QoS doing it's job, consider setting Congestion Control 
to **Auto-enable** so speeds are not limited when priority traffic isn't detected.

## Check Connection Benchmark (DumaOS 3.0 only)

To do this, log in to your DumaOS interface. 

1. For Netgear, go to **192.168.1.1** OR [**routerlogin.net**](https://routerlogin.net) in your browser. For an R1 or an R2, go to **192.168.88.1** (R1) or **192.168.77.1** (R2) in your browser. 
2. Login with your credentials
3. Go to **Connection Benchmark.** 
4. Run a test and wait for it to complete.
5. Check the Speed test to see if you're getting the full speeds you'd expect from your ISP.

If
 Connection Benchmark reports considerably lower speeds than what you'd 
expect, run a speed test while connected directly to you ISP 
router/modem and check to see if the results are the same. If they are, 
contact your ISP.

![F8viid4kl7EXFLO1rQbh-rxM_sJrquAcyg.png](whycantigetfullspeedsfrommydumaosrouter\F8viid4kl7EXFLO1rQbh-rxM_sJrquAcyg.png)

If you haven't found the cause/solution to your problem using this article, please create a new topic on our support [forum](https://forum.netduma.com/) and one of our admins will be glad to assist you.
