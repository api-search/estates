---
api_total: 16
category: Estates
description: ServiceNow provides cloud-based platform services that automate enterprise IT operations.
estate_rating:
  agent_avg: 12.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 13.1
  agent_ready: 2
  band: emerging
  best: 55.7
  composite_avg: 20.0
  composite_band: emerging
  composite_raw: 19.7
  developing: 0
  exemplar: 0
  rating: 16.8
  scored: 7
  spread: 53.2
  strength: 2
  strong: 1
  worst: 2.5
estate_root: null
estate_root_name: null
image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: 2025
    agent_band: agent-ready
    agent_score: 35.8
    api_count: 9
    immediate_parent: servicenow
    name: Moveworks
    relationship: acquisition
    score_band: strong
    score_composite: 55.7
    slug: moveworks
    source: declared
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 24.3
    api_count: 2
    immediate_parent: servicenow
    name: Cuein
    relationship: acquisition
    score_band: thin
    score_composite: 34.1
    slug: cuein
    source: prose
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 29.0
    api_count: 4
    immediate_parent: servicenow
    name: Logik.io
    relationship: product
    score_band: thin
    score_composite: 33.4
    slug: logikio
    source: parent-company-property
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 4
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: servicenow
    name: ServiceNow Flow Designer
    relationship: product
    score_band: minimal
    score_composite: 7.0
    slug: servicenow-flow-designer
    source: declared
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: servicenow
    name: Element AI
    relationship: acquisition
    score_band: minimal
    score_composite: 2.5
    slug: element-ai
    source: declared
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: servicenow
    name: SkyGiraffe
    relationship: acquisition
    score_band: minimal
    score_composite: 2.5
    slug: skygiraffe
    source: prose
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: servicenow
    name: VendorHawk
    relationship: acquisition
    score_band: minimal
    score_composite: 2.5
    slug: vendorhawk
    source: prose
  label: Minimal
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
name: ServiceNow
overview: 'ServiceNow publishes its API surface across 7 provider profiles indexed on the APIs.io network,
  of which 7 carry a rating. The rated members span 53.2 points, from 55.7 down to 2.5.


  Its highest-rated surfaces are Moveworks, Cuein, Logik.io, ServiceNow Flow Designer, Element AI.'
parent_provider: servicenow
permalink: /estates/servicenow/
slug: servicenow
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- ServiceNow
- Automation
- Cloud Services
- Digital Workflows
- Enterprise Platform
- ITSM
- Processes
- T1
- Workflow Automation
- Workflows
- A2A
title: ServiceNow
---
