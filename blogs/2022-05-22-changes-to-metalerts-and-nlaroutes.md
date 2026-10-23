---
title: "Changes to MetAlerts and NLAroutes"
url: "https://api.met.no/blog/2022-05-22-metalerts-nlaroutes"
date: "2022-05-22"
feed_url: "https://api.met.no/feed/news"
---
MetAlerts From 1 June 2022 there will be some changes in the CAP warnings in MetAlerts : https://api.met.no/weatherapi/metalerts/1.1/ Some of the area polygons will now be drawn freehand by the meteorologists, and will be in better agreement with the actual weather situation. We will still use geocode "county" and "municipalityId" for the affected administrative areas, but geocodes NUTS3 and iso will no longer be included in the CAP file. We suggest that users of CAP warnings make some extra checks after 1 June to ensure their systems are running as intended.
