---
api_total: 4
category: Estates
description: 'RTX Corporation is a leading American aerospace and defense company comprising three market
  businesses: Collins Aerospace, Pratt & Whitney, and Raytheon. Raytheon develops the EAGLE (Enhanced
  Automated Graphical Logistics Environment) software platform for integrated logistics support and logistic
  support analysis across defense programs. RTX BBN Technologies (a Raytheon subsidiary) develops open-source
  software including SPARQL triple stores, NLP frameworks, and TAK ecosystem plugins for government and
  military situational awareness platforms.'
estate_rating:
  agent_avg: 10.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.0
  agent_ready: 2
  band: emerging
  best: 38.1
  composite_avg: 18.1
  composite_band: emerging
  composite_raw: 14.5
  developing: 0
  exemplar: 0
  rating: 15.1
  scored: 6
  spread: 34.7
  strength: 0
  strong: 0
  worst: 3.4
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/rtx.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 29.1
    api_count: 1
    immediate_parent: united-technologies
    name: Rockwell Collins
    relationship: product
    score_band: thin
    score_composite: 38.1
    slug: rockwell-collins
    source: prose
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 30.6
    api_count: 3
    immediate_parent: rtx
    name: United Technologies
    relationship: product
    score_band: thin
    score_composite: 28.8
    slug: united-technologies
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 4
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: rockwell-collins
    name: B/E Aerospace
    relationship: product
    score_band: minimal
    score_composite: 7.2
    slug: b-e-aerospace
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: rtx
    name: BBN
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: bbn
    source: declared
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: rtx
    name: Raytheon
    relationship: product
    score_band: minimal
    score_composite: 4.2
    slug: raytheon
    source: declared
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: rtx
    name: BBN Technologies
    relationship: product
    score_band: minimal
    score_composite: 3.4
    slug: bbn-technologies
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
name: RTX
overview: 'RTX publishes its API surface across 6 provider profiles indexed on the APIs.io network, of
  which 6 carry a rating. The rated members span 34.7 points, from 38.1 down to 3.4.


  Its highest-rated surfaces are Rockwell Collins, United Technologies, B/E Aerospace, BBN, Raytheon.'
parent_provider: rtx
permalink: /estates/rtx/
slug: rtx
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rtx/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 2
  members:
  - name: Rockwell Collins
    score_band: thin
    score_composite: 38.1
    slug: rockwell-collins
  - name: B/E Aerospace
    score_band: minimal
    score_composite: 7.2
    slug: b-e-aerospace
  name: United Technologies
  on_network: true
  permalink: /estates/united-technologies/
  slug: united-technologies
subfamily_page_count: 0
tags:
- Defense
- Aerospace
- Government
- Logistics
- Intelligence
- Military
title: RTX
---
