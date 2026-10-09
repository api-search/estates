---
api_total: 1
category: Estates
description: Snowflake is a cloud-based data platform delivering data warehousing, data lakes, data engineering,
  data science and data application development as a single managed service across AWS, Azure and Google
  Cloud. Its developer surface is a 47-document OpenAPI corpus over /api/v2 covering databases, schemas,
  tables, Iceberg and dynamic tables, warehouses, tasks, pipes, streams, roles and grants, plus a SQL
  API for arbitrary statements and a Cortex family for AI inference, semantic analytics and retrieval.
  Snowflake also serves a SCIM 2.0 identity endpoint, an Apache Iceberg REST Catalog, and an account-hosted
  Model Context Protocol server that exposes Cortex tools to agents under Snowflake RBAC.
estate_rating:
  agent_avg: 5.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.1
  agent_ready: 0
  band: emerging
  best: 19.6
  composite_avg: 15.1
  composite_band: emerging
  composite_raw: 8.5
  developing: 0
  exemplar: 0
  rating: 11.4
  scored: 4
  spread: 19.6
  strength: 0
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://www.snowflake.com/wp-content/themes/snowflake/assets/img/brand-guidelines/logo-sno-blue-example.svg
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: snowflake
    name: Datavolo
    relationship: acquisition
    score_band: emerging
    score_composite: 19.6
    slug: datavolo
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.6
    api_count: 1
    api_count_basis: split
    immediate_parent: snowflake
    name: TruEra (Snowflake)
    relationship: acquisition
    score_band: minimal
    score_composite: 10.6
    slug: truera
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: snowflake
    name: Ponder
    relationship: acquisition
    score_band: minimal
    score_composite: 3.6
    slug: ponder
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: snowflake
    name: Neeva
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: neeva
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: snowflake
    name: Sisu Data
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: sisu-data
    source: prose
  label: Unrated
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
name: Snowflake
overview: 'Snowflake publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 19.6 points, from 19.6 down to 0.0.


  Its highest-rated surfaces are Datavolo, TruEra (Snowflake), Ponder, Neeva, Sisu Data.'
parent_provider: snowflake
permalink: /estates/snowflake/
slug: snowflake
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/snowflake/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Snowflake
- Data
- Data Warehouse
- Data Lakehouse
- Cloud Data Platform
- Analytics
- Artificial Intelligence
- Data Engineering
- Data Governance
- SQL
- Apache Iceberg
- MCP
title: Snowflake
---
