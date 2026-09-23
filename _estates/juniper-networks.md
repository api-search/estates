---
api_total: 2
category: Estates
description: ''
estate_rating:
  agent_avg: 14.8
  agent_band: emerging
  agent_native: 0
  agent_raw: 22.8
  agent_ready: 1
  band: emerging
  best: 60.8
  composite_avg: 27.5
  composite_band: thin
  composite_raw: 39.6
  developing: 0
  exemplar: 0
  rating: 22.4
  scored: 2
  spread: 42.4
  strength: 2
  strong: 1
  worst: 18.4
estate_root: null
estate_root_name: null
image: ''
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 31.5
    api_count: 1
    immediate_parent: juniper-networks
    name: Mist
    relationship: product
    score_band: strong
    score_composite: 60.8
    slug: mist
    source: parent-company-property
  label: Strong
  open: true
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 14.0
    api_count: 1
    immediate_parent: juniper-networks
    name: Aria Networks
    relationship: product
    score_band: emerging
    score_composite: 18.4
    slug: aria-networks
    source: parent-company-property
  label: Emerging
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
    immediate_parent: juniper-networks
    name: Argon Networks
    relationship: product
    score_band: null
    score_composite: null
    slug: argon
    source: parent-company-property
  - &id004
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: juniper-networks
    name: Peribit
    relationship: product
    score_band: null
    score_composite: null
    slug: peribit
    source: parent-company-property
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
name: juniper-networks
overview: 'juniper-networks publishes its API surface across 4 provider profiles indexed on the APIs.io
  network, of which 4 carry a rating. The rated members span 42.4 points, from 60.8 down to 18.4.


  Its highest-rated surfaces are Mist, Aria Networks, Argon Networks, Peribit.'
parent_provider: juniper-networks
permalink: /estates/juniper-networks/
slug: juniper-networks
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags: []
title: juniper-networks
---
