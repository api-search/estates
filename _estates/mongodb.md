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
  agent_raw: 19.1
  agent_ready: 0
  band: emerging
  best: 35.8
  composite_avg: 22.6
  composite_band: emerging
  composite_raw: 29.6
  developing: 0
  exemplar: 0
  rating: 18.8
  scored: 2
  spread: 12.3
  strength: 0
  strong: 0
  worst: 23.5
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/mongodb.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 22.2
    api_count: 1
    api_count_basis: published
    immediate_parent: mongodb
    name: MongoDB Atlas
    relationship: product
    score_band: thin
    score_composite: 35.8
    slug: mongodb-atlas
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 16.1
    api_count: 1
    api_count_basis: published
    immediate_parent: mongodb
    name: Voyage AI
    relationship: acquisition
    score_band: emerging
    score_composite: 23.5
    slug: voyage-ai
    source: prose
  label: Emerging
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
  of which 3 carry a rating. The rated members span 12.3 points, from 35.8 down to 23.5.


  Its highest-rated surfaces are MongoDB Atlas, Voyage AI, Schema Free.'
parent_provider: mongodb
permalink: /estates/mongodb/
slug: mongodb
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/mongodb/apis.yml
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
