---
api_total: 5
category: Estates
description: ServiceNow provides cloud-based platform services that automate enterprise IT operations.
estate_rating:
  agent_avg: 11.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.5
  agent_ready: 1
  band: emerging
  best: 34.1
  composite_avg: 20.1
  composite_band: emerging
  composite_raw: 15.9
  developing: 0
  exemplar: 0
  rating: 16.5
  scored: 3
  spread: 29.1
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 29.0
    api_count: 4
    immediate_parent: servicenow
    name: Logik.io
    relationship: product
    score_band: thin
    score_composite: 34.1
    slug: logikio
    source: parent-company-property
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: servicenow
    name: ServiceNow Flow Designer
    relationship: product
    score_band: minimal
    score_composite: 8.6
    slug: servicenow-flow-designer
    source: declared
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: servicenow
    name: Element AI
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: element-ai
    source: declared
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: ServiceNow
overview: 'ServiceNow publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 29.1 points, from 34.1 down to 5.0.


  Its highest-rated surfaces are Logik.io, ServiceNow Flow Designer, Element AI.'
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
- Workflow-Automation
- Workflows
title: ServiceNow
---
