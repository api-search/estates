---
api_total: 0
category: Estates
description: Marathon Petroleum is one of the largest petroleum product refiners, transporters, and marketers
  in the United States, with operations including refineries, pipelines, terminals, and retail outlets.
  No public developer APIs have been identified at this time.
estate_rating:
  agent_avg: 8.3
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 8.9
  composite_avg: 18.4
  composite_band: emerging
  composite_raw: 7.6
  developing: 0
  exemplar: 0
  rating: 14.4
  scored: 2
  spread: 2.7
  strength: 0
  strong: 0
  worst: 6.2
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/marathon-petroleum.png
is_subfamily: false
layout: estate
member_bands:
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: marathon-petroleum
    name: Tesoro
    relationship: acquisition
    score_band: minimal
    score_composite: 8.9
    slug: tesoro
    source: declared
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: marathon-petroleum
    name: Western Refining
    relationship: product
    score_band: minimal
    score_composite: 6.2
    slug: western-refining
    source: parent-company-property
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: western-refining
    name: Northern Tier Energy
    relationship: product
    score_band: null
    score_composite: null
    slug: northern-tier-energy
    source: parent-company-property
  label: Unrated
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Marathon Petroleum
overview: 'Marathon Petroleum publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 2.7 points, from 8.9 down to 6.2.


  Its highest-rated surfaces are Tesoro, Western Refining, Northern Tier Energy.'
parent_provider: marathon-petroleum
permalink: /estates/marathon-petroleum/
slug: marathon-petroleum
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/marathon-petroleum/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Northern Tier Energy
    score_band: null
    score_composite: null
    slug: northern-tier-energy
  name: Western Refining
  on_network: true
  permalink: /estates/western-refining/
  slug: western-refining
subfamily_page_count: 0
tags:
- Energy
- Fortune 500
- Petroleum
- Pipelines
- Refining
title: Marathon Petroleum
---
