---
api_total: 130
category: Estates
description: APIs for Qlik's analytics and data integration platform.
estate_rating:
  agent_avg: 17.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 23.1
  agent_ready: 3
  band: thin
  best: 72.5
  composite_avg: 31.8
  composite_band: thin
  composite_raw: 40.0
  developing: 1
  exemplar: 1
  rating: 26.2
  scored: 7
  spread: 56.6
  strength: 6
  strong: 1
  worst: 15.9
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
    score_composite: 72.5
    slug: qliksense
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 51.9
    api_count: 17
    immediate_parent: qlik
    name: Talend
    relationship: product
    score_band: strong
    score_composite: 64.1
    slug: talend
    source: parent-company-property
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 5.0
    api_count: 10
    immediate_parent: qlik
    name: QlikView
    relationship: product
    score_band: developing
    score_composite: 41.7
    slug: qlikview
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 33.3
    api_count: 6
    immediate_parent: qlik
    name: Qlik Sense Enterprise
    relationship: product
    score_band: thin
    score_composite: 37.8
    slug: qlik-sense-enterprise
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 22.9
    api_count: 13
    immediate_parent: qlik
    name: Qlik Cloud
    relationship: product
    score_band: thin
    score_composite: 31.8
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
    score_composite: 16.3
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
    score_composite: 15.9
    slug: qlik-mashups
    source: declared
  label: Emerging
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id008
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: talend
    name: RJMetrics
    relationship: product
    score_band: null
    score_composite: null
    slug: rjmetrics
    source: parent-company-property
  label: Unrated
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
  which 8 carry a rating. The rated members span 56.6 points, from 72.5 down to 15.9.


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
    score_band: null
    score_composite: null
    slug: rjmetrics
  name: Talend
  on_network: true
  permalink: /estates/talend/
  slug: talend
subfamily_page_count: 0
tags:
- Security
- Access Control
- Machine Learning
- Artificial Intelligence
title: Qlik
---
