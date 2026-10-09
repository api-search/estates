---
api_total: 51
category: Estates
description: Splunk is a data platform that enables organizations to search, monitor, analyze, and visualize
  massive streams of machine-generated data across security, observability, and AI use cases. It offers
  solutions for security information and event management (SIEM), infrastructure monitoring, application
  performance monitoring, and AI-driven analytics, helping enterprises turn data into actionable insights
  and operational intelligence.
estate_rating:
  agent_avg: 10.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.1
  agent_ready: 1
  band: emerging
  best: 66.2
  composite_avg: 25.6
  composite_band: thin
  composite_raw: 32.2
  developing: 1
  exemplar: 0
  rating: 19.5
  scored: 4
  spread: 64.6
  strength: 3
  strong: 1
  worst: 1.6
estate_root: cisco
estate_root_name: Cisco
image: https://www.splunk.com/content/dam/splunk2/images/icons/favicons/favicon.ico
is_subfamily: true
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 32.4
    api_count: 48
    api_count_basis: published
    immediate_parent: splunk
    name: Splunk Observability Cloud
    relationship: product
    score_band: strong
    score_composite: 66.2
    slug: splunk-observability
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id002
    acquired: 2018
    agent_band: agent-aware
    agent_score: 7.9
    api_count: 1
    api_count_basis: split
    immediate_parent: splunk
    name: Splunk SOAR
    relationship: acquisition
    score_band: developing
    score_composite: 44.7
    slug: splunk-soar
    source: declared
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: 2018
    agent_band: human-only
    agent_score: 0.0
    api_count: 2
    api_count_basis: split
    immediate_parent: splunk
    name: Splunk On-Call (VictorOps)
    relationship: acquisition
    score_band: emerging
    score_composite: 16.4
    slug: victorops
    source: declared
  label: Emerging
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
    api_count_basis: split
    immediate_parent: splunk
    name: Streamlio
    relationship: acquisition
    score_band: minimal
    score_composite: 1.6
    slug: streamlio
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: splunk
    name: Rocana
    relationship: product
    score_band: null
    score_composite: null
    slug: rocana
    source: parent-company-property
  label: Unrated
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
name: Splunk
overview: 'Splunk publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 64.6 points, from 66.2 down to 1.6.


  Its highest-rated surfaces are Splunk Observability Cloud, Splunk SOAR, Splunk On-Call (VictorOps),
  Streamlio, Rocana.'
parent_provider: splunk
permalink: /estates/splunk/
slug: splunk
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/apis.yml
subfamilies: []
tags:
- Analytics
- Data Analysis
- Logging
- Machine Data
- Monitoring
- Observability
- Platform
- Security
- SIEM
title: Splunk
---
