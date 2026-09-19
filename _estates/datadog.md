---
api_total: 4
category: Estates
description: Datadog is a monitoring and analytics platform that helps organizations gain insight into
  their infrastructure, applications, and services. It allows users to collect, visualize, and analyze
  real-time data from a variety of sources, including servers, databases, and cloud services. Datadog's
  platform enables companies to track performance metrics, troubleshoot issues, and optimize their systems
  for peak efficiency.
estate_rating:
  agent_avg: 18.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 27.4
  agent_ready: 1
  band: thin
  best: 79.3
  composite_avg: 32.8
  composite_band: thin
  composite_raw: 45.9
  developing: 1
  exemplar: 1
  rating: 27.0
  scored: 4
  spread: 74.3
  strength: 6
  strong: 1
  worst: 5.0
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
    agent_score: 56.3
    api_count: 2
    immediate_parent: datadog
    name: Datadog APM
    relationship: product
    score_band: exemplar
    score_composite: 79.3
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
    agent_score: 27.9
    api_count: 1
    immediate_parent: datadog
    name: Metaplane
    relationship: product
    score_band: strong
    score_composite: 58.7
    slug: metaplane
    source: prose
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 25.4
    api_count: 1
    immediate_parent: datadog
    name: Adaptive ML
    relationship: product
    score_band: developing
    score_composite: 40.4
    slug: adaptive-ml
    source: prose
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: datadog
    name: Sqreen
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: sqreen
    source: prose
  label: Minimal
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Datadog
overview: 'Datadog publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 74.3 points, from 79.3 down to 5.0.


  Its highest-rated surfaces are Datadog APM, Metaplane, Adaptive ML, Sqreen.'
parent_provider: datadog
permalink: /estates/datadog/
slug: datadog
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Analytics
- Dashboards
- Monitoring
- Platform
- T1
- Visualization
title: Datadog
---
