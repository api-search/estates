---
api_total: 53
category: Estates
description: Splunk is a platform for searching, monitoring, and analyzing machine-generated big data
  via a web-style interface.
estate_rating:
  agent_avg: 11.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 14.5
  agent_ready: 1
  band: emerging
  best: 60.6
  composite_avg: 29.8
  composite_band: thin
  composite_raw: 40.4
  developing: 1
  exemplar: 0
  rating: 22.6
  scored: 4
  spread: 33.8
  strength: 3
  strong: 1
  worst: 26.8
image: https://www.splunk.com/content/dam/splunk2/images/icons/favicons/favicon.ico
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 34.6
    api_count: 49
    immediate_parent: splunk
    name: Splunk Observability Cloud
    relationship: product
    score_band: strong
    score_composite: 60.6
    slug: splunk-observability
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
    immediate_parent: splunk
    name: Splunk SOAR
    relationship: acquisition
    score_band: developing
    score_composite: 41.3
    slug: splunk-soar
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id003
    acquired: 2019
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: splunk
    name: SignalFx
    relationship: acquisition
    score_band: thin
    score_composite: 33.0
    slug: signalfx
  - &id004
    acquired: 2018
    agent_band: agent-aware
    agent_score: 12.9
    api_count: 2
    immediate_parent: splunk
    name: Splunk On-Call (VictorOps)
    relationship: acquisition
    score_band: thin
    score_composite: 26.8
    slug: victorops
  label: Thin
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Splunk
overview: 'Splunk publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 33.8 points, from 60.6 down to 26.8.


  Its highest-rated surfaces are Splunk Observability Cloud, Splunk SOAR, SignalFx, Splunk On-Call (VictorOps).'
parent_provider: splunk
permalink: /estates/splunk/
slug: splunk
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/apis.yml
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
