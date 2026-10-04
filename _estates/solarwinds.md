---
api_total: 2
category: Estates
description: A collection of APIs provided by SolarWinds for IT infrastructure management, monitoring,
  and observability.
estate_rating:
  agent_avg: 10.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 9.5
  agent_ready: 1
  band: emerging
  best: 53.6
  composite_avg: 19.5
  composite_band: emerging
  composite_raw: 17.9
  developing: 1
  exemplar: 0
  rating: 15.8
  scored: 3
  spread: 53.6
  strength: 1
  strong: 0
  worst: 0.0
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
    agent_score: 28.6
    api_count: 1
    immediate_parent: solarwinds
    name: VividCortex
    relationship: acquisition
    score_band: developing
    score_composite: 53.6
    slug: vividcortex
    source: prose
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: solarwinds
    name: Librato
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: librato
    source: parent-company-property
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: solarwinds
    name: LogicNow
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: logicnow
    source: parent-company-property
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
  of which 3 carry a rating. The rated members span 53.6 points, from 53.6 down to 0.0.


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
- Monitoring
title: SolarWinds
---
