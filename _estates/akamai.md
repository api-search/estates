---
api_total: 6
category: Estates
description: Akamai is a global content delivery network (CDN), cloud services, and cybersecurity company
  that helps organizations deliver fast, reliable, and secure digital experiences. Akamai's intelligent
  edge platform spans over 4,000 locations in 130+ countries, enabling customers to accelerate content
  delivery, protect against cyberattacks, and run cloud applications at the edge of the internet.
estate_rating:
  agent_avg: 8.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 7.8
  agent_ready: 0
  band: emerging
  best: 36.1
  composite_avg: 16.2
  composite_band: emerging
  composite_raw: 13.5
  developing: 0
  exemplar: 0
  rating: 13.3
  scored: 6
  spread: 36.1
  strength: 0
  strong: 0
  worst: 0.0
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
    api_count_basis: published
    immediate_parent: akamai
    name: Akamai API Security
    relationship: product
    score_band: thin
    score_composite: 36.1
    slug: akamai-api-security
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 18.9
    api_count: 1
    api_count_basis: published
    immediate_parent: akamai
    name: Styra
    relationship: acquisition
    score_band: thin
    score_composite: 29.0
    slug: styra
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 4
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.6
    api_count: 4
    api_count_basis: split
    immediate_parent: akamai
    name: Noname Security
    relationship: product
    score_band: minimal
    score_composite: 9.6
    slug: noname-security
    source: parent-company-property
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: akamai
    name: Guardicore
    relationship: product
    score_band: minimal
    score_composite: 3.4
    slug: guardicore
    source: parent-company-property
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: akamai
    name: Soha Systems
    relationship: acquisition
    score_band: minimal
    score_composite: 2.6
    slug: soha-systems
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: akamai
    name: Instart Logic
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: instart-logic
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id007
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: akamai
    name: Soasta
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: soasta
    source: prose
  label: Unrated
  open: false
member_on_network: 7
member_total: 7
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
members_unrated: []
name: Akamai
overview: 'Akamai publishes its API surface across 7 provider profiles indexed on the APIs.io network,
  of which 7 carry a rating. The rated members span 36.1 points, from 36.1 down to 0.0.


  Its highest-rated surfaces are Akamai API Security, Styra, Noname Security, Guardicore, Soha Systems.'
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
