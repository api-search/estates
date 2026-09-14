---
api_total: 2
category: Estates
description: Walmart is a multinational retail corporation that operates a chain of hypermarkets, discount
  department stores, and grocery stores. The company is known for offering a wide range of products at
  competitive prices, attracting customers from all walks of life. Walmart also provides various convenience
  services, such as pharmacy, optical, and financial services, making it a one-stop shop for many consumers.
  The Walmart Marketplace APIs enable third-party sellers to list and sell products, manage orders, inventory,
  pricing, fulfillment, and reporting on Walmart.com.
estate_rating:
  agent_avg: 10.6
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.3
  agent_ready: 0
  band: emerging
  best: 34.4
  composite_avg: 21.6
  composite_band: emerging
  composite_raw: 20.9
  developing: 0
  exemplar: 0
  rating: 17.2
  scored: 4
  spread: 29.4
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/walmart.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: walmart
    name: Flipkart
    relationship: product
    score_band: thin
    score_composite: 34.4
    slug: flipkart
    source: prose
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    immediate_parent: walmart
    name: PhonePe
    relationship: product
    score_band: thin
    score_composite: 32.5
    slug: phonepe
    source: prose
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: walmart
    name: Eloquii
    relationship: product
    score_band: emerging
    score_composite: 11.8
    slug: eloquii
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: flipkart
    name: Myntra
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: myntra
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: walmart
    name: Kosmix
    relationship: product
    score_band: null
    score_composite: null
    slug: kosmix
    source: prose
  label: Unrated
  open: false
member_on_network: 5
member_total: 5
members:
- *id001
- *id002
- *id003
- *id004
- *id005
members_unrated: []
name: Walmart
overview: 'Walmart publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 29.4 points, from 34.4 down to 5.0.


  Its highest-rated surfaces are Flipkart, PhonePe, Eloquii, Myntra, Kosmix.'
parent_provider: walmart
permalink: /estates/walmart/
slug: walmart
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/walmart/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Myntra
    score_band: minimal
    score_composite: 5.0
    slug: myntra
  name: Flipkart
  on_network: true
  permalink: /estates/flipkart/
  slug: flipkart
subfamily_page_count: 0
tags:
- Commerce
- Retail
- Fortune 100
- Marketplace
- E-Commerce
- Order
- Inventory
- Fulfillment
- Supply Chain
- Seller APIs
- Webhook
- MCP
title: Walmart
---
