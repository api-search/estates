---
api_total: 0
category: Estates
description: DoorDash is an on-demand local commerce platform whose developer program exposes its logistics
  and marketplace network through thirteen publicly documented REST APIs. Drive, Drive (classic) and Parcel
  let businesses request deliveries fulfilled by DoorDash's Dasher fleet, with Refunds, Redelivery and
  Dasher Feedback attached to that surface. Marketplace, Marketplace (legacy) and Item Management let
  merchants and retailers receive orders and synchronize menus, catalogs, inventory and promotions, while
  Storefront powers white-label online ordering, Reporting delivers financial and operational data exchange,
  and the Ads API sells sponsored placement on the marketplace. Every API authenticates with a short-lived
  HS256 JSON Web Token the caller signs itself, and DoorDash serves each OpenAPI definition as plain YAML
  from developer.doordash.com.
estate_rating:
  agent_avg: 6.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 7.3
  composite_avg: 16.2
  composite_band: emerging
  composite_raw: 5.8
  developing: 0
  exemplar: 0
  rating: 12.5
  scored: 3
  spread: 2.3
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/doordash.png
is_subfamily: false
layout: estate
member_bands:
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: doordash
    name: Bbot
    relationship: product
    score_band: minimal
    score_composite: 7.3
    slug: bbot
    source: prose
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: doordash
    name: Caviar
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: caviar
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: doordash
    name: chowbotics
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: chowbotics
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
name: Doordash
overview: 'Doordash publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 2.3 points, from 7.3 down to 5.0.


  Its highest-rated surfaces are Bbot, Caviar, chowbotics.'
parent_provider: doordash
permalink: /estates/doordash/
slug: doordash
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Delivery
- Logistics
- Last Mile
- On-Demand
- Food Delivery
- Local Commerce
- Marketplace
- Restaurant
- Grocery
- Retail
- Fulfillment
- Webhook
title: Doordash
---
