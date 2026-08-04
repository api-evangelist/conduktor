---
title: "Kafka Partitions are the wrong ordering abstraction. Keys are."
url: "https://www.conduktor.io/blog/kafka-partitions-are-the-wrong-ordering-abstraction-keys-are"
date: "2026-06-01"
author: "stephane-derosiaux"
feed_url: "https://www.conduktor.io/blog/feed.xml"
---
Confluent deprecated Parallel Consumer and points to Share Consumers. Different problem: in event-driven systems, the key is the real unit of work.
