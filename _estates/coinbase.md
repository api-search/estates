---
api_total: 1
category: Estates
description: Coinbase is a leading cryptocurrency platform providing trading, custody, and payment infrastructure
  for individuals, businesses, and institutions. The Coinbase Developer Platform (CDP) exposes a wide
  product surface across retail trading (Advanced Trade), professional and institutional trading (Exchange
  and Prime), merchant payments (Commerce), fiat onboarding (Onramp), developer wallet integration (Wallet
  SDK), market and on-chain data (Data API), and AI agent toolkits (AgentKit). Authentication is performed
  using API keys with HMAC-SHA256 signatures (Advanced Trade, Exchange) or JWT bearer tokens (Prime, CDP),
  with WebSocket and FIX feeds available for low-latency market data and order management.
estate_rating:
  agent_avg: 7.7
  agent_band: minimal
  agent_native: 0
  agent_raw: 3.5
  agent_ready: 0
  band: emerging
  best: 20.8
  composite_avg: 16.1
  composite_band: emerging
  composite_raw: 8.1
  developing: 0
  exemplar: 0
  rating: 12.7
  scored: 4
  spread: 19.3
  strength: 0
  strong: 0
  worst: 1.5
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/coinbase.png
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 14.0
    api_count: 1
    immediate_parent: coinbase
    name: Coinbase Pro
    relationship: product
    score_band: emerging
    score_composite: 20.8
    slug: coinbase-pro
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: coinbase
    name: Azarus
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: azarus
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: coinbase
    name: Bison Trails
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: bison-trails
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: coinbase
    name: Earn
    relationship: product
    score_band: minimal
    score_composite: 1.5
    slug: earn
    source: prose
  label: Minimal
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Coinbase
overview: 'Coinbase publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 19.3 points, from 20.8 down to 1.5.


  Its highest-rated surfaces are Coinbase Pro, Azarus, Bison Trails, Earn.'
parent_provider: coinbase
permalink: /estates/coinbase/
slug: coinbase
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Blockchain
- Cryptocurrency
- Custody
- Exchange
- On-Ramp
- Payments
- Trading
- Wallets
- Web3
title: Coinbase
---
