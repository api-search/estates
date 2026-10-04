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
  agent_avg: 8.6
  agent_band: minimal
  agent_native: 0
  agent_raw: 6.9
  agent_ready: 0
  band: emerging
  best: 35.6
  composite_avg: 16.6
  composite_band: emerging
  composite_raw: 13.5
  developing: 0
  exemplar: 0
  rating: 13.4
  scored: 6
  spread: 35.6
  strength: 0
  strong: 0
  worst: 0.0
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
    relationship: acquisition
    score_band: thin
    score_composite: 35.6
    slug: flipkart
    source: prose
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    immediate_parent: walmart
    name: PhonePe
    relationship: acquisition
    score_band: thin
    score_composite: 30.3
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
    score_composite: 11.4
    slug: eloquii
    source: parent-company-property
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: flipkart
    name: Myntra
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: myntra
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: walmart
    name: Jet (Walmart)
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: jet-walmart
    source: parent-company-property
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: walmart
    name: Kosmix
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: kosmix
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 6
member_total: 6
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
members_unrated: []
name: Walmart
overview: 'Walmart publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 35.6 points, from 35.6 down to 0.0.


  Its highest-rated surfaces are Flipkart, PhonePe, Eloquii, Myntra, Jet (Walmart).'
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
    score_composite: 3.4
    slug: myntra
  name: Flipkart
  on_network: true
  permalink: /estates/flipkart/
  slug: flipkart
subfamily_page_count: 0
tags:
- Walmart
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
title: Walmart
---
