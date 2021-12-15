# DDoS Protection for your Minecraft Server / Network!


This guide is for those who need to protect their home/vps/dedicated/shared server from DDoSes. If I'm wrong about something or something is missing, contact me on discord - qbasty#0001.


# Europe
- [TCPShield](https://tcpshield.com) - The most popular DDoS Protection for minecraft servers. TCPShield's servers are in France and Germany. Here is a table comparing all the plans quickly: 

| Plan  | Price  | Bandwidth Limit  | Bedrock Support (UDP)  | Networks (How many different servers)  | Domains  |
| --- | --- | --- | --- | --- | --- |
| Free  | 0$ / month  | 1TB  | :x:  | 1  | 3  |
| Pro  | 25$ / month  | 2TB  | :x:  | 1  | 10  |
| Premium  | 100$ / month  | Unlimited  | :white_check_mark:  | 3  | 25  |
| Enterprise  | 250$ / month  | Unlimited  | :white_check_mark:  | 10  | Unlimited  |

- [CosmicGuard](https://cosmicguard.com) - Locations: UK and Amsterdam. There isn't an unlimited bandwidth plan but their protection is known for being really good. I really like their pricing since you pay for what you actually use.
- [MCShield](https://mcshield.com) - 10$ / month. Unlimited bandwidth. No Geyser (UDP) support at the moment. Locations: Amsterdam, Germany, UK, France.
- [BuyVM](https://buyvm.net) (VPS Hosting) - Starting at 6.5 USD a month but I would recommend at least the 2048 SLICE (10 USD, 3 USD is for the ddos protected IP). Locations: Luxembourg, 9 to 15ms to Hetzner. Geyser (UDP) filters also available. The protection is path.net. Shared 100Mbit connection for 1024 and 2048. Dedicated 100Mbit for 4096, dedicated 200Mbit for 8192, etc. You can use as high as 1gbit for some time if the network isn't full. I was able to get ~400 bots online on my 2048 SLICE before the connections started to get blocked.
- [Blockhost](https://blockhost.net) (Minecraft Server Hosting) - My own hosting company, same protection as BuyVM/Tempest(Path.net). Locations: Germany and New York. Supports Geyser (UDP).
- [Hetzner](https://hetzner.com) (Dedicated Server Hosting) - Their filters are good enough for some people. If that's not the case for you, request an IP change and switch to one of the above mentioned DDoS Protection providers.
- [OVH](https://www.ovhcloud.com/en/) (Dedicated Server Hosting) - TCPShield is a custom network based on OVH servers so it should be good in most cases. Internal attacks are an issue for some people. The GAME range has the best DDoS Protection for Minecraft. (This doesn't apply to the VPS)

Quick Summary for those on a budget:
| Company | Plan Name | Price | Bandwidth Limit | GeyserMC Support (UDP) | Networks (How many different servers) | Domains | Player Limit | Protection Capacity | Limits |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [TCPShield](https://tcpshield.com) | Free | 0$ / month | 1TB | No | 1 | 3 | None, but you have only 1TB of bandwidth! | Layer 4 16Tbps, Layer 7 Unlimited | :x: |
| [TCPShield](https://tcpshield.com) | Pro | 25$ / month | 2TB | No | 1 | 10 | None, but you have only 2TB of bandwidth! | Layer 4 16Tbps, Layer 7 Unlimited | :x: |
| [MCShield](https://mcshield.com) | None | 10$ / month | Unlimited | No | Unknown | Unknown | None | 42Tbps | :x: |
| [BuyVM](https://buyvm.net) | SLICE 1024 | 6.5$ / month | Unlimited | Yes | Unlimited | Unlimited | None, but I wouldn't suggest more than 50 players | 6.5Tbps | Shared 100Mbit/s connection, burst up to 1Gbit/s |
| [BuyVM](https://buyvm.net) | SLICE 2048 | 10$ / month | Unlimited  | Yes | Unlimited | Unlimited | None, but I wouldn't suggest more than 200 players | 6.5Tbps | Shared 100Mbit/s connection, burst up to 1Gbit/s |
| [BuyVM](https://buyvm.net) | SLICE 4096 | 17$ / month | Unlimited | Yes | Unlimited | Unlimited | None, but I wouldn't suggest more than 500 players | 6.5Tbps | Dedicated 100Mbit/s connection, burst up to 1Gbit/s |
| [CosmicGuard](https://cosmicguard.com) | 10 players AVG | 9$ / month | You pay for what you use | Yes | Unknown | Unknown | 10 avg players, 13 peak | 1 Tbps I think? | :x: |
| [CosmicGuard](https://cosmicguard.com) | 25 players AVG | 24$ / month | You pay for what you use | Yes | Unknown | Unknown | 25 avg players, 39 peak | 1 Tbps I think? | :x: |

If you a larger server, definetely learn more about all these options.

### North America
- [TCPShield](https://tcpshield.com) - Same as Europe, their servers are in Canada - Beauharnois, Quebec
- [BuyVM](https://buyvm.net) (VPS Hosting) - Same prices as in Europe but you have more locations to choose from: Miami, New York, Las Vegas
- [CosmicGuard](https://cosmicguard.com) - Dallas, LA, Reston, Secaucus. Same as europe.
- [Blockhost](https://blockhost.net) (Minecraft Server Hosting) - My own hosting company, same protection as BuyVM/Tempest(Path.net). Locations: Germany and New York. Supports GeyserMC(UDP).
- [Bloom Hosting](https://bloom.host) (Minecraft Server Hosting) - Cloudflare Magic Transit as protection. Locations: Texas, Virginia and California (The protection doesn't apply to the Germany location). Supports GeyserMC(UDP).

### Australia
- [Ausguard](https://discord.gg/TQwezt4Sq5) - Really cheap and might be an option for you. Supports GeyserMC(UDP).

### Singapore
- Nothing really at the moment, if you have to choose between OVH and PhoenixNAP, get ovh as their ddos protection is better there

### Large networks
- Tempest.net - same ddos protection as BuyVM but it can handle MUCH more traffic (10 Gbit Port Speed), you might aswell just host your server on their dedicated server unless you have a huge network and you just need ddos protection. Their locations: https://tempest.net/network.
- Cloudflare - if you have the money, go for it, hypixel uses cloudflare

### Other
- https://mcshield.com - CloudFlare spectrum, costs 10$ USD a month, I'll need to learn more about them. Edit: for that 10 usd you get unlimited bandwidth :O No GeyserMC(UDP) Protection

## Lowering the bandwidth usage
- Lower view distance
- set compression-level to 512 in your velocity config, this will increase cpu usage at the cost of lower bandwidth usage (if you run without a proxy, set it in server.properties, but if you do run with a proxy, set it to -1 on all of your paper servers)
- block some packets like 2b2t does in their queue (more on this soon)


## Contact
Discord: qbasty#0001
