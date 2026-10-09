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
  agent_avg: 8.3
  agent_band: minimal
  agent_native: 0
  agent_raw: 4.7
  agent_ready: 0
  band: emerging
  best: 16.4
  composite_avg: 15.5
  composite_band: emerging
  composite_raw: 7.5
  developing: 0
  exemplar: 0
  rating: 12.6
  scored: 3
  spread: 13.7
  strength: 0
  strong: 0
  worst: 2.7
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
    api_count_basis: split
    immediate_parent: coinbase
    name: Coinbase Pro
    relationship: product
    score_band: emerging
    score_composite: 16.4
    slug: coinbase-pro
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: coinbase
    name: Bison Trails
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: bison-trails
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: coinbase
    name: Earn
    relationship: acquisition
    score_band: minimal
    score_composite: 2.7
    slug: earn
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: coinbase
    name: Azarus
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: azarus
    source: prose
  label: Unrated
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
  of which 4 carry a rating. The rated members span 13.7 points, from 16.4 down to 2.7.


  Its highest-rated surfaces are Coinbase Pro, Bison Trails, Earn, Azarus.'
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
- Agentic Commerce
- x402
- Real-Time
title: Coinbase
---
