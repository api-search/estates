---
api_total: 1
category: Estates
description: A multinational semiconductor company designing high-performance processors, graphics cards,
  and adaptive computing solutions. Competes in data center, gaming, and embedded markets with its Ryzen,
  EPYC, and Radeon product lines.
estate_rating:
  agent_avg: 9.2
  agent_band: minimal
  agent_native: 0
  agent_raw: 7.0
  agent_ready: 0
  band: emerging
  best: 26.3
  composite_avg: 18.2
  composite_band: emerging
  composite_raw: 14.6
  developing: 0
  exemplar: 0
  rating: 14.6
  scored: 3
  spread: 22.7
  strength: 0
  strong: 0
  worst: 3.6
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/amd.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 0
    api_count_basis: split
    immediate_parent: amd
    name: Xilinx
    relationship: product
    score_band: thin
    score_composite: 26.3
    slug: xilinx
    source: parent-company-property
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: 2022
    agent_band: agent-aware
    agent_score: 5.4
    api_count: 1
    api_count_basis: split
    immediate_parent: amd
    name: Pensando *
    relationship: acquisition
    score_band: emerging
    score_composite: 14.0
    slug: pensando
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: amd
    name: Mipsology
    relationship: product
    score_band: minimal
    score_composite: 3.6
    slug: mipsology
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: AMD
overview: 'AMD publishes its API surface across 3 provider profiles indexed on the APIs.io network, of
  which 3 carry a rating. The rated members span 22.7 points, from 26.3 down to 3.6.


  Its highest-rated surfaces are Xilinx, Pensando *, Mipsology.'
parent_provider: amd
permalink: /estates/amd/
slug: amd
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amd/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Semiconductors
- Technology
- Processors
- Graphics
title: AMD
---
