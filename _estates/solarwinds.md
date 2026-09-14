---
api_total: 2
category: Estates
description: A collection of APIs provided by SolarWinds for IT infrastructure management, monitoring,
  and observability.
estate_rating:
  agent_avg: 11.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 12.1
  agent_ready: 1
  band: emerging
  best: 52.9
  composite_avg: 23.4
  composite_band: emerging
  composite_raw: 25.5
  developing: 1
  exemplar: 0
  rating: 18.6
  scored: 3
  spread: 47.9
  strength: 1
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://www.solarwinds.com/sites/all/themes/solarwinds_theme/logo.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 30.8
    api_count: 1
    immediate_parent: solarwinds
    name: VividCortex
    relationship: product
    score_band: developing
    score_composite: 52.9
    slug: vividcortex
    source: prose
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 5.4
    api_count: 1
    immediate_parent: solarwinds
    name: Librato
    relationship: product
    score_band: emerging
    score_composite: 18.5
    slug: librato
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
    immediate_parent: solarwinds
    name: LogicNow
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: logicnow
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
name: SolarWinds
overview: 'SolarWinds publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 47.9 points, from 52.9 down to 5.0.


  Its highest-rated surfaces are VividCortex, Librato, LogicNow.'
parent_provider: solarwinds
permalink: /estates/solarwinds/
slug: solarwinds
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Application Monitoring
- Database Monitoring
- Infrastructure
- IP Address Management
- IT Management
- ITSM
- Log Management
- Network Monitoring
- Observability
title: SolarWinds
---
