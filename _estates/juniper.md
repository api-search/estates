---
api_total: 3
category: Estates
description: Juniper Networks (an HPE company since 2025) builds AI-native networking, routing, switching
  and security for service providers, enterprises and public-sector organizations. Its programmable surface
  spans the Mist cloud API (1,059 REST operations), Apstra data-center automation, Junos device automation
  over NETCONF/YANG, Junos Telemetry Interface gRPC streaming, and three first-party MCP servers.
estate_rating:
  agent_avg: 12.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 13.8
  agent_ready: 1
  band: emerging
  best: 60.2
  composite_avg: 23.1
  composite_band: emerging
  composite_raw: 25.3
  developing: 1
  exemplar: 0
  rating: 18.8
  scored: 6
  spread: 60.2
  strength: 3
  strong: 1
  worst: 0.0
estate_root: hpe
estate_root_name: Hewlett Packard Enterprise
image: https://www.juniper.net/content/dam/www/assets/images/juniper-networks-logo.png
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
    agent_score: 29.3
    api_count: 1
    immediate_parent: juniper
    name: Mist
    relationship: product
    score_band: strong
    score_composite: 60.2
    slug: mist
    source: parent-company-property
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 28.4
    api_count: 1
    immediate_parent: juniper
    name: Juniper Mist AI
    relationship: acquisition
    score_band: developing
    score_composite: 45.7
    slug: mist-ai
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id003
    acquired: 2020
    agent_band: agent-aware
    agent_score: 25.2
    api_count: 1
    immediate_parent: juniper
    name: 128 Technology
    relationship: acquisition
    score_band: thin
    score_composite: 37.1
    slug: 128-technology
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: juniper
    name: BTI Systems (Juniper)
    relationship: product
    score_band: minimal
    score_composite: 8.6
    slug: bti-systems-juniper
    source: declared
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: juniper
    name: Argon Networks
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: argon
    source: parent-company-property
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: juniper
    name: Peribit
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: peribit
    source: parent-company-property
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
name: Juniper Networks
overview: 'Juniper Networks publishes its API surface across 6 provider profiles indexed on the APIs.io
  network, of which 6 carry a rating. The rated members span 60.2 points, from 60.2 down to 0.0.


  Its highest-rated surfaces are Mist, Juniper Mist AI, 128 Technology, BTI Systems (Juniper), Argon Networks.'
parent_provider: juniper
permalink: /estates/juniper/
slug: juniper
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/apis.yml
subfamilies: []
tags:
- Artificial Intelligence
- Automation
- Cloud
- Enterprise
- Networking
- SDN
- Security
- Fortune 1000
title: Juniper Networks
---
