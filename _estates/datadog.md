---
api_total: 5
category: Estates
description: Datadog is a monitoring and analytics platform that helps organizations gain insight into
  their infrastructure, applications, and services. It allows users to collect, visualize, and analyze
  real-time data from a variety of sources, including servers, databases, and cloud services. Datadog's
  platform enables companies to track performance metrics, troubleshoot issues, and optimize their systems
  for peak efficiency.
estate_rating:
  agent_avg: 17.7
  agent_band: emerging
  agent_native: 0
  agent_raw: 24.9
  agent_ready: 1
  band: thin
  best: 81.9
  composite_avg: 32.5
  composite_band: thin
  composite_raw: 44.6
  developing: 2
  exemplar: 1
  rating: 26.6
  scored: 5
  spread: 81.9
  strength: 7
  strong: 1
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://imgix.datadoghq.com/img/dd_logo_n_70x75.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 56.0
    api_count: 2
    api_count_basis: published
    immediate_parent: datadog
    name: Datadog APM
    relationship: product
    score_band: exemplar
    score_composite: 81.9
    slug: datadog-apm
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 25.7
    api_count: 1
    api_count_basis: published
    immediate_parent: datadog
    name: Metaplane
    relationship: acquisition
    score_band: strong
    score_composite: 59.2
    slug: metaplane
    source: prose
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    api_count_basis: published
    immediate_parent: datadog
    name: Quickwit
    relationship: acquisition
    score_band: developing
    score_composite: 42.1
    slug: quickwit
    source: prose
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 1
    api_count_basis: published
    immediate_parent: datadog
    name: Adaptive ML
    relationship: product
    score_band: developing
    score_composite: 39.6
    slug: adaptive-ml
    source: parent-company-property
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: datadog
    name: Sqreen
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: sqreen
    source: parent-company-property
  label: Minimal
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
name: Datadog
overview: 'Datadog publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 81.9 points, from 81.9 down to 0.0.


  Its highest-rated surfaces are Datadog APM, Metaplane, Quickwit, Adaptive ML, Sqreen.'
parent_provider: datadog
permalink: /estates/datadog/
slug: datadog
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Visualization
- Datadog
- Analytics
- Dashboards
- Monitoring
- Platform
- T1
title: Datadog
---
