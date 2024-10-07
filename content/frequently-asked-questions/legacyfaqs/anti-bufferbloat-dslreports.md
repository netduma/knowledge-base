---
title: Legacy Guide - I can't get an A+ on DSLReports. Is Anti-Bufferbloat not working?
---

> This is a legacy guide. It is now possible to test your ping-under-load using the Ping Optimiser feature in DumaOS. This guide has been preserved for those that might find it useful.

**If DSLReports is giving you an A instead of A+, does that mean that Anti-Bufferbloat isn't working fully?** 

DSLReports is a website which can be used to run a speedtest on your connection. As part of the results, it measures how your connection handles 'Bufferbloat' (congestion) by creating congestion and then testing your ping.

DumaOS contains the world's best QoS solution, which prevents Bufferbloat from building. In theory, this should mean that DSLReports should return the best possible Bufferbloat result, 'A+'. However, in practice it returns an 'A' rating, one below a perfect A+.

The reason for this is because DSLReports incorrectly misreads the DumaOS Deep Packet Inspection feature, which analyses the first eight packets of a new connection. DPI is very useful because it allows games to be prioritized automatically in Traffic Prioritization. You can also see Deep Packet Inspection in action on the Network Monitor; if you click on a bar on the Network Snapshot panel  you will be able to break down the applications that are currently using a device's bandwidth in extreme detail.

DSLReports mistakes this inspection for a small ping spike. **No ping spikes actually occur, DPI does not interfere or slow down your connection in any way**.**** DumaOS can handle QoS at gigabit speeds which is far beyond the reach of most routers, and is heralded as one of the most effective Anti-Bufferbloat tools in networking.

If you wish to verify this yourself, then you can easily do so by using a program called PingPlotter. All you need to do is:

1. Open Pingplotter and ping a common server e.g. google.com
2. Saturate your connection as much as possible (e.g. download files, stream HD    videos etc), then do a PingPlotter test and see how much your ping rises.
3. Enable QoS by switching Anti-Bufferbloat to 'Always' and drag the sliders down to 70% each. You will then see your ping return to pre-congestion levels and stabilise your connection.

For full test steps, [see this link](http://support.netduma.com/support/solutions/articles/16000074717-diagnose-modem-internet-service-provider-issues/preview)
