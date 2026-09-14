---
api_total: 0
category: Estates
description: A connected fitness company offering stationary bikes, treadmills, rowers, and a digital
  platform for live and on-demand fitness classes. Peloton pioneered the premium at-home fitness category,
  blending hardware, software, and instructor-led content into an interactive workout experience available
  across Peloton equipment and a standalone Peloton App on iOS, Android, web, and connected TV. Peloton
  does not publish a public developer API, partner portal, or third-party integration program; all API
  surfaces are internal and only reachable through the consumer apps. Reverse-engineered community libraries
  exist on GitHub but are unsupported by Peloton.
estate_rating:
  agent_avg: 7.8
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 10.5
  composite_avg: 17.8
  composite_band: emerging
  composite_raw: 7.0
  developing: 0
  exemplar: 0
  rating: 13.8
  scored: 2
  spread: 7.0
  strength: 0
  strong: 0
  worst: 3.5
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/peloton.png
is_subfamily: false
layout: estate
member_bands:
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: peloton
    name: Breathwrk
    relationship: product
    score_band: minimal
    score_composite: 10.5
    slug: breathwrk
    source: prose
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: peloton
    name: Peloton Interactive
    relationship: product
    score_band: minimal
    score_composite: 3.5
    slug: peloton-interactive
    source: declared
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: peloton-interactive
    name: Atlas Wearables
    relationship: product
    score_band: null
    score_composite: null
    slug: atlas-wearables
    source: prose
  label: Unrated
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Peloton
overview: 'Peloton publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 7.0 points, from 10.5 down to 3.5.


  Its highest-rated surfaces are Breathwrk, Peloton Interactive, Atlas Wearables.'
parent_provider: peloton
permalink: /estates/peloton/
slug: peloton
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/peloton/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Atlas Wearables
    score_band: null
    score_composite: null
    slug: atlas-wearables
  name: Peloton Interactive
  on_network: true
  permalink: /estates/peloton-interactive/
  slug: peloton-interactive
subfamily_page_count: 0
tags:
- Fitness
- Wellness
- Connected Fitness
- Subscription
- Hardware
- Streaming
- Consumer
title: Peloton
---
