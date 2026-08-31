---
api_total: 13
category: Estates
description: Elastic is a software company that builds search-powered solutions for observability, security,
  and search use cases. The Elastic Stack (Elasticsearch, Kibana, and related tools) lets organizations
  ingest, search, analyze, and visualize structured and unstructured data in real time. Elastic Cloud
  delivers managed Elasticsearch and Kibana deployments with REST APIs for both data operations and deployment
  management.
estate_rating:
  agent_avg: 21.8
  agent_band: emerging
  agent_native: 2
  agent_raw: 33.7
  agent_ready: 1
  band: thin
  best: 65.1
  composite_avg: 33.3
  composite_band: thin
  composite_raw: 45.4
  developing: 1
  exemplar: 0
  rating: 28.7
  scored: 5
  spread: 37.3
  strength: 5
  strong: 2
  worst: 27.8
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/elastic.png
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-native
    agent_score: 51.3
    api_count: 3
    immediate_parent: elastic
    name: Elastic Stack (ELK Stack)
    relationship: product
    score_band: strong
    score_composite: 65.1
    slug: elk-stack
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 32.2
    api_count: 1
    immediate_parent: elastic
    name: Elastic Observability
    relationship: product
    score_band: strong
    score_composite: 57.0
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
    score_composite: 42.5
    slug: elasticsearch
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: agent-native
    agent_score: 41.7
    api_count: 1
    immediate_parent: elastic
    name: Kibana
    relationship: product
    score_band: thin
    score_composite: 34.4
    slug: kibana
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 17.3
    api_count: 7
    immediate_parent: elastic
    name: Elastic Stack
    relationship: product
    score_band: thin
    score_composite: 27.8
    slug: elastic-stack
  label: Thin
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
  of which 5 carry a rating. The rated members span 37.3 points, from 65.1 down to 27.8.


  Its highest-rated surfaces are Elastic Stack (ELK Stack), Elastic Observability, Elasticsearch, Kibana,
  Elastic Stack.'
parent_provider: elastic
permalink: /estates/elastic/
slug: elastic
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/elastic/refs/heads/main/apis.yml
subfamilies: []
tags:
- Search
- Analytics
- Observability
- Security
- Visualization
- Cloud
title: Elastic
---
