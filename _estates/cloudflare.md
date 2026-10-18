---
api_total: 7
category: Estates
description: Cloudflare is a global network designed to make everything you connect to the Internet secure,
  private, fast, and reliable.
estate_rating:
  agent_avg: 12.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 15.0
  agent_ready: 0
  band: emerging
  best: 35.9
  composite_avg: 23.0
  composite_band: emerging
  composite_raw: 27.2
  developing: 0
  exemplar: 0
  rating: 18.7
  scored: 4
  spread: 24.6
  strength: 0
  strong: 0
  worst: 11.3
estate_root: null
estate_root_name: null
image: https://www.cloudflare.com/preview.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 15.9
    api_count: 4
    api_count_basis: split
    immediate_parent: cloudflare
    name: PartyKit
    relationship: product
    score_band: thin
    score_composite: 35.9
    slug: partykit
    source: prose
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 26.2
    api_count: 2
    api_count_basis: published
    immediate_parent: cloudflare
    name: Cloudflare R2
    relationship: product
    score_band: thin
    score_composite: 35.0
    slug: cloudflare-r2
    source: declared
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 17.9
    api_count: 1
    api_count_basis: published
    immediate_parent: cloudflare
    name: Dyte
    relationship: product
    score_band: thin
    score_composite: 26.7
    slug: dyte
    source: parent-company-property
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: cloudflare
    name: VoidZero
    relationship: acquisition
    score_band: emerging
    score_composite: 11.3
    slug: voidzero
    source: prose
  label: Emerging
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Cloudflare
overview: 'Cloudflare publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 24.6 points, from 35.9 down to 11.3.


  Its highest-rated surfaces are PartyKit, Cloudflare R2, Dyte, VoidZero.'
parent_provider: cloudflare
permalink: /estates/cloudflare/
slug: cloudflare
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudflare/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- AI Gateway
- API Gateway
- Artificial Intelligence
- CDN
- Cloud
- Containers
- DDoS Protection
- DNS
- Edge
- Edge Computing
- Object Storage
- Platform
title: Cloudflare
---
