# DDoS Protection for your Minecraft Server / Network!

This guide is for those who need to protect their home server from DDoSes or Hetzner/OVH ddos protection is not good enough for you. If I'm wrong about something or something is missing, contact me on discord.

### Europe
- TCPShield - Free plan has 1TB Bandwidth, it's a really great option with servers in France and Germany but it might be in not everyone's budget. Geyser (UDP) ddos protection available only with the paid plans.
- BuyVM - Starting at 6.5 USD a month but I would recommend at least the 2048 SLICE (10 USD, 3 USD is for the ddos protected IP). I'll be soon writing a guide about how to configure a simple nginx proxy for this. They have servers in Luxembourg, around ~10-15ms to hetzner. Bedrock ddos protection also available (UDP). Note: 512, 1024 and 2048 have a shared 100mbps connection, 4096 has dedicated 100mbps, 8192 has 200mbps, etc. You can use as high as 1gbps for some time if the network isnt full.
- CosmicGuard - UK and Amsterdam. There isn't an unlimited bandwidth plan but their protection is known for being really good.
- Hetzner - (dedicated servers) should be good in most cases, if you have issues with it, kindly ask hetzner to change your ip and switch to one of the above mentioned options
- OVH - (dedicated servers), they have ddos protection better than hetzner. TCPShield is just a network of OVH Servers; OVH VPS is another story ;). Internal attacks might be an issue. I'm pretty sure the GAME servers have best DDoS Protection for minecraft.

### North America
- TCPShield - Same as Europe but their servers are in Canada - Beauharnois, Quebec
- BuyVM - Same pricing as Europe but you have more locations to choose from than OVH/TCPShield : Miami, New York, Las Vegas
- Bloom.host - you can host your proxy server there, it's Cloudflare Magic Transit and they have Texas, Virginia and California locations (colocation, not reselling)
- blockbost.net - my own hosting company, has the same ddos protection as buyvm/tempest(path.net), eu and us plans.
- OVH - same as europe
- CosmicGuard - Dallas, LA, Reston, Secaucus. Same as europe.

### Australia
- Ausguard - https://discord.gg/TQwezt4Sq5, it's really cheap and might be an option for you. Also supports UDP (Bedrock).
- OVH - if you have issues with it, give ausguard a try

### Singapore
- Nothing really at the moment, if you have to choose between OVH and PhoenixNAP, get ovh as their ddos protection is better there

### Large networks
- Tempest.net - same ddos protection as BuyVM but it can handle MUCH more traffic (10 Gbit Port Speed), you might aswell just host your server on their dedicated server unless you have a huge network and you just need ddos protection. Their locations: https://tempest.net/network.
- Cloudflare - if you have the money, go for it, hypixel uses cloudflare

### Other
- https://mcshield.com - CloudFlare spectrum, costs 10$ USD a month, I'll need to learn more about them. Edit: for that 10 usd you get unlimited bandwidth :O

## Lowering the bandwidth usage
- Lower view distance
- set compression-level to 512 in your velocity config, this will increase cpu usage at the cost of lower bandwidth usage (if you run without a proxy, set it in server.properties, but if you do run with a proxy, set it to -1 on all of your paper servers)
- block some packets like 2b2t does in their queue (more on this soon)


## Contact
Discord: qbasty#0001
