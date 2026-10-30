---
api_total: 129
category: Estates
description: APIs for Qlik's analytics and data integration platform.
estate_rating:
  agent_avg: 16.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 19.6
  agent_ready: 3
  band: emerging
  best: 71.0
  composite_avg: 28.3
  composite_band: thin
  composite_raw: 33.6
  developing: 1
  exemplar: 1
  rating: 23.4
  scored: 8
  spread: 67.9
  strength: 6
  strong: 1
  worst: 3.1
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
    agent_score: 42.9
    api_count: 78
    api_count_basis: published
    immediate_parent: qlik
    name: Qlik Sense
    relationship: product
    score_band: exemplar
    score_composite: 71.0
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
    agent_score: 51.1
    api_count: 16
    api_count_basis: published
    immediate_parent: qlik
    name: Talend
    relationship: product
    score_band: strong
    score_composite: 57.2
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
    api_count_basis: split
    immediate_parent: qlik
    name: QlikView
    relationship: product
    score_band: developing
    score_composite: 40.2
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
    agent_score: 31.8
    api_count: 6
    api_count_basis: published
    immediate_parent: qlik
    name: Qlik Sense Enterprise
    relationship: product
    score_band: thin
    score_composite: 36.6
    slug: qlik-sense-enterprise
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 22.7
    api_count: 13
    api_count_basis: split
    immediate_parent: qlik
    name: Qlik Cloud
    relationship: product
    score_band: thin
    score_composite: 30.3
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
    api_count_basis: split
    immediate_parent: qlik
    name: Upsolver
    relationship: product
    score_band: emerging
    score_composite: 16.4
    slug: upsolver
    source: parent-company-property
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.6
    api_count: 5
    api_count_basis: split
    immediate_parent: qlik
    name: Qlik Mashups
    relationship: product
    score_band: emerging
    score_composite: 14.4
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
    api_count_basis: split
    immediate_parent: qlik
    name: Blendr.io
    relationship: acquisition
    score_band: minimal
    score_composite: 3.1
    slug: blendr
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id009
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: talend
    name: RJMetrics
    relationship: product
    score_band: null
    score_composite: null
    slug: rjmetrics
    source: parent-company-property
  label: Unrated
  open: false
member_on_network: 9
member_total: 9
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
- *id009
members_unrated: []
name: Qlik
overview: 'Qlik publishes its API surface across 9 provider profiles indexed on the APIs.io network, of
  which 9 carry a rating. The rated members span 67.9 points, from 71.0 down to 3.1.


  Its highest-rated surfaces are Qlik Sense, Talend, QlikView, Qlik Sense Enterprise, Qlik Cloud.'
parent_provider: qlik
permalink: /estates/qlik/
slug: qlik
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/qlik/apis.yml
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
