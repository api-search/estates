---
api_total: 2
category: Estates
description: 'SS&C Technologies Holdings (NASDAQ: SSNC) is a global provider of financial-services and
  healthcare software and outsourcing, headquartered in Windsor, Connecticut, operating under brands including
  SS&C Advent, SS&C Eze, SS&C GlobeOp, SS&C GIDS, SS&C Intralinks, SS&C Black Diamond, SS&C Algorithmics
  and SS&C Blue Prism. Most of the API surface is client-gated: the corporate SS&C APIM developer portal
  at developer.ssctech.com and the Black Diamond developer portal both require an account, and access
  is requested through a client relationship manager. The substantial public exception is SS&C Eze EMS
  xAPI, whose machine-readable contract SS&C Eze publishes openly on GitHub as three proto3 files — 64
  gRPC RPCs across MarketDataService, SubmitOrderService and UtilityServices — alongside a matching REST
  projection described by a live OpenAPI 3.0.4 document with 73 operations covering order submission and
  amendment, pair and basket orders, allocations and trade reports, real-time and historical market data,
  and intraday balances, positions and activity.'
estate_rating:
  agent_avg: 14.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 18.8
  agent_ready: 1
  band: emerging
  best: 49.2
  composite_avg: 25.3
  composite_band: thin
  composite_raw: 30.2
  developing: 2
  exemplar: 0
  rating: 20.8
  scored: 3
  spread: 47.9
  strength: 2
  strong: 0
  worst: 1.3
estate_root: null
estate_root_name: null
image: https://www.ssctech.com/hubfs/website/logos/ssc_logo_1200x630.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 31.5
    api_count: 1
    immediate_parent: ss-c-technologies
    name: Blue Prism
    relationship: product
    score_band: developing
    score_composite: 49.2
    slug: blue-prism
    source: prose
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 1
    immediate_parent: ss-c-technologies
    name: SS&C Geneva
    relationship: product
    score_band: developing
    score_composite: 40.1
    slug: ssc-geneva
    source: declared
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: ss-c-technologies
    name: DST Systems
    relationship: product
    score_band: minimal
    score_composite: 1.3
    slug: dst-systems
    source: prose
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: SS&C Technologies
overview: 'SS&C Technologies publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 47.9 points, from 49.2 down to 1.3.


  Its highest-rated surfaces are Blue Prism, SS&C Geneva, DST Systems.'
parent_provider: ss-c-technologies
permalink: /estates/ss-c-technologies/
slug: ss-c-technologies
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ss-c-technologies/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Financial-Services
- Investment Management
- Fund Administration
- Wealth Management
- Execution Management
- Order Management
- Market Data
- Trading
- gRPC
- Enterprise Software
title: SS&C Technologies
---
