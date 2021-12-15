# DDoS Protection for your Minecraft Server / Network!


This guide is for those who need to protect their home/vps/dedicated/shared server from DDoSes. If I'm wrong about something or something is missing, contact me on discord - qbasty#0001.


# Europe
- [TCPShield](https://tcpshield.com) - The most popular DDoS Protection for Minecraft servers and the only one on this list which is free. TCPShield's servers are in France and Germany. Here is a table comparing all the plans quickly: 

| Plan  | Price  | Bandwidth Limit  | Bedrock Support (UDP)  | Networks (How many different servers)  | Domains  |
| --- | --- | --- | --- | --- | --- |
| Free  | 0$ / month  | 1TB  | :x:  | 1  | 3  |
| Pro  | 25$ / month  | 2TB  | :x:  | 1  | 10  |
| Premium  | 100$ / month  | Unlimited  | :white_check_mark:  | 3  | 25  |
| Enterprise  | 250$ / month  | Unlimited  | :white_check_mark:  | 10  | Unlimited  |

- [CosmicGuard](https://cosmicguard.com) - CosmicGuard's servers are in UK and Amsterdam. There isn't an unlimited bandwidth plan but their protection is used by few major servers and websites. Their pricing is different from other options since you pay for what you actually use. CosmicGuard also has Geyser (UDP) Protection.

- [MCShield](https://mcshield.com) - MCShield is a new option for Minecraft Servers and at the moment it looks REALLY good. It costs 10$ / month. You get unlimited bandwidth (No strings attached in ToS). No Geyser (UDP) support at the moment. Their servers are in: Amsterdam, Germany, UK and France. The protection is CloudFlare Spectrum.

- [BuyVM](https://buyvm.net) (VPS Hosting) - Starting at 6.5 USD a month but I would recommend at least the 2048 SLICE (10 USD, 3 USD is for the ddos protected IP). Locations: Luxembourg, 9 to 15ms to Hetzner. Geyser (UDP) filters are also available. The protection  is Path.net. 1024 and 2048 SLICEs get a shared 100Mbit/s connection, 4096 SLICE gets a dedicated 100Mbit/s connection, 8192 SLICE gets a dedicated 200Mbit/s connection, etc. You are allowed to burst up to 1Gbit/s for some time during the times of lower network usage. I was able to get ~400 bots online on my 2048 SLICE before the connections started to get blocked. Guide coming soon on how to set this up.

- [Blockhost](https://blockhost.net) (Minecraft Server Hosting) - My own hosting company, same protection as BuyVM/Tempest(Path.net). Locations: Germany but the DDoS Protection in Luxembourg. We also have Geyser (UDP) filters.

Quick Summary for those on a budget:
| Company | Plan Name | Price | Bandwidth Limit | GeyserMC Support (UDP) | Networks (How many different servers) | Domains | Player Limit | Protection Capacity | Limits |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [TCPShield](https://tcpshield.com) | Free | 0$ / month | 1TB | No | 1 | 3 | None | Layer 4 16Tbps, Layer 7 Unlimited | :x: |
| [TCPShield](https://tcpshield.com) | Pro | 25$ / month | 2TB | No | 1 | 10 | None | Layer 4 16Tbps, Layer 7 Unlimited | :x: |
| [MCShield](https://mcshield.com) | None | 10$ / month | Unlimited | No | Unknown | Unknown | None | 42Tbps | :x: |
| [BuyVM](https://buyvm.net) | SLICE 1024 | 6.5$ / month | Unlimited | Yes | Unlimited | Unlimited | None, but I wouldn't suggest more than 50 players | 6.5Tbps | Shared 100Mbit/s connection, burst up to 1Gbit/s |
| [BuyVM](https://buyvm.net) | SLICE 2048 | 10$ / month | Unlimited  | Yes | Unlimited | Unlimited | None, but I wouldn't suggest more than 200 players | 6.5Tbps | Shared 100Mbit/s connection, burst up to 1Gbit/s |
| [BuyVM](https://buyvm.net) | SLICE 4096 | 17$ / month | Unlimited | Yes | Unlimited | Unlimited | None, but I wouldn't suggest more than 500 players | 6.5Tbps | Dedicated 100Mbit/s connection, burst up to 1Gbit/s |
| [CosmicGuard](https://cosmicguard.com) | 10 players AVG | 9$ / month | You pay for what you use | Yes | Unknown | Unknown | 10 avg players, 13 peak | 1 Tbps I think? | :x: |
| [CosmicGuard](https://cosmicguard.com) | 25 players AVG | 24$ / month | You pay for what you use | Yes | Unknown | Unknown | 25 avg players, 39 peak | 1 Tbps I think? | :x: |

Note for TCPShield: There isn't a player limit but you will quickly run out of bandwidth with 100+ players.
Note for BuyVM: Head above to learn about their connection limits.

# North America
- [TCPShield](https://tcpshield.com) - Same pricing and features as Europe, their servers are in Canada - Beauharnois, Quebec.

- [MCShield](https://mcshield.com) - Same prices and features like in Europe. Locations: Ashburn, Chicago, Dallas, LA, NY, Seattle, San Francisco, Phoenix, Miami
- 
- [BuyVM](https://buyvm.net) (VPS Hosting) - Same prices as in Europe but you have more locations to choose from: Miami, New York and Las Vegas. The NY SLICEs are around 10-15ms away from OVH Canada.

- [CosmicGuard](https://cosmicguard.com) - Same pricing and features like Europe but you have more servers available: Dallas, LA, Reston and Secaucus.

- [Blockhost](https://blockhost.net) (Minecraft Server Hosting) - My own hosting company, same protection as BuyVM/Tempest(Path.net). Locations: New York. We also have Geyser (UDP) filters.

- [Bloom Hosting](https://bloom.host) (Minecraft Server Hosting) - Cloudflare Magic Transit as protection. Locations: Texas, Virginia and California (The protection doesn't apply to the Germany location). Supports GeyserMC (UDP).

# Australia
- [Ausguard](https://discord.gg/TQwezt4Sq5) - A brand new DDoS Protection for Australia/New Zealand. Really cheap and might be an option for you. Supports GeyserMC (UDP).

# Singapore/ Asia
- Nothing really at the moment, OVH has better DDoS Protection in Singapore than PhoenixNAP.

# Large networks
- Tempest.net - All servers come with a 10Gbit Port Speed which can handle A LOT of traffic and Path.net DDoS Protection (The same as BuyVM). They also have a lot of locations across 4 continents.

- Cloudflare - The most expensive option but 42Tbit protection isn't cheap. Used by Hypixel.

## Lowering the bandwidth usage
- Lower view distance
- set compression-level to 512 in your velocity config, this will increase cpu usage at the cost of lower bandwidth usage (if you run without a proxy, set it in server.properties, but if you do run with a proxy, set it to -1 on all of your paper servers)
- block some packets like 2b2t does in their queue (more on this soon)


## Contact
Discord: qbasty#0001
