---
api_total: 19
category: Estates
description: Collection of APIs for Microsoft Power Platform services including Power Apps, Power Automate,
  Power BI, Copilot Studio, Power Pages, and Dataverse.
estate_rating:
  agent_avg: 20.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 29.1
  agent_ready: 3
  band: thin
  best: 72.7
  composite_avg: 37.2
  composite_band: thin
  composite_raw: 52.0
  developing: 0
  exemplar: 1
  rating: 30.4
  scored: 5
  spread: 37.1
  strength: 7
  strong: 2
  worst: 35.6
estate_root: microsoft
estate_root_name: Microsoft
image: https://powerplatform.microsoft.com/images/power-platform-logo.png
is_subfamily: true
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 34.2
    api_count: 1
    immediate_parent: power-platform
    name: Power BI
    relationship: product
    score_band: exemplar
    score_composite: 72.7
    slug: power-bi
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 34.4
    api_count: 1
    immediate_parent: power-platform
    name: Microsoft Power Apps
    relationship: product
    score_band: strong
    score_composite: 60.8
    slug: microsoft-power-apps
    source: declared
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 34.6
    api_count: 10
    immediate_parent: power-platform
    name: Microsoft Power Automate
    relationship: product
    score_band: strong
    score_composite: 54.8
    slug: microsoft-power-automate
    source: declared
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 4
    immediate_parent: power-platform
    name: Microsoft Power Virtual Agents
    relationship: product
    score_band: thin
    score_composite: 36.2
    slug: microsoft-power-virtual-agents
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 3
    immediate_parent: power-platform
    name: Microsoft Power Pages
    relationship: product
    score_band: thin
    score_composite: 35.6
    slug: microsoft-power-pages
    source: declared
  label: Thin
  open: false
member_on_network: 5
member_total: 5
members:
- *id001
- *id002
- *id003
- *id004
- *id005
members_unrated: []
name: Microsoft Power Platform APIs
overview: 'Microsoft Power Platform APIs publishes its API surface across 5 provider profiles indexed
  on the APIs.io network, of which 5 carry a rating. The rated members span 37.1 points, from 72.7 down
  to 35.6.


  Its highest-rated surfaces are Power BI, Microsoft Power Apps, Microsoft Power Automate, Microsoft Power
  Virtual Agents, Microsoft Power Pages.'
parent_provider: power-platform
permalink: /estates/power-platform/
slug: power-platform
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/power-platform/refs/heads/main/apis.yml
subfamilies: []
tags:
- Business Applications
- Copilot Studio
- Dataverse
- Low-Code
- Microsoft
- No-Code
- Power Pages
- Power Platform
title: Microsoft Power Platform APIs
---
