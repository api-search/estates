---
api_total: 113
category: Estates
description: APIs for Qlik's analytics and data integration platform.
estate_rating:
  agent_avg: 15.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 18.4
  agent_ready: 2
  band: emerging
  best: 69.7
  composite_avg: 29.6
  composite_band: thin
  composite_raw: 35.6
  developing: 0
  exemplar: 1
  rating: 23.8
  scored: 6
  spread: 52.9
  strength: 3
  strong: 0
  worst: 16.8
estate_root: null
estate_root_name: null
image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 43.6
    api_count: 78
    immediate_parent: qlik
    name: Qlik Sense
    relationship: product
    score_band: exemplar
    score_composite: 69.7
    slug: qliksense
    source: declared
  label: Exemplar
  open: true
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 5.0
    api_count: 10
    immediate_parent: qlik
    name: QlikView
    relationship: product
    score_band: thin
    score_composite: 39.0
    slug: qlikview
    source: declared
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 33.7
    api_count: 6
    immediate_parent: qlik
    name: Qlik Sense Enterprise
    relationship: product
    score_band: thin
    score_composite: 38.1
    slug: qlik-sense-enterprise
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 13
    immediate_parent: qlik
    name: Qlik Cloud
    relationship: product
    score_band: thin
    score_composite: 33.2
    slug: qlik-cloud
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: qlik
    name: Upsolver
    relationship: product
    score_band: emerging
    score_composite: 17.1
    slug: upsolver
    source: prose
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
    source: declared
  label: Emerging
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id007
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: qlik
    name: Qlik Sense
    relationship: product
    score_band: null
    score_composite: null
    slug: qlik-sense
    source: declared
  label: Unrated
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
name: Qlik
overview: 'Qlik publishes its API surface across 7 provider profiles indexed on the APIs.io network, of
  which 7 carry a rating. The rated members span 52.9 points, from 69.7 down to 16.8.


  Its highest-rated surfaces are Qlik Sense, QlikView, Qlik Sense Enterprise, Qlik Cloud, Upsolver.'
parent_provider: qlik
permalink: /estates/qlik/
slug: qlik
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qlik/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Security
- Access Control
- Machine-Learning
- Artificial Intelligence
title: Qlik
---
