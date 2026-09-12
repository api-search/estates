---
api_total: 13
category: Estates
description: Elastic is a software company that builds search-powered solutions for observability, security,
  and search use cases. The Elastic Stack (Elasticsearch, Kibana, and related tools) lets organizations
  ingest, search, analyze, and visualize structured and unstructured data in real time. Elastic Cloud
  delivers managed Elasticsearch and Kibana deployments with REST APIs for both data operations and deployment
  management.
estate_rating:
  agent_avg: 20.9
  agent_band: emerging
  agent_native: 1
  agent_raw: 31.0
  agent_ready: 2
  band: thin
  best: 76.7
  composite_avg: 34.9
  composite_band: thin
  composite_raw: 47.8
  developing: 1
  exemplar: 1
  rating: 29.3
  scored: 5
  spread: 51.6
  strength: 6
  strong: 1
  worst: 25.1
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
    agent_band: agent-native
    agent_score: 47.1
    api_count: 3
    immediate_parent: elastic
    name: Elastic Stack (ELK Stack)
    relationship: product
    score_band: exemplar
    score_composite: 76.7
    slug: elk-stack
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 29.5
    api_count: 1
    immediate_parent: elastic
    name: Elastic Observability
    relationship: product
    score_band: strong
    score_composite: 58.4
    slug: elastic-observability
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 26.1
    api_count: 1
    immediate_parent: elastic
    name: Elasticsearch
    relationship: product
    score_band: developing
    score_composite: 41.8
    slug: elasticsearch
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 35.2
    api_count: 1
    immediate_parent: elastic
    name: Kibana
    relationship: product
    score_band: thin
    score_composite: 37.0
    slug: kibana
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 17.3
    api_count: 7
    immediate_parent: elastic
    name: Elastic Stack
    relationship: product
    score_band: emerging
    score_composite: 25.1
    slug: elastic-stack
  label: Emerging
  open: false
member_on_network: 5
member_total: 5
members:
- *id001
- *id002
- *id003
- *id004
- *id005
members_unrated: []
name: Elastic
overview: 'Elastic publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 51.6 points, from 76.7 down to 25.1.


  Its highest-rated surfaces are Elastic Stack (ELK Stack), Elastic Observability, Elasticsearch, Kibana,
  Elastic Stack.'
parent_provider: elastic
permalink: /estates/elastic/
slug: elastic
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/elastic/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Search
- Analytics
- Observability
- Security
- Visualization
- Cloud
title: Elastic
---
