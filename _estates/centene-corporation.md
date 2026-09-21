---
api_total: 2
category: Estates
description: ''
estate_rating:
  agent_avg: 11.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.1
  agent_ready: 1
  band: emerging
  best: 36.5
  composite_avg: 19.7
  composite_band: emerging
  composite_raw: 14.8
  developing: 0
  exemplar: 0
  rating: 16.2
  scored: 3
  spread: 33.2
  strength: 0
  strong: 0
  worst: 3.3
estate_root: null
estate_root_name: null
image: ''
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 30.2
    api_count: 2
    immediate_parent: centene-corporation
    name: WellCare Health Plans
    relationship: product
    score_band: thin
    score_composite: 36.5
    slug: wellcare-health-plans
    source: parent-company-property
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: wellcare-health-plans
    name: Universal American
    relationship: product
    score_band: minimal
    score_composite: 4.7
    slug: universal-american
    source: parent-company-property
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: centene-corporation
    name: Apixio (Centene)
    relationship: product
    score_band: minimal
    score_composite: 3.3
    slug: apixio-centene
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
name: centene-corporation
overview: 'centene-corporation publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 33.2 points, from 36.5 down to 3.3.


  Its highest-rated surfaces are WellCare Health Plans, Universal American, Apixio (Centene).'
parent_provider: centene-corporation
permalink: /estates/centene-corporation/
slug: centene-corporation
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/centene-corporation/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Universal American
    score_band: minimal
    score_composite: 4.7
    slug: universal-american
  name: WellCare Health Plans
  on_network: true
  permalink: /estates/wellcare-health-plans/
  slug: wellcare-health-plans
subfamily_page_count: 0
tags: []
title: centene-corporation
---
