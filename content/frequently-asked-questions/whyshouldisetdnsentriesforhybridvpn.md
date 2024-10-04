---
title: DumaOS 3 - Why should I set DNS entries for Hybrid VPN?
---

Whenever we use a VPN server to hide our network traffic, we are hiding our IP and encrypting our data. However, there's still the chance for an external "observer" ( eg. Netflix ) to notice that we are behind a VPN server and it could not allow the access to its services (eg. watching a film from the list of a specific nation). 

When this happens, we are probably experiencing DNS leak. That is to say all of our traffic is correctly tunnelled **except** the DNS queries.

To solve this problem, we have added a new section to Hybrid VPN whereby you can specify the DNS server that you want to use for the tunnelled traffic. By default, the tunnelled traffic uses the same nameservers as the non-tunnelled traffic.

Before we do this, we've got to make sure of a couple of things:

- If you have a DNS server already configured on your Desktop/Laptop, please either delete this or change it to use the DumaOS routers IP for DNS (192.168.77.1 OR 192.168.1.1).
- Disable IPv6 on your WAN interface from the DumaOS GUI. This can be found in Network Settings. The reason we do this is to ensure the R2 is only sending DNS requests over IPv4, this maintains the validity of our tests.

## How do I know if I'm experiencing a DNS Leak?

To see if you're experiencing a DNS Leak, check out [https://www.dnsleaktest.com/](https://www.dnsleaktest.com/).

Using this website, you'll need to run two tests:

- Connect to a VPN server of your choice in your VPN providers desktop client and   use the default configuration for the DNS servers (tunnelled and   not-tunnelled that use the same DNS), then run the DNS leak test. This   test is helpful to verify whether we suffer of a DNS leak.
- Connect to a VPN server and set a specific DNS server for the tunnelled traffic from the Hybrid VPN page, then run the DNS leak test. If in the previous step we have detected a DNS leak, this test will prove that we've now resolved the issue.

## How do I do this?

To test if you've got a DNS leak and how you can resolve it, follow the below steps. 

1. Make sure your PC is connected directly to a DumaOS powered router
2. Choose a nation you want to pretend to live in (let's suppose we've chosen Italy as nation)
3. Access the DumaOS interface and go to Hybrid VPN
4. Set a VPN server from Italy and enable the VPN
5. Go to [https://www.dnsleaktest.com](https://www.dnsleaktest.com) and run the extended test at least twice.
6. If the nation(s) of the DNS servers showed in the result page of the previous step are not in Italy then we are likely dealing with a DNS leak.
7. Go on your favourite search engine and search for: "DNS server Italy" (Or whichever nation the VPN server you've chosen is located in.
8. Get the IP address of a server with a high reliability.
9. Ping the IP address chosen to be sure the server is up.
10. Go to the Hybrid VPN page.
11. Leave the previous configuration, just specify a DNS server in the field provided by the UI.
12. Go to [https://www.dnsleaktest.com](https://www.dnsleaktest.com) and run the extended test at least twice.
13. If the nation of the DNS servers showed in the result page of the previous step is now the country your VPN server is based in, we've now resolved the DNS leak.

If you have any further questions or experienced any difficulty in testing/resolving your DNS leak, please create a new topic in the relevant sub-forum over at forums.netduma.com
