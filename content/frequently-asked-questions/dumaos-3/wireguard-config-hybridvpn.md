---
title: DumaOS 3 - How do I use WireGuard config files with Hybrid VPN?
---

This article will explain how to use a WireGuard config file with Hybrid VPN. Please be aware that not all VPN providers offer WireGuard config files, so check with your provider first.

This article assumes that you have already used Hybrid VPN before and are familiar with adding your devices to route them through the VPN.

The first thing to do is go to your VPN provider's website and login to your account. Download the WireGuard configuration file you'd like to use.

Then:

1. Access your DumaOS powered router's interface and navigate to HybridVPN
2. Click 'Setup'
3. Switch to 'Advanced'
4. Click the 'VPN Type' dropdown menu and switch to WireGuard
5. Copy the entire contents of your chosen WireGuard config file and paste it in here.
6. Click Connect.

If you believe your traffic is not being routed through the VPN, use [https://iplocation.com/](https://iplocation.com/) to check where your apparent location is.

If it shows that your IP hasn't changed and that your location remains the same, you may be experiencing a DNS leak. Please check this article to see how you can resolve that.

[Why should I set DNS entries for Hybrid VPN? : NETDUMA](/frequently-asked-questions/hybrid-vpn-dns-entries/)
