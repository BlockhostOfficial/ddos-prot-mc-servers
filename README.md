# DDoS Protection for your Minecraft Server!

If you are experiencing issues with DDoSes on your Minecraft Server or you want to protect your server against them, this guide is for you.
Contact: qbasty#0001

Note: there are some affiliate links in the list and I'll earn from them a % of the purchase

# Do I need DDoS Protection?
If your server is small or just private, you don't have to worry about DDoSes but there are many free DDoS tools today and some hosts can't even protect you against them so it might be worth it to spend a litle bit more money on DDoS protection or a good host with DDoS protection.

## Dedicated Server Providers
Dedicated Server Providers with DDoS Protection out of the box so you don't have to worry about attacks later on.

Good/Great:
- Tempest - Path.net DDoS Protection together with 10Gbit traffic and port. The biggest issues with Path.net are stability and latency. Current capacity is 10Tbit.
- OVH - OVH has great protection but there are some issues with their network (latency + internal attacks), billing and support is non-existent for many. SoYouStart and Kimsufi have the same protection. TCPShield and Infinity Filter run on OVH with custom filters and load balancing.
- CosmicGuard - CosmicGuard now has their own dedicated servers. Open a ticket / live chat if interested.

Ok/Bad:
- Hetzner - In case you have issues with their protection, you can request 1 IP change for free so you can upgrade to some DDoS protection service
- ReliableSite
- PhoenixNAP

# Best Protection
Don't use this as your main reason to buy / not buy. This is my personal opinon based on my and other's experience.

1. CosmicGuard - Out of the box it wasn't fully ready but we quickly had everything setup (dedicated server). The biggest issue for me right now is latency to Asia.
2. Path.net - When using BuyVM, we had issues with uptime, latency and L7 attacks. We had to setup iptables to stop the attack.
3. Cloudflare
4. OVH (without any custom filters)

# Favourite services
Lectron - pay-as-you-use billing + 210 locations with CloudFlare's minimal latency - [https://lectron.com](https://lec.net/qbasty)

InfinityFilter - similar protection as TCPShield but much better billing system, also has a free plan - [https://www.infinity-filter.com](https://panel.infinity-filter.com/partner/8f0fcec8-0c54-4c5c-a425-27867bcc248a)

CosmicGuard - Amazing protection that also stops many bots - https://cosmicguard.com/

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

Website: [https://www.lectron.com](https://lec.net/qbasty)

This seems like the perfect middle between CosmicGuard's pay-as-you-use billing and MCShield's huge number of locations. 
They use CloudFlare for the proxies and Path.net for the tunnel.

### Pros
- 210 Proxy (CloudFlare) Locations
- 21 Tunnel (Path.net) Locations
- Pay-as-you-go billing
- Many filters - TCP, UDP, HTTP, HTTPS
- Custom filters

### Cons:
- Bit expensive for big servers (high bandwidth usage)

# Packets-decreaser

Discord: https://discord.gg/kuyjtzC7mq
Only Netherlands location, 10ms to Hetzner.

Soon.

# PassionShield

Discord: https://discord.gg/P7TeNekAUv

Soon.

# CosmicGuard

Used by a few big networks too.

Website: https://cosmicguard.com
More info: https://www.peeringdb.com/net/21075

Locations: Dallas, LA, Reston, Secaucus, Amsterdam, London, and Maidenhead.

### Pros
- Custom-built 1Tbps DDoS Protection
- You are charged for what you actually use
- Geyser Support

### Cons
- Pretty expensive
- No Asia/Australia Locations

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


# Upcoming services:
- https://sch-cloud.com they will have a free plan and multiple locations (free plan seems to use path.net)
- https://discord.gg/pXX79xv5Td based on GSL, locations: North America, Singapore/Asia, Europe, Australia, New Zealand

# Lower the bandwidth usage:
Soon

# Contact
Discord: qbasty#0001
