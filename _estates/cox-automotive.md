---
api_total: 2
category: Estates
description: 'Cox Automotive is one of the world''s largest providers of products and services spanning
  the automotive ecosystem, operating a portfolio of brands that includes Manheim (wholesale vehicle auctions
  and remarketing), Kelley Blue Book (vehicle valuations and editorial data), Autotrader, Dealertrack
  (DMS, registration and titling, credit applications), vAuto, VinSolutions, Xtime, Dealer.com, HomeNet
  and Esntial. Its public API surface is split across several developer properties: the Kelley Blue Book
  Developer Portal (developer.kbb.com) publishes Swagger 2.0 contracts for the IDWS 4.0 vehicle and editorial
  services, the Advertising Data API, the Instant Cash Offer API and the Batch VIN API; the Manheim Developer
  Portal (developer.manheim.com) documents a hypermedia REST suite covering auctions, inventory, marketplace
  offerings, valuations, condition reports, images, users and a publish/subscribe event notification service;
  and the Cox Automotive Integration Platform / API Storefront (developer.coxautoinc.com) fronts the partner-gated
  catalogue of more than seventy runtime services visible on the public Cox Automotive API status page.
  Access to every environment is granted after a review by a Cox Automotive account representative, with
  keys issued through the Boomi/Mashery gateway.'
estate_rating:
  agent_avg: 11.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 11.9
  agent_ready: 1
  band: emerging
  best: 51.9
  composite_avg: 21.5
  composite_band: emerging
  composite_raw: 23.2
  developing: 1
  exemplar: 0
  rating: 17.3
  scored: 3
  spread: 48.5
  strength: 1
  strong: 0
  worst: 3.4
estate_root: null
estate_root_name: null
image: https://www.coxautoinc.com/wp-content/uploads/2025/09/CAI-1200x628-1.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 35.6
    api_count: 2
    immediate_parent: cox-automotive
    name: AutoLeadStar
    relationship: acquisition
    score_band: developing
    score_composite: 51.9
    slug: autoleadstar
    source: prose
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cox-automotive
    name: Xtime
    relationship: product
    score_band: emerging
    score_composite: 14.4
    slug: xtime
    source: prose
  label: Emerging
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
    immediate_parent: cox-automotive
    name: AutoTrader.com
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: autotradercom
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
name: Cox Automotive
overview: 'Cox Automotive publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 48.5 points, from 51.9 down to 3.4.


  Its highest-rated surfaces are AutoLeadStar, Xtime, AutoTrader.com.'
parent_provider: cox-automotive
permalink: /estates/cox-automotive/
slug: cox-automotive
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cox-automotive/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Cox Automotive
- Automotive
- Vehicle Data
- Vehicle Valuations
- Auctions
- Dealer Software
- Automotive Retail
- VIN Decoding
- Inventory
- Remarketing
- Event
- Webhook
title: Cox Automotive
---
