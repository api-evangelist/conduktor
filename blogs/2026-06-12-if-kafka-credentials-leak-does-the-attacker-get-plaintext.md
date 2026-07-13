---
title: "If Kafka Credentials Leak, Does the Attacker Get Plaintext or Ciphertext?"
url: "https://www.conduktor.io/blog/kafka-credentials-leak-plaintext-or-ciphertext"
date: "2026-06-12"
author: "stephane-derosiaux"
feed_url: "https://www.conduktor.io/blog/feed.xml"
---
TLS, disk encryption, and BYOK each stop a different attacker. None of them stops a leaked Kafka credential from reading topics in plaintext.
