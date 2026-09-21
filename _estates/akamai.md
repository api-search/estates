---
api_total: 6
category: Estates
description: Akamai is a global content delivery network (CDN), cloud services, and cybersecurity company
  that helps organizations deliver fast, reliable, and secure digital experiences. Akamai's intelligent
  edge platform spans over 4,000 locations in 130+ countries, enabling customers to accelerate content
  delivery, protect against cyberattacks, and run cloud applications at the edge of the internet.
estate_rating:
  agent_avg: 12.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 12.7
  agent_ready: 0
  band: emerging
  best: 38.5
  composite_avg: 22.1
  composite_band: emerging
  composite_raw: 21.4
  developing: 0
  exemplar: 0
  rating: 18.1
  scored: 4
  spread: 33.5
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/akamai.png
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
    agent_score: 27.3
    api_count: 1
    immediate_parent: akamai
    name: Akamai API Security
    relationship: product
    score_band: thin
    score_composite: 38.5
    slug: akamai-api-security
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 21.0
    api_count: 1
    immediate_parent: akamai
    name: Styra
    relationship: product
    score_band: thin
    score_composite: 29.4
    slug: styra
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
    agent_score: 2.5
    api_count: 4
    immediate_parent: akamai
    name: Noname Security
    relationship: product
    score_band: emerging
    score_composite: 12.8
    slug: noname-security
    source: parent-company-property
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
    immediate_parent: akamai
    name: Guardicore
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: guardicore
    source: parent-company-property
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
name: Akamai
overview: 'Akamai publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 33.5 points, from 38.5 down to 5.0.


  Its highest-rated surfaces are Akamai API Security, Styra, Noname Security, Guardicore.'
parent_provider: akamai
permalink: /estates/akamai/
slug: akamai
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/akamai/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- CDN
- Cloud
- Edge Computing
- Networks
- Platform
- Security
title: Akamai
---
