---
api_total: 2
category: Estates
description: MongoDB provides a document‑model database platform that can be deployed on any cloud or
  on‑premises infrastructure. It offers services such as MongoDB Atlas for multi‑cloud data management,
  vector search, real‑time operational workloads, and tools like Compass for GUI access. The platform
  is used by developers and enterprises building applications that require scalable, searchable, and AI‑enabled
  data handling.
estate_rating:
  agent_avg: 13.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 19.2
  agent_ready: 0
  band: emerging
  best: 34.3
  composite_avg: 23.6
  composite_band: emerging
  composite_raw: 31.8
  developing: 0
  exemplar: 0
  rating: 19.4
  scored: 2
  spread: 4.9
  strength: 0
  strong: 0
  worst: 29.4
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/mongodb.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 20.5
    api_count: 1
    api_count_basis: published
    immediate_parent: mongodb
    name: MongoDB Atlas
    relationship: product
    score_band: thin
    score_composite: 34.3
    slug: mongodb-atlas
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 18.0
    api_count: 1
    api_count_basis: published
    immediate_parent: mongodb
    name: Voyage AI
    relationship: acquisition
    score_band: thin
    score_composite: 29.4
    slug: voyage-ai
    source: prose
  label: Thin
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: null
    immediate_parent: mongodb
    name: Schema Free
    relationship: product
    score_band: null
    score_composite: null
    slug: schema-free
    source: declared
  label: Unrated
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: MongoDB
overview: 'MongoDB publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 4.9 points, from 34.3 down to 29.4.


  Its highest-rated surfaces are MongoDB Atlas, Voyage AI, Schema Free.'
parent_provider: mongodb
permalink: /estates/mongodb/
slug: mongodb
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mongodb/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Cloud Database
- Database
- Document Database
- NoSQL
- MongoDB
title: MongoDB
---
