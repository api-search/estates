---
api_total: 117
category: Estates
description: APIs for Qlik's analytics and data integration platform.
estate_rating:
  agent_avg: 16.7
  agent_band: emerging
  agent_native: 0
  agent_raw: 22.3
  agent_ready: 3
  band: thin
  best: 59.3
  composite_avg: 30.7
  composite_band: thin
  composite_raw: 38.6
  developing: 1
  exemplar: 0
  rating: 25.1
  scored: 6
  spread: 42.5
  strength: 3
  strong: 1
  worst: 16.8
image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo.png
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 40.1
    api_count: 82
    immediate_parent: qlik
    name: Qlik Sense APIs
    relationship: product
    score_band: strong
    score_composite: 59.3
    slug: qliksense
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 30.7
    api_count: 1
    immediate_parent: qlik
    name: Qlik Sense
    relationship: product
    score_band: developing
    score_composite: 45.8
    slug: qlik-sense
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 8.5
    api_count: 10
    immediate_parent: qlik
    name: QlikView
    relationship: product
    score_band: thin
    score_composite: 39.0
    slug: qlikview
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 29.0
    api_count: 6
    immediate_parent: qlik
    name: Qlik Sense Enterprise
    relationship: product
    score_band: thin
    score_composite: 36.7
    slug: qlik-sense-enterprise
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 13
    immediate_parent: qlik
    name: Qlik Cloud
    relationship: product
    score_band: thin
    score_composite: 33.7
    slug: qlik-cloud
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 5
    immediate_parent: qlik
    name: Qlik Mashups
    relationship: product
    score_band: emerging
    score_composite: 16.8
    slug: qlik-mashups
  label: Emerging
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
name: Qlik
overview: 'Qlik publishes its API surface across 6 provider profiles indexed on the APIs.io network, of
  which 6 carry a rating. The rated members span 42.5 points, from 59.3 down to 16.8.


  Its highest-rated surfaces are Qlik Sense APIs, Qlik Sense, QlikView, Qlik Sense Enterprise, Qlik Cloud.'
parent_provider: qlik
permalink: /estates/qlik/
slug: qlik
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qlik/refs/heads/main/apis.yml
subfamilies: []
tags: []
title: Qlik
---
