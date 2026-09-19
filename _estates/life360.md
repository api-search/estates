---
api_total: 2
category: Estates
description: Life360 is a family safety platform built around a location-sharing mobile app for iOS and
  Android, offering real-time member location, Place Alerts, location history, driving safety scores and
  trip history, crash detection, SOS alerts and emergency dispatch, plus digital safety features such
  as identity theft protection and dark web monitoring. Its hardware line, following the acquisitions
  of Tile and Jiobit, spans Tile Mate, Pro, Slim and Sticker Bluetooth item trackers and a cellular GPS
  pet tracker, sold direct and through Amazon, Best Buy, Target and Walmart. The service is sold as Free,
  Silver, Gold and Platinum membership tiers. Life360 publishes no public developer API, no OpenAPI, no
  SDKs and no developer portal — its only machine-readable surface is an agent-facing one (llms.txt, an
  ai-plugin manifest whose advertised OpenAPI does not resolve, and Content-Signal directives in robots.txt).
  This profile is maintained in the API Evangelist network for company discovery and monitoring.
estate_rating:
  agent_avg: 8.1
  agent_band: minimal
  agent_native: 0
  agent_raw: 3.1
  agent_ready: 0
  band: emerging
  best: 40.9
  composite_avg: 22.0
  composite_band: emerging
  composite_raw: 21.3
  developing: 1
  exemplar: 0
  rating: 16.4
  scored: 3
  spread: 30.3
  strength: 1
  strong: 0
  worst: 10.6
estate_root: null
estate_root_name: null
image: https://www.life360.com/svgs/life360-logo-dark.svg
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 9.2
    api_count: 2
    immediate_parent: life360
    name: Nativo
    relationship: product
    score_band: developing
    score_composite: 40.9
    slug: nativo
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
    immediate_parent: life360
    name: Tile (thetileapp)
    relationship: product
    score_band: emerging
    score_composite: 12.3
    slug: thetileapp
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
    immediate_parent: life360
    name: Jiobit
    relationship: product
    score_band: minimal
    score_composite: 10.6
    slug: jiobit
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
name: Life360
overview: 'Life360 publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 30.3 points, from 40.9 down to 10.6.


  Its highest-rated surfaces are Nativo, Tile (thetileapp), Jiobit.'
parent_provider: life360
permalink: /estates/life360/
slug: life360
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/life360/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Company
- Consumer
- Family Safety
- Location
- GPS Tracking
- Bluetooth Trackers
- Mobile App
- Driving Safety
- Wearables
- Subscription
title: Life360
---
