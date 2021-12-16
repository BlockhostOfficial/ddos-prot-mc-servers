# DDoS Protection for your Minecraft Server / Network!


This guide is for those who need to protect their home/vps/dedicated/shared server from DDoSes. If I'm wrong about something or something is missing, contact me on discord - qbasty#0001.

# Do I need DDoS Protection?
Not everyone needs DDoS Protection, your server for 2 friends doesn't, even bigger server with 50 players might not need it. You probably shouldn't worry until... yea, it happens. 

# How to check if my host has ddos protection?
Sadly, almost every dedicated/vps or even shared server hosting says that they have great DDoS Protection. Let's check that! If you don't know the IP of your server because you just have a subdomain, make sure your server is on and use https://mcsrvstat.us to get the IP of your server (Show Debug Info). Once you have the IP, head to https://ipinfo.io and enter the IP there. Look at ORG and Name, if you see something that wasn't mentioned in this guide, your host probably has none or barely any custom ddos protection.

# DDoS Protection out of the box


# Europe
Europe has options starting from 0$ a month to hundreds, it all depends on your needs. Click on the name to learn more about the pros of cons of each option.

- [TCPShield](https://github.com/qbasty/ddos-prot-mc-servers#tcpshield) - The most known protection for minecraft servers. Locations: France & Germany. Starts at 0$ a month. Geyser support starts at 100$ a month.

- [CosmicGuard](https://github.com/qbasty/ddos-prot-mc-servers#cosmicguard) - Locations: UK & Amsterdam. There isn't an unlimited bandwidth plan but their protection is used by few major servers and websites. Their pricing is different from other options since you pay for what you actually use. CosmicGuard also has Geyser protection.

- [MCShield](https://github.com/qbasty/ddos-prot-mc-servers#mcshield) - MCShield is a new option for Minecraft Servers and at the moment it looks REALLY good. It costs 10$ / month. You get unlimited bandwidth (No strings attached in ToS). No Geyser support at the moment. Their servers are in: Amsterdam, Germany, UK and France. The protection is CloudFlare Spectrum.

- [BuyVM](https://buyvm.net) (VPS Hosting) - Starting at 6.5 USD a month but I would recommend at least the 2048 SLICE (10 USD, 3 USD is for the ddos protected IP). Locations: Luxembourg, 9 to 15ms to Hetzner. Geyser (UDP) filters are also available. The protection  is Path.net. 1024 and 2048 SLICEs get a shared 100Mbit/s connection, 4096 SLICE gets a dedicated 100Mbit/s connection, 8192 SLICE gets a dedicated 200Mbit/s connection, etc. You are allowed to burst up to 1Gbit/s for some time during the times of lower network usage. I was able to get ~400 bots online on my 2048 SLICE before the connections started to get blocked. Guide coming soon on how to set this up.

- [Blockhost](https://blockhost.net) (Minecraft Server Hosting) - My own hosting company, same protection as BuyVM/Tempest(Path.net). Locations: Germany but the DDoS Protection in Luxembourg. We also have Geyser (UDP) filters.

Quick Summary for those on a budget:
| Company | Plan Name | Price | Bandwidth Limit | GeyserMC Support (UDP) | Networks (How many different servers) | Domains | Player Limit | Recommened Player Limit | Protection Capacity |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [TCPShield](https://tcpshield.com) | Free | 0$ / month | 1TB | No | 1 | 3 | None | Not sure :/ | Layer 4 16Tbps, Layer 7 Unlimited |
| [TCPShield](https://tcpshield.com) | Pro | 25$ / month | 2TB | No | 1 | 10 | None | not sure :/ |Layer 4 16Tbps, Layer 7 Unlimited |
| [MCShield](https://mcshield.com) | None | 10$ / month | Unlimited | No | Unknown | Unknown | None | None! | 42Tbps |
| [BuyVM](https://buyvm.net) | SLICE 1024 | 6.5$ / month | Unlimited | Yes | Unlimited | Unlimited | None | 100 | 6.5Tbps |
| [BuyVM](https://buyvm.net) | SLICE 2048 | 10$ / month | Unlimited  | Yes | Unlimited | Unlimited | None | 200 | 6.5Tbps |
| [BuyVM](https://buyvm.net) | SLICE 4096 | 17$ / month | Unlimited | Yes | Unlimited | Unlimited | None | 500 | 6.5Tbps |
| [CosmicGuard](https://cosmicguard.com) | 10 players AVG | 9$ / month | You pay for what you use | Yes | Unknown | Unknown | 10 avg players, 13 peak | Doesn't apply | 1 Tbps I think? |
| [CosmicGuard](https://cosmicguard.com) | 25 players AVG | 24$ / month | You pay for what you use | Yes | Unknown | Unknown | 25 avg players, 39 peak | Doesn't apply | 1 Tbps I think? |

Note for TCPShield: There isn't a player limit but you will quickly run out of bandwidth with 100+ players.

# North America
- [TCPShield](https://github.com/qbasty/ddos-prot-mc-servers#tcpshield) - The most known protection for minecraft servers. Locations: Canada. Starts at 0$ a month. Geyser support starts at 100$ a month.

- [MCShield](https://mcshield.com) - Same prices and features like in Europe. Locations: Ashburn, Chicago, Dallas, LA, NY, Seattle, San Francisco, Phoenix, Miami

- [CosmicGuard](https://cosmicguard.com) - Same pricing and features like Europe but you have more servers available: Dallas, LA, Reston and Secaucus.

- [BuyVM](https://buyvm.net) (VPS Hosting) - Same prices as in Europe but you have more locations to choose from: Miami, New York and Las Vegas. The NY SLICEs are around 10-15ms away from OVH Canada.

- [Blockhost](https://blockhost.net) (Minecraft Server Hosting) - My own hosting company, same protection as BuyVM/Tempest(Path.net). Locations: New York. We also have Geyser (UDP) filters.

- [Bloom Hosting](https://bloom.host) (Minecraft Server Hosting) - Cloudflare Magic Transit as protection. Locations: Texas, Virginia and California (The protection doesn't apply to the Germany location). Supports GeyserMC (UDP).

# Australia
- [Ausguard](https://discord.gg/TQwezt4Sq5) - A brand new DDoS Protection for Australia/New Zealand. Really cheap and might be an option for you. Supports GeyserMC (UDP).

- [MCShield](https://mcshield.com) - Another option but no Bedrock (UDP) filters.

# Singapore/ Asia
- If you have choose between OVH and PhoenixNAP, choose OVH for better DDoS Protection out of the box
- [MCShield](https://mcshield.com) - Locations: Singapore, Hong Kong
- Tempest - Learn more below. Server locations: Dubai, Taiwan and Tokyo

# Africa and South America
- Tempest - Learn more below. Server locations: Sao Paolo and Miami (Not South America but close to there)
- [MCShield](https://mcshield.com) - Location: Johannesburg, South Africa. The only DDoS protection provider in africa at the moment?

# Large networks
- [Tempest](https://tempest.net) - All servers come with a 10Gbit Port Speed which can handle A LOT of traffic and Path.net DDoS Protection (The same as BuyVM). They also have a lot of [locations](https://tempest.net/network) across 4 continents. It's expensive but it's really good.

- [Cloudflare](https://cloudflare.com) - The most expensive option but 42Tbit protection isn't cheap. Used by Hypixel.

# TCPShield

Extremely popular Minecraft Server DDoS Protection operational since 2015. Used by many large networks.

Website: https://tcpshield.com
Setup Guide: https://docs.tcpshield.com/panel/setup-process

Locations: France (Gravelines), Germany (Frankfurt), Canada (Beauharnois, Quebec)

Pros:
- Free Plan
- Great 16Tbps Layer 4 & Unlimited Layer 7 Protection
- Running since 2015, has a great reputation
- [Cloudflare Spectrum](https://docs.tcpshield.com/cloudflare-network) to reduce latency
- TCPShield Plugin to hide your server IP
- Great uptime

Cons:
- Expensive compared to the other alternatives
- Geyser Support starts at 100$ / month
- No Asia/Africa/South America/Australia locations

For dedicated servers / vps:

If you don't have a hosting for your server yet but you are interested in getting TCPShield, here is a list of hosts that will work great with TCPShield:
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

For home hosting:

If you just want to run a server for few friends but you still want some ddos protection, TCPShield is the best option at the moment if you are in Europe/North America of course.

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

Brand new option made by MCPROHOSTING. It came out on 20th of October. The protection is CloudFlare Spectrum (42 Tbps) and you there is only one plan which costs 10 USD a month. You get unlimited bandwidth, access to 22 [locations](https://mcprohosting.com/billing/knowledgebase/106/Server-Locations-MCProHosting-Offers.html) on 6 continents and there is also 7 day money back guarantee. 

Pros:
- 10 USD a month for unlimited bandwidth
- CloudFlare Spectrum 42Tbps Protection
- 22 locations on 6 continents

Cons:
- Brand new
- Run by a hosting company that runs your server on a Dual Xeon E5-2600 CPU
- No Geyser Support
- Lack of information on the website

# BuyVM
BuyVM is a VPS provider, this isn't a fancy panel like TCPShield. You will have to configure a nginx proxy to protect your server. But before that, some info here:

### Which SLICE?
I wouldn't recommend the 512 SLICE at all as it's just not enough power. 1024 is the bare minimum, I recommend at least the 2048 SLICE, 4096 will run pretty good.
512, 1024 and 2048 SLICE get a shared 100Mbit/s but you can burst up to 1Gbit/s if there isn't much traffic on the whole network at the moment. 4096 SLICE gets a dedicated 100Mbit/s, 8192 gets a dedicated 200Mbit/s, etc. 

### How to order
Simply go [here](https://buyvm.net/kvm-dedicated-server-slices/), choose the slice you want, the location and then in the order form order x1 DDOS PROTECTED IP. If you get an out of stock error, join [here](https://discord.gg/3hs44DjPc8) to wait for the stock. 

More soon!

# Lowering the bandwidth usage
- Lower view distance
- set compression-level to 256 in your velocity config, this will increase cpu usage at the cost of lower bandwidth usage (if you run without a proxy, set it in server.properties, but if you do run with a proxy, set it to -1 on all of your paper servers)
- block some packets like 2b2t does in their queue (more on this soon)


## Contact
Discord: qbasty#0001
