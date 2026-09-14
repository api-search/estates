---
api_total: 52
category: Estates
description: Splunk is a platform for searching, monitoring, and analyzing machine-generated big data
  via a web-style interface.
estate_rating:
  agent_avg: 10.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 9.7
  agent_ready: 1
  band: emerging
  best: 60.8
  composite_avg: 25.6
  composite_band: thin
  composite_raw: 28.4
  developing: 1
  exemplar: 0
  rating: 19.4
  scored: 6
  spread: 56.7
  strength: 3
  strong: 1
  worst: 4.1
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
    agent_score: 34.6
    api_count: 48
    immediate_parent: splunk
    name: Splunk Observability Cloud
    relationship: product
    score_band: strong
    score_composite: 60.8
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
    immediate_parent: splunk
    name: Splunk SOAR
    relationship: acquisition
    score_band: developing
    score_composite: 42.0
    slug: splunk-soar
    source: declared
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
    score_composite: 31.9
    slug: signalfx
    source: declared
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
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: splunk
    name: Rocana
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: rocana
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: splunk
    name: Streamlio
    relationship: product
    score_band: minimal
    score_composite: 4.1
    slug: streamlio
    source: prose
  label: Minimal
  open: false
member_on_network: 6
member_total: 6
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
members_unrated: []
name: Splunk
overview: 'Splunk publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 56.7 points, from 60.8 down to 4.1.


  Its highest-rated surfaces are Splunk Observability Cloud, Splunk SOAR, SignalFx, Splunk On-Call (VictorOps),
  Rocana.'
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
