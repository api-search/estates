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
  agent_avg: 9.4
  agent_band: minimal
  agent_native: 0
  agent_raw: 8.5
  agent_ready: 2
  band: emerging
  best: 36.6
  composite_avg: 15.5
  composite_band: emerging
  composite_raw: 12.0
  developing: 0
  exemplar: 0
  rating: 13.1
  scored: 7
  spread: 34.1
  strength: 0
  strong: 0
  worst: 2.5
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
    score_composite: 36.6
    slug: rockwell-collins
    source: parent-company-property
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 30.6
    api_count: 3
    immediate_parent: rtx
    name: United Technologies
    relationship: product
    score_band: thin
    score_composite: 28.4
    slug: united-technologies
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 5
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
    score_composite: 4.7
    slug: b-e-aerospace
    source: parent-company-property
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: rtx
    name: Raytheon
    relationship: product
    score_band: minimal
    score_composite: 4.6
    slug: raytheon
    source: declared
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: rtx
    name: BBN Technologies
    relationship: subsidiary
    score_band: minimal
    score_composite: 3.7
    slug: bbn-technologies
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: rtx
    name: Pratt & Whitney
    relationship: subsidiary
    score_band: minimal
    score_composite: 3.4
    slug: pratt-and-whitney
    source: prose
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: rtx
    name: BBN
    relationship: product
    score_band: minimal
    score_composite: 2.5
    slug: bbn
    source: declared
  label: Minimal
  open: false
member_on_network: 7
member_total: 7
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
members_unrated: []
name: RTX
overview: 'RTX publishes its API surface across 7 provider profiles indexed on the APIs.io network, of
  which 7 carry a rating. The rated members span 34.1 points, from 36.6 down to 2.5.


  Its highest-rated surfaces are Rockwell Collins, United Technologies, B/E Aerospace, Raytheon, BBN Technologies.'
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
    score_composite: 36.6
    slug: rockwell-collins
  - name: B/E Aerospace
    score_band: minimal
    score_composite: 4.7
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
