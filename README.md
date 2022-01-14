# DDoS Protection for your Minecraft Server / Network!

This guide is for those who need to protect their home/VPS/dedicated/shared server from DDoS attacks. If I'm wrong about something or something is missing, contact me on discord - qbasty#0001.

# Do I need DDoS Protection?
Not everyone needs DDoS Protection, a server for 2 friends doesn't, but even bigger servers with 50 players might need it. You probably shouldn't worry until you actually start having issues with DDoSes. 

## Dedicated Server Providers
Dedicated Server Providers with DDoS Protection that I can/can't recommend

Very Good/Amazing:
- Tempest - Path.net DDoS Protection together with 10Gbit traffic. The biggest issues with path.net are stability and latency.
- OVH - TCPShield and Infinity-Filter are running on OVH machines. Some of the issues are internal attacks and bad support.

Good/Decent:
- Hetzner - It's good enough for some people. You can request an IP reset for free.
- ReliableSite

Bad/Horrible:
- OVH VPS
- PhoenixNAP

More soon

# Protection with panel and support
These are some great options for those who don't want to spend too much time worrying all of this.

## Europe

- [TCPShield](https://github.com/qbasty/ddos-prot-mc-servers#tcpshield)
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [CosmicGuard](https://github.com/qbasty/ddos-prot-mc-servers#cosmicguard)
- [Infinity Filter](https://github.com/qbasty/ddos-prot-mc-servers#infinity-filter)
- [Game Shield](https://github.com/qbasty/ddos-prot-mc-servers#game-shield)
- [Lectron](https://github.com/qbasty/ddos-prot-mc-servers#lectron)

## North America

- [TCPShield](https://github.com/qbasty/ddos-prot-mc-servers#tcpshield)
- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield)
- [CosmicGuard](https://github.com/qbasty/ddos-prot-mc-servers#cosmicguard)
- [Infinity Filter](https://github.com/qbasty/ddos-prot-mc-servers#infinity-filter)
- [Game Shield](https://github.com/qbasty/ddos-prot-mc-servers#game-shield)
- [Lectron](https://github.com/qbasty/ddos-prot-mc-servers#lectron)

## Oceania

- [Ausguard](https://github.com/qbasty/ddos-prot-mc-servers#ausguard)
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
- Let's hope this isn't bad like MCProHosting can be
- No Geyser Support
- Lack of information on the website
- No ip forwarding (you have to open a ticket)???

### For home hosting
You have more locations than TCPShield. UK Location is available.

### For dedicated servers
I wouldn't recommend this to bigger servers at the moment.

# Infinity Filter

Website: https://www.infinity-filter.com/en

I've talked to the developer a lot. This seems like a great TCPShield alternative. Geyser support costs additional 10$ a month.

### Pros
- Cheap
- Unlimited bandwidth
- Plans to expand to UK, Poland
- Geyser support
- Custom filters
- Really cool panel and discord notifications coming soon

### Cons
- France, Germany and Canada
- Not as many nodes as TCPShield

# Game Shield

Website: https://www.gameshield.gg

I have very little info about this option for now.

### Pros
- Singapore location :woah:

### Cons
- No germany location?
- Vulnarable to some attacks
- No geyser support
- Not as many nodes as TCPShield


# Lecton

Website: https://www.lectron.com

Soon.

# CosmicGuad
Used by a few big networks too, but to save money, for example, 2b2t disables A LOT of packets in their queue server. 

Website: https://cosmicguard.com
More info: https://www.peeringdb.com/net/21075

Locations: Dallas, LA, Reston, Secaucus, Amsterdam, London, and Maidenhead.

### For home hosting
UK Location is available.

### For dedicated servers
You could protect your PebbleHost UK dedicated server with CosmicGuard I guess?

### Pros
- Custom-built 1Tbps DDoS Protection (EDIT: You get null routed if the attack is 500Gb or more)
- You are charged for what you actually use
- Geyser Support

### Cons
- Pretty expensive

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
DM me on discord and I can help you choose the best option.

# Lowering the bandwidth usage
- Lower view distance
- set compression-level to 256 or lower in your velocity config, this will increase CPU usage at the cost of lower bandwidth usage (if you run without a proxy, set it in server.properties, but if you do run with a proxy, set it to -1 on all of your paper servers)
- block some packets like 2b2t does in their queue (more on this soon)

# Contact
Discord: qbasty#0001
