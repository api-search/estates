---
api_total: 115
category: Estates
description: APIs for Qlik's analytics and data integration platform.
estate_rating:
  agent_avg: 14.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 16.3
  agent_ready: 2
  band: emerging
  best: 69.7
  composite_avg: 28.9
  composite_band: thin
  composite_raw: 32.7
  developing: 1
  exemplar: 1
  rating: 23.1
  scored: 8
  spread: 64.7
  strength: 4
  strong: 0
  worst: 5.0
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
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 2
    immediate_parent: qlik
    name: Talend
    relationship: product
    score_band: developing
    score_composite: 42.8
    slug: talend
    source: parent-company-property
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id003
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
  - &id004
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
  - &id005
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
  - &id006
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
    source: parent-company-property
  - &id007
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
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id008
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: talend
    name: RJMetrics
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: rjmetrics
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 8
member_total: 8
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
members_unrated: []
name: Qlik
overview: 'Qlik publishes its API surface across 8 provider profiles indexed on the APIs.io network, of
  which 8 carry a rating. The rated members span 64.7 points, from 69.7 down to 5.0.


  Its highest-rated surfaces are Qlik Sense, Talend, QlikView, Qlik Sense Enterprise, Qlik Cloud.'
parent_provider: qlik
permalink: /estates/qlik/
slug: qlik
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qlik/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: RJMetrics
    score_band: minimal
    score_composite: 5.0
    slug: rjmetrics
  name: Talend
  on_network: true
  permalink: /estates/talend/
  slug: talend
subfamily_page_count: 0
tags:
- Security
- Access Control
- Machine-Learning
- Artificial Intelligence
title: Qlik
---
