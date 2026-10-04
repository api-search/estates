---
api_total: 73
category: Estates
description: Collection of Workday REST and SOAP APIs for human capital management, financial management,
  enterprise planning, analytics, and platform extensibility.
estate_rating:
  agent_avg: 17.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 20.8
  agent_ready: 1
  band: thin
  best: 48.1
  composite_avg: 30.9
  composite_band: thin
  composite_raw: 36.8
  developing: 6
  exemplar: 0
  rating: 25.4
  scored: 9
  spread: 45.2
  strength: 6
  strong: 0
  worst: 2.9
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/workday.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 6
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 2
    immediate_parent: workday
    name: Workday Studio
    relationship: product
    score_band: developing
    score_composite: 48.1
    slug: workday-studio
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 54
    immediate_parent: workday
    name: Workday Integration
    relationship: product
    score_band: developing
    score_composite: 47.2
    slug: workday-integration
    source: declared
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 1
    immediate_parent: workday
    name: Flowise
    relationship: product
    score_band: developing
    score_composite: 45.8
    slug: flowise
    source: parent-company-property
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 2
    immediate_parent: workday
    name: Workday Finance
    relationship: product
    score_band: developing
    score_composite: 45.6
    slug: workday-finance
    source: declared
  - &id005
    acquired: null
    agent_band: agent-ready
    agent_score: 31.5
    api_count: 11
    immediate_parent: workday
    name: Scout RFP (Workday Strategic Sourcing)
    relationship: product
    score_band: developing
    score_composite: 43.3
    slug: scoutrfp
    source: declared
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 1
    immediate_parent: workday
    name: Sana
    relationship: product
    score_band: developing
    score_composite: 39.3
    slug: sana
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id007
    acquired: null
    agent_band: agent-aware
    agent_score: 21.4
    api_count: 1
    immediate_parent: workday
    name: Peakon
    relationship: product
    score_band: thin
    score_composite: 30.4
    slug: peakon
    source: parent-company-property
  - &id008
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: workday
    name: Evisort
    relationship: product
    score_band: thin
    score_composite: 28.6
    slug: evisort
    source: parent-company-property
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id009
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: workday
    name: VNDLY
    relationship: product
    score_band: minimal
    score_composite: 2.9
    slug: vndly
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 9
member_total: 9
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
- *id009
members_unrated: []
name: Workday
overview: 'Workday publishes its API surface across 9 provider profiles indexed on the APIs.io network,
  of which 9 carry a rating. The rated members span 45.2 points, from 48.1 down to 2.9.


  Its highest-rated surfaces are Workday Studio, Workday Integration, Flowise, Workday Finance, Scout
  RFP (Workday Strategic Sourcing).'
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
