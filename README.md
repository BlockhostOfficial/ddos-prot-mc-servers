# DDoS Protection for your Minecraft Server / Network!

I'll be actively updating this guide
This guide is for those who need to protect their home server from DDoSes or Hetzner/OVH ddos protection is not good enough for you.

### Europe
- TCPShield - Free plan has 1TB Bandwidth, it's a really great option with servers in France and Germany but it might not in everyone's budget. Geyser (UDP) ddos protection only with the paid plans.
- BuyVM - Starting at 6.5 USD a month but I would recommend at least the 2048 SLICE (10 USD, 3 USD is for the ddos protected IP). I'll be soon writing a guide about how to configure a simple nginx proxy for this. They have servers in Luxembourg, around ~10-15ms to hetzner. Bedrock ddos protection also available (UDP).

### North America
- TCPShield - Same as Europe but their servers are in Canada - Beauharnois, Quebec
- BuyVM - Same pricing as Europe but you have more locations to choose from: Miami, New York, Las Vegas

### Australia
- Ausguard - https://discord.gg/TQwezt4Sq5, it's really cheap and might be an option for you. Also supports UDP (Bedrock).

### Singapore
Nothing really at the moment, if you have to choose between OVH and PhoenixNAP, get ovh as their ddos protection is better there

### Large networks
- Tempest.net - same ddos protection as BuyVM but it can handle MUCH more traffic (10 Gbit Port Speed), you might aswell just host your server on their dedicated server unless you have a huge network

### Other
- https://cosmicguard.com - I'll add this to the list soon
- https://mcshield.com - CloudFlare spectrum, costs 10$ USD a month, I'll need to learn more about them
- Cloudflare - if you have the money, go for it
- OVH - ovh ddos protection is very good in most of the cases, I'll update more about them soon
- Hetzner - if you have issues with it, get a buyvm slice in lux and kindly ask hetzner to change your ip for free :)

## Lowering the bandwidth usage
- Lower view distance
- set compression-level to 512 in your velocity config, this will increase cpu usage at the cost of lower bandwidth usage (if you run without a proxy, set it in server.properties, but if you do run with a proxy, set it to -1 on all of your paper servers)

my discord: qbasty#0001
