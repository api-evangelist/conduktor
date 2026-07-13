---
title: "SNI Routing vs Port Routing in a Kafka Proxy"
url: "https://www.conduktor.io/blog/kafka-proxy-sni-routing-vs-port-routing"
date: "2026-07-08"
author: "stephane-derosiaux"
feed_url: "https://www.conduktor.io/blog/feed.xml"
---
A Kafka proxy must give every client a routable address for every broker. Port-per-broker breaks at scale; SNI routing is the production answer, at a cost.
