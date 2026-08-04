---
title: "AWS MSK Authentication: OIDC and mTLS Without Touching the Broker"
url: "https://www.conduktor.io/blog/kafka-msk-authentication-oidc-mtls"
date: "2026-07-21"
author: "siddhanth-lathar"
feed_url: "https://www.conduktor.io/blog/feed.xml"
---
AWS MSK clients can only use IAM, SCRAM, or ACM-bound mTLS. Here's how to use OIDC and mTLS with AWS MSK by terminating the scheme at a Kafka proxy.
