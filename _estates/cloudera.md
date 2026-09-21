---
api_total: 12
category: Estates
description: Cloudera is a hybrid data platform company offering the Cloudera Data Platform (CDP) for
  data engineering, data warehousing, machine learning, streaming, and operational data. The platform
  exposes multiple REST APIs including the CDP Public Cloud Control Plane API for managing environments,
  datalakes, data hubs and workloads, the Cloudera Manager API for cluster lifecycle and configuration
  management, and per-service REST APIs across the runtime (Cruise Control, Streams Replication Manager,
  HBase REST, YARN Queue Manager, etc.). APIs are JSON, support standard CRUD, and are typically authenticated
  via API access keys, basic auth, or session cookies.
estate_rating:
  agent_avg: 9.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 7.0
  agent_ready: 0
  band: emerging
  best: 25.2
  composite_avg: 19.1
  composite_band: emerging
  composite_raw: 13.0
  developing: 0
  exemplar: 0
  rating: 15.4
  scored: 3
  spread: 20.2
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cloudera.png
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 21.0
    api_count: 12
    immediate_parent: cloudera
    name: Verta
    relationship: product
    score_band: emerging
    score_composite: 25.2
    slug: verta
    source: parent-company-property
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cloudera
    name: Continual
    relationship: product
    score_band: minimal
    score_composite: 8.9
    slug: continual
    source: parent-company-property
  - &id003
    acquired: 2022
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cloudera
    name: Cazena
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: cazena
    source: declared
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Cloudera
overview: 'Cloudera publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 20.2 points, from 25.2 down to 5.0.


  Its highest-rated surfaces are Verta, Continual, Cazena.'
parent_provider: cloudera
permalink: /estates/cloudera/
slug: cloudera
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudera/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Big Data
- Data Engineering
- Data Lakehouse
- Data Platform
- Data Warehouse
- Hadoop
- Hybrid Cloud
- Machine-Learning
- Streaming
title: Cloudera
---
