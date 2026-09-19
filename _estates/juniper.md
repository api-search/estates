---
api_total: 2
category: Estates
description: Juniper Networks provides high-performance networking and cybersecurity solutions for service
  providers, enterprises, and public sector organizations.
estate_rating:
  agent_avg: 16.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 28.4
  agent_ready: 1
  band: emerging
  best: 50.6
  composite_avg: 28.7
  composite_band: thin
  composite_raw: 44.5
  developing: 1
  exemplar: 0
  rating: 23.6
  scored: 2
  spread: 12.2
  strength: 1
  strong: 0
  worst: 38.4
estate_root: null
estate_root_name: null
image: https://www.juniper.net/content/dam/www/assets/images/juniper-networks-logo.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 31.5
    api_count: 1
    immediate_parent: juniper
    name: Mist
    relationship: product
    score_band: developing
    score_composite: 50.6
    slug: mist
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: 2020
    agent_band: agent-aware
    agent_score: 25.2
    api_count: 1
    immediate_parent: juniper
    name: 128 Technology
    relationship: acquisition
    score_band: thin
    score_composite: 38.4
    slug: 128-technology
    source: declared
  label: Thin
  open: false
- band: unrated
  blurb: Not yet scored
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: juniper
    name: Argon Networks
    relationship: product
    score_band: null
    score_composite: null
    slug: argon
    source: prose
  - &id004
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: juniper
    name: Peribit
    relationship: product
    score_band: null
    score_composite: null
    slug: peribit
    source: prose
  label: Unrated
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Juniper Networks
overview: 'Juniper Networks publishes its API surface across 4 provider profiles indexed on the APIs.io
  network, of which 4 carry a rating. The rated members span 12.2 points, from 50.6 down to 38.4.


  Its highest-rated surfaces are Mist, 128 Technology, Argon Networks, Peribit.'
parent_provider: juniper
permalink: /estates/juniper/
slug: juniper
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
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
