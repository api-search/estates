---
api_total: 19
category: Estates
description: Collection of APIs for Microsoft Power Platform services including Power Apps, Power Automate,
  Power BI, Copilot Studio, Power Pages, and Dataverse.
estate_rating:
  agent_avg: 18.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 27.7
  agent_ready: 3
  band: thin
  best: 65.9
  composite_avg: 33.6
  composite_band: thin
  composite_raw: 47.6
  developing: 1
  exemplar: 0
  rating: 27.7
  scored: 5
  spread: 31.8
  strength: 5
  strong: 2
  worst: 34.1
estate_root: microsoft
estate_root_name: Microsoft
image: https://powerplatform.microsoft.com/images/power-platform-logo.png
is_subfamily: true
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 33.8
    api_count: 1
    api_count_basis: published
    immediate_parent: power-platform
    name: Power BI
    relationship: product
    score_band: strong
    score_composite: 65.9
    slug: power-bi
    source: declared
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 33.7
    api_count: 1
    api_count_basis: published
    immediate_parent: power-platform
    name: Microsoft Power Apps
    relationship: product
    score_band: strong
    score_composite: 54.3
    slug: microsoft-power-apps
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 32.8
    api_count: 10
    api_count_basis: split
    immediate_parent: power-platform
    name: Microsoft Power Automate
    relationship: product
    score_band: developing
    score_composite: 49.3
    slug: microsoft-power-automate
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 17.9
    api_count: 4
    api_count_basis: split
    immediate_parent: power-platform
    name: Microsoft Power Virtual Agents
    relationship: product
    score_band: thin
    score_composite: 34.4
    slug: microsoft-power-virtual-agents
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 20.4
    api_count: 3
    api_count_basis: split
    immediate_parent: power-platform
    name: Microsoft Power Pages
    relationship: product
    score_band: thin
    score_composite: 34.1
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
  on the APIs.io network, of which 5 carry a rating. The rated members span 31.8 points, from 65.9 down
  to 34.1.


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
