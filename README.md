# DDoS Protection for your Minecraft Server / Network!

This guide is for those who need to protect their home/VPS/dedicated/shared server from DDoS attacks. If I'm wrong about something or something is missing, contact me on discord - qbasty#0001.

# Do I need DDoS Protection?
Not everyone needs DDoS Protection, a server for 2 friends doesn't, but even bigger servers with 50 players might need it. You probably shouldn't worry until you actually start having issues with DDoSes. 

## Dedicated Server Providers
Dedicated Server Providers with DDoS Protection out of the box so you don't have to worry about attacks later on.

Good/Great:
- Tempest - Path.net DDoS Protection together with 10Gbit traffic and port. The biggest issues with path.net are stability and latency. Current capacity is 10Tbit.
- OVH - OVH offers great protection at a great price. OVH is known for having some issues with billing, support and internal attacks. You get same protection with SoYouStart and Kimsufi. TCPShield and Infinity Filter run on OVH.
- CosmicGuard - Yes, now they have their own dedicated servers. Open a ticket / live chat if interested.

Ok/Bad:
- Hetzner - It's good enough for some people but really bad in some cases. You can request an IP reset for free (only one time).
- ReliableSite
- PhoenixNAP

# Best Protection
This is my personal opinion and feedback from others, don't use this as your main reason to buy / not buy.

1. CosmicGuard - It's been great for me so far but when there was some attack that worked, they fixed it really fast.
2. Path.net - When I was using BuyVM, we had to block a lot of proxies ourself and that wasn't an issue with CosmicGuard
3. Cloudflare
4. OVH (without any custom filters) - All the options I mentioned like TCPShield and Infinity Filter have their own custom filters

# Protection with panel and support
These are some options that come with a panel and support, no hard and time consuming setups. BuyVM is the only setup that doesn't have a panel.

## Europe

- [TCPShield](https://github.com/qbasty/ddos-prot-mc-servers#tcpshield)
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [CosmicGuard](https://github.com/qbasty/ddos-prot-mc-servers#cosmicguard)
- [Infinity Filter](https://github.com/qbasty/ddos-prot-mc-servers#infinity-filter)
- [Game Shield](https://github.com/qbasty/ddos-prot-mc-servers#game-shield)
- [Lectron](https://github.com/qbasty/ddos-prot-mc-servers#lectron)
- [BuyVM](https://github.com/qbasty/ddos-prot-mc-servers#buyvm)
- [Packets-Decreaser](https://github.com/qbasty/ddos-prot-mc-servers#packets-decreaser)

## North America

- [TCPShield](https://github.com/qbasty/ddos-prot-mc-servers#tcpshield)
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [CosmicGuard](https://github.com/qbasty/ddos-prot-mc-servers#cosmicguard)
- [Infinity Filter](https://github.com/qbasty/ddos-prot-mc-servers#infinity-filter)
- [Game Shield](https://github.com/qbasty/ddos-prot-mc-servers#game-shield)
- [Lectron](https://github.com/qbasty/ddos-prot-mc-servers#lectron)
- [BuyVM](https://github.com/qbasty/ddos-prot-mc-servers#buyvm)

## Oceania

- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [Lectron](https://github.com/qbasty/ddos-prot-mc-servers#lectron)

## Asia

- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [Game Shield](https://github.com/qbasty/ddos-prot-mc-servers#game-shield)
- [Lectron](https://github.com/qbasty/ddos-prot-mc-servers#lectron)

## Africa and South America

- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [Lectron](https://github.com/qbasty/ddos-prot-mc-servers#lectron)

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

# MCShield

Website: https://mcshield.com

The brand new option made by MCPROHOSTING. It came out on the 20th of October 2021. The protection is Cloudflare Spectrum (42 Tbps) and there is only one plan, which costs 10 USD a month. You get unlimited bandwidth, access to 22 [locations](https://mcprohosting.com/billing/knowledgebase/106/Server-Locations-MCProHosting-Offers.html) on 6 continents and there is also a 7-day money-back guarantee. 

### Pros
- Cheap
- Unlimited bandwidth
- Cloudflare Spectrum 42Tbps Protection
- 22 locations on 6 continents

### Cons
- No Geyser Support
- Lack of information on the website
- No ip forwarding (you have to open a ticket)???
- You need to use SRV record

### For home hosting
You have access to a lot of locations + it's cloudflare so latency should be great.

### For dedicated servers
I wouldn't recommend this to bigger servers at the moment.

# Infinity Filter

Website: https://www.infinity-filter.com/en

I've talked to the developer a lot. This seems like a great TCPShield alternative. Geyser support costs additional 10$ a month. It runs on OVH servers.

### Pros
- Cheap
- Unlimited bandwidth
- Plans to expand to more locations
- Geyser support
- Custom filters
- Support is really fast

### Cons
- No Asia/Australia
- Not as many nodes as TCPShield (lower capacity)

# Game Shield

Website: https://www.gameshield.gg

I have very little info about this option for now. It runs on OVH servers.

### Pros
- Singapore location

### Cons
- No germany location?
- No geyser support
- Not as many nodes as TCPShield


# Lectron

Website: https://www.lectron.com

Soon.

# Packets-decreaser

Discord: https://discord.gg/kuyjtzC7mq
Only Netherlands location, 10ms to Hetzner.

Soon.

# PassionShield

Discord: https://discord.gg/P7TeNekAUv

Soon.

# CosmicGuard
Used by a few big networks too, but to save money, for example, 2b2t disables A LOT of packets in their queue server. 

Website: https://cosmicguard.com
More info: https://www.peeringdb.com/net/21075

Locations: Dallas, LA, Reston, Secaucus, Amsterdam, London, and Maidenhead.

### For home hosting
More locations than OVH and new locations are coming soon so if your home server doesn't have many players, Cosmic will be great.

### For dedicated servers
You can get a dedicated server from CosmicGuard in any location they have right now, setup time is 2 weeks and you get 50TB Bandwidth out of the box, it's also possible to upgrade to 10Gbit port.

### Pros
- Custom-built 1Tbps DDoS Protection
- You are charged for what you actually use
- Geyser Support

### Cons
- Pretty expensive

# BuyVM

Website: https://buyvm.net

BuyVM offers cheap VPS with Path.net DDos Protection, you have to setup nginx (or other proxy) and you don't get a panel of course. You need some linux knowledge. 4GB RAM gets 100Mbit/s but it can burst up to 1Gbit/s. 8GB RAM gets 200Mbit/s etc. This can be an issue with a lot of players or with file transfers.

### Pros
- Cheap
- Unlimited bandwidth
- Path.net 10Tbit DDos Protection
- 4 locations
- More control if that's what you want

### Cons
- Hours of downtime (personal experience, happened twice)
- Bad latency in some cases
- No easy panel (unless you don't want one)
- Vulnerable to some attacks (happened to me with a cracked/offline-mode server)

### For home hosting
3 locations in US.

### For dedicated servers
Latency to hetzner from LUX is 10-15ms which is OK but you will have a much better experience with other DDoS Protection services that have a Germany Location. I wouldn't recommend BuyVM for large servers.


# For large networks
Dedicated servers: Tempest, OVH, CosmicGuard
Protection: TCPShield, CosmicGuard

# Upcoming services:
- https://sch-cloud.com they will have a free plan and multiple locations (free plan seems to use path.net)
- https://discord.gg/pXX79xv5Td based on GSL, locations: North America, Singapore/Asia, Europe, Australia, New Zealand

# Lowering the bandwidth usage
- Lower view distance
- set compression-level to 256 or lower in your velocity config, this will increase CPU usage at the cost of lower bandwidth usage (if you run without a proxy, set it in server.properties, but if you do run with a proxy, set it to -1 on all of your paper servers)
- block some packets like 2b2t does in their queue (more on this soon) (example: https://github.com/AlexProgrammerDE/PistonQueue/blob/main/src/main/java/net/pistonmaster/pistonqueue/bukkit/ProtocolLibWrapper.java)

# Contact
Discord: qbasty#0001
