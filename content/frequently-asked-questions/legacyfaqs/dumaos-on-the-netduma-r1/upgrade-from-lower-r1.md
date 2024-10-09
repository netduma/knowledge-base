---
title: "How to upgrade your R1 from a version lower than 1.03.6"
---

If you attempt to upgrade your Netduma R1 from a version lower than 1.03.6, for example 1.03.3, there is a high probability you will completely break your router. To solve this problem, we need to run a simple fix on your router. (To check your firmware version, follow [**this guide**](/frequently-asked-questions/legacyfaqs/dumaos-on-the-netduma-r1/check-firmware-version-r1/))

To enable us to do fix your router, we need to be able to remotely access it. Please follow these instructions to allow us to do this:

1. Access your Netduma R1 interface
2. Go to >Settings >Miscellaneous
3. Tick ‘Allow remote access to Netduma tech support’
4. Go to Settings >UPnP and enable the feature if it's not already enabled
5. Go to Settings > Port Forwarding and remove any rules
6. Now verify that everything is working by going to [What is my IP?](https://www.whatismyip.com/port-scanner/)
7. In the port entry field, type in 7777 and click Scan 
8. If the result is 'Open' then you have successfully allowed us to access your router to run the fix. Please notify us of this on the forum here: [Upgrading your Netduma R1 to DumaOS from a version lower than 1.03.6 - Netduma R1 Support](/frequently-asked-questions/legacyfaqs/dumaos-on-the-netduma-r1/upgrade-from-lower-r1/)
9. If the result is closed then you have another router on your network which will block our access attempt. Please put your other router into 'modem mode' or 'bridge mode' (if possible). If you cannot see this option, then you will need to put the Netduma R1 into a DMZ on your other router. Please refer to the user manual for your other router for instructions on how to do this. Repeat the port scan step in steps 6 and 7 above to confirm we can now access your router.