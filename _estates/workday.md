---
api_total: 15
category: Estates
description: Collection of Workday REST and SOAP APIs for human capital management, financial management,
  enterprise planning, analytics, and platform extensibility.
estate_rating:
  agent_avg: 16.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 20.1
  agent_ready: 1
  band: emerging
  best: 48.4
  composite_avg: 28.9
  composite_band: thin
  composite_raw: 34.0
  developing: 3
  exemplar: 0
  rating: 23.8
  scored: 6
  spread: 43.4
  strength: 3
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/workday.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 3
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 1
    immediate_parent: workday
    name: Flowise
    relationship: product
    score_band: developing
    score_composite: 48.4
    slug: flowise
    source: parent-company-property
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 31.5
    api_count: 11
    immediate_parent: workday
    name: Scout RFP (Workday Strategic Sourcing)
    relationship: product
    score_band: developing
    score_composite: 43.7
    slug: scoutrfp
    source: parent-company-property
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 1
    immediate_parent: workday
    name: Sana
    relationship: product
    score_band: developing
    score_composite: 43.3
    slug: sana
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 23.6
    api_count: 1
    immediate_parent: workday
    name: Peakon
    relationship: product
    score_band: thin
    score_composite: 32.1
    slug: peakon
    source: parent-company-property
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: workday
    name: Evisort
    relationship: product
    score_band: thin
    score_composite: 31.5
    slug: evisort
    source: parent-company-property
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: workday
    name: VNDLY
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: vndly
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
name: Workday
overview: 'Workday publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 43.4 points, from 48.4 down to 5.0.


  Its highest-rated surfaces are Flowise, Scout RFP (Workday Strategic Sourcing), Sana, Peakon, Evisort.'
parent_provider: workday
permalink: /estates/workday/
slug: workday
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Cloud Computing
- Enterprise Software
- Financial Management
- HCM
- Software-as-a-Service
title: Workday
---
