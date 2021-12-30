# DDoS Protection for your Minecraft Server / Network!

This guide is for those who need to protect their home/VPS/dedicated/shared server from DDoS attacks. If I'm wrong about something or something is missing, contact me on discord - qbasty#0001.

# Do I need DDoS Protection?
Not everyone needs DDoS Protection, a server for 2 friends doesn't, but even bigger servers with 50 players might need it. You probably shouldn't worry until... yea, it happens. 

## How to check if my host has DDoS protection?
Sadly, almost every dedicated/VPS or even shared server hosting says that they have great DDoS Protection. Let's check that! If you don't know the IP of your server because you just have a subdomain, make sure your server is on and use https://mcsrvstat.us to get the IP of your server (Show Debug Info). Once you have the IP, head to https://ipinfo.io and enter the IP there. Look at ORG and Name, if you see something that wasn't mentioned in this guide, your host probably has none or barely any custom DDoS protection (This is the case for MANY hosting companies, message them for more info).

## DDoS Protection out of the box

Very Good/Amazing:
- Tempest - You will be able to handle a few thousand players (traffic) and DDoS attacks at the same time
- OVH - Game Range has the best protection for Minecraft. Internal attacks are an issue for some people. (Not as good as Tempest)

Good/Decent:
- Hetzner - it's enough for some people, for some it isn't. You can kindly ask for an IP change of your dedicated server if you want to get some DDoS Protection
- ReliableSite

Bad/Horrible:
- OVH VPS - They can be taken down easily
- PhoenixNAP

More soon

# On budget
Below you can find a list of DDoS Protection services across all continents, some of these can be used by large networks.

Locations you will find: to do

## Europe
Europe has options starting from 0$ a month to hundreds, it all depends on your needs. Click on the name to learn more about each option.

- [TCPShield](https://github.com/qbasty/ddos-prot-mc-servers#tcpshield)
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [CosmicGuard](https://github.com/qbasty/ddos-prot-mc-servers#cosmicguard)
- [BuyVM](https://github.com/qbasty/ddos-prot-mc-servers#buyvm) (VPS Hosting)

## North America
North America has very similar options to Europe, but more locations are available.

- [TCPShield](https://github.com/qbasty/ddos-prot-mc-servers#tcpshield)
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [CosmicGuard](https://github.com/qbasty/ddos-prot-mc-servers#cosmicguard)
- [BuyVM](https://github.com/qbasty/ddos-prot-mc-servers#buyvm) (VPS Hosting)

## Australia / New Zealand
Only 2 options here, there aren't many great dedicated servers for Minecraft in this region.
- [Ausguard](https://github.com/qbasty/ddos-prot-mc-servers#ausguard)
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)

## Singapore / Asia
- If you have chosen between OVH and PhoenixNAP, choose OVH for better DDoS Protection out of the box
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)

## Africa and South America
- You could get a server in Miami, so players from South America have a decent ping, in that case, you can choose from MCShield, BuyVM, Bloom Hosting.
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)

# TCPShield

Extremely popular Minecraft Server DDoS Protection operational since 2015. Used by many large networks.

Website: https://tcpshield.com
Setup Guide: https://docs.tcpshield.com/panel/setup-process

Locations: France (Gravelines), Germany (Frankfurt), Canada (Beauharnois, Quebec)

### Pros
- Free Plan
- Great 16Tbps Layer 4 & Unlimited Layer 7 Protection
- Running since 2015, has a great reputation
- [Cloudflare Spectrum](https://docs.tcpshield.com/cloudflare-network) to reduce latency
- TCPShield Plugin to hide your server IP
- Great uptime
- Simple and fast setup 

### Cons
- Expensive compared to the other alternatives
- Geyser Support starts at 100$ / month
- No Asia/Africa/South America/Australia locations

### For dedicated servers / vps

If you don't have a host for your server yet, but you are interested in getting TCPShield, here is a list of hosts that will work great with TCPShield:
- OVH (Canada)
- ReliableSite (New York)
- PhoenixNAP (Ashburn)
- SoYouStart (Canada)
- Ready2Frag (Chicago) - Not sure about this one yet
- HostVenom (Chicago) - Not sure about this one yet
- Hetzner (Germany)
- PhoenixNAP (Amsterdam)
- OVH (Germany)
- OVH (France)
- SoYouStart (France)
- SoYouStart (Germany)

### For home hosting

If you just want to run a server for a few friends but you still want some DDoS protection, TCPShield is the best option at the moment if you are in Europe/North America of course.

Quickly comparing all the plans. 
| Plan  | Price  | Bandwidth Limit  | Bedrock Support (UDP)  | Networks (How many different servers)  | Domains  | Sub accounts  |
| --- | --- | --- | --- | --- | --- | --- |
| Free  | 0$ / month  | 1TB  | :x:  | 1  | 3  | :x:  |
| Pro  | 25$ / month  | 2TB  | :x:  | 1  | 10  | :x:  |
| Premium  | 100$ / month  | Unlimited  | :white_check_mark:  | 3  | 25  | :white_check_mark:  |
| Enterprise  | 250$ / month  | Unlimited  | :white_check_mark:  | 10  | Unlimited  | :white_check_mark:  |

Note: There are MANY more features for each plan, learn more about them [here](https://tcpshield.com/plans).

# MCShield

Website: https://mcshield.com

The brand new option made by MCPROHOSTING. It came out on the 20th of October. The protection is Cloudflare Spectrum (42 Tbps) and there is only one plan, which costs 10 USD a month. You get unlimited bandwidth, access to 22 [locations](https://mcprohosting.com/billing/knowledgebase/106/Server-Locations-MCProHosting-Offers.html) on 6 continents and there is also a 7-day money-back guarantee. 

### Pros
- Cheap
- Unlimited bandwidth
- Cloudflare Spectrum 42Tbps Protection
- 22 locations on 6 continents

### Cons
- Brand new and run by a hosting company that runs your server on a Dual Xeon E5-2600 CPU. I'll be doing some tests soon so maybe MCShield is actually much better than MCProHosting, who knows.
- No Geyser Support
- Lack of information on the website

### For home hosting
You have more locations than TCPShield. UK Location is available.

### For dedicated servers
In my opinion, MCShield isn't really a DDoS Protection for professionals at the moment but you could give it a try, the number of locations can let you choose a server anywhere in the world.

# CosmicGuad
Used by a few big networks too, but to save money, for example, 2b2t disables A LOT of packets in their queue server. 

Website: https://cosmicguard.com
More info: https://www.peeringdb.com/net/21075

Locations: Dallas, LA, Reston, Secaucus, Amsterdam, London, and Maidenhead.

### For home hosting
UK Location is available.

### For dedicated servers
You could protect your PebbleHost dedicated server with CosmicGuard I guess?

### Pros
- Custom-built 1Tbps DDoS Protection (EDIT: You get null routed if the attack is 500Gb or more)
- You are charged for what you actually use
- Geyser Support

### Cons
- Pretty expensive

# BuyVM
BuyVM is a VPS provider but doesn't have a fancy panel like TCPShield. You will have to configure an Nginx proxy to protect your server. But before that, some info here:

### Which SLICE?
I wouldn't recommend the 512 SLICE at all as it's just not enough power. 1024 is the bare minimum, but I recommend at least the 2048 SLICE. 4096 will run pretty well.
512, 1024, and 2048 SLICE get a shared 100Mbit/s, but you can burst up to 1Gbit/s if there isn't much traffic on the whole network at the moment. 4096 SLICE gets a dedicated 100Mbit/s, 8192 gets a dedicated 200Mbit/s, etc. 

### How to order
Simply go [here](https://buyvm.net/kvm-dedicated-server-slices/), choose the slice you want, the location, and then in the order form order x1 DDOS PROTECTED IP. If you get an out-of-stock error, join [here](https://discord.gg/3hs44DjPc8) to wait for the stock. 

More soon!

### For home hosting
The cheapest option (6.5 USD) and the only one where it's a VPS, not a panel if that's what you want.

### For dedicated servers
These should work great:
- OVH (Canada)
- ReliableSite (New York)
- ReliableSite (Miami)
- PhoenixNAP (Ashburn)
- SoYouStart (Canada)
- Ready2Frag (Chicago)
- HostVenom (Chicago)
- Hetzner (Germany)
- PhoenixNAP (Amsterdam)
- OVH (Germany)
- OVH (France)
- OVH (Poland) ~30ms
- SoYouStart (France)
- SoYouStart (Germany)

### Pros
- You can run whatever you want on this along with the Nginx/infrared proxy
- You can run multiple servers, with different IPs
- Easily upgradable

### Cons
- No downgrades
- It is hard to set up for non-Linux users
- If something breaks, you must fix it yourself

# Ausguard

EDIT: It seems down at the moment, you can still join the discord: https://discord.gg/wZtJSCmqyy.
Locations you get: Sydney, Melbourne, Perth, Brisbane, Adelaide, Auckland (New Zealand)

It costs 10$ / month and you get unlimited bandwidth!

### For dedicated servers
You could protect your OVH dedicated server

### For home hosting
It's cheap and has more locations in Australia than MCShield

### Pros
- Many locations in this region
- Great load balancing (I talked to the dev)
- Unlimited bandwidth
- The only alternative to MCShield which seems to be aimed at more professional servers

### Cons
- It's down at the moment!

# For large networks

- TCPShield - the 100 or 250 USD plan a month is what you would be looking at. Extremely fast support, load balancing, great panel, and Cloudflare Spectrum for smaller ping if needed. Used by MrBeast Event Server, LTT, PebbleHost, MineSuperior, Vortex, Lunar, and many others - https://tcpshield.com/#clients
- CosmicGuard - you might have to do some tricks to save bandwidth and lower the costs. Used by 2b2t, Tebex, Chess.com, Wynncraft, Cosmic.
- Tempest - Dedicated Servers with 10Gbit port and 6.5Tbps Path.net DDoS Protection.
- Cloudflare - The most expensive but 42Tbit DDoS Protection isn't cheap. Cloudflare has many locations too. Used by Hypixel.

# Lowering the bandwidth usage
- Lower view distance
- set compression-level to 256 in your velocity config, this will increase CPU usage at the cost of lower bandwidth usage (if you run without a proxy, set it in server.properties, but if you do run with a proxy, set it to -1 on all of your paper servers)
- block some packets like 2b2t does in their queue (more on this soon)

# Contact
Discord: qbasty#0001
