---
title: "Intermittent disruptions of service"
url: "https://api.met.no/blog/2023-12-07-disruptions"
date: "2023-12-07"
feed_url: "https://api.met.no/feed/news"
---
On Monday afternoon (Dec 4th) we had a severe outbreak of planned maintenance, which resulted in disruption of most MET services between 15:00 and 18:00 UTC. To cut a long story short, someone tried to turn off some old DNS servers which were thought not to be in use, which resulted in DHCP overload and most VMs becoming unresponsive. From what we can see, api.met.no was unavailable for about 1 hour and 39 minutes, although delivery varied from product to product.
