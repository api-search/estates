---
api_total: 14
category: Estates
description: Elastic is a software company that builds search-powered solutions for observability, security,
  and search use cases. The Elastic Stack (Elasticsearch, Kibana, and related tools) lets organizations
  ingest, search, analyze, and visualize structured and unstructured data in real time. Elastic Cloud
  delivers managed Elasticsearch and Kibana deployments with REST APIs for both data operations and deployment
  management.
estate_rating:
  agent_avg: 18.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 27.1
  agent_ready: 2
  band: thin
  best: 76.9
  composite_avg: 33.0
  composite_band: thin
  composite_raw: 46.3
  developing: 1
  exemplar: 1
  rating: 27.4
  scored: 5
  spread: 55.9
  strength: 6
  strong: 1
  worst: 21.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/elastic.png
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
    agent_score: 43.9
    api_count: 10
    api_count_basis: published
    immediate_parent: elastic
    name: Elastic Stack
    relationship: product
    score_band: exemplar
    score_composite: 76.9
    slug: elk-stack
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 28.5
    api_count: 1
    api_count_basis: published
    immediate_parent: elastic
    name: Elastic Observability
    relationship: product
    score_band: strong
    score_composite: 58.0
    slug: elastic-observability
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 25.8
    api_count: 1
    api_count_basis: published
    immediate_parent: elastic
    name: Elasticsearch
    relationship: product
    score_band: developing
    score_composite: 42.5
    slug: elasticsearch
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 32.5
    api_count: 1
    api_count_basis: published
    immediate_parent: elastic
    name: Kibana
    relationship: product
    score_band: thin
    score_composite: 33.1
    slug: kibana
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 5.0
    api_count: 1
    api_count_basis: split
    immediate_parent: elastic
    name: Swiftype
    relationship: product
    score_band: emerging
    score_composite: 21.0
    slug: swiftype
    source: parent-company-property
  label: Emerging
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id006
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: elastic
    name: Cmd *
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: cmd
    source: prose
  label: Unrated
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
name: Elastic
overview: 'Elastic publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 55.9 points, from 76.9 down to 21.0.


  Its highest-rated surfaces are Elastic Stack, Elastic Observability, Elasticsearch, Kibana, Swiftype.'
parent_provider: elastic
permalink: /estates/elastic/
slug: elastic
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/elastic/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Search
- Analytics
- Observability
- Security
- Visualization
- Cloud
- Monitoring
title: Elastic
---
