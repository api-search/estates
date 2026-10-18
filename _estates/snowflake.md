---
api_total: 26
category: Estates
description: Snowflake is a cloud-based data platform delivering data warehousing, data lakes, data engineering,
  data science and data application development as a single managed service across AWS, Azure and Google
  Cloud. Its developer surface is a 47-document OpenAPI corpus over /api/v2 covering databases, schemas,
  tables, Iceberg and dynamic tables, warehouses, tasks, pipes, streams, roles and grants, plus a SQL
  API for arbitrary statements and a Cortex family for AI inference, semantic analytics and retrieval.
  Snowflake also serves a SCIM 2.0 identity endpoint, an Apache Iceberg REST Catalog, and an account-hosted
  Model Context Protocol server that exposes Cortex tools to agents under Snowflake RBAC.
estate_rating:
  agent_avg: 12.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 13.6
  agent_ready: 2
  band: emerging
  best: 61.6
  composite_avg: 21.6
  composite_band: emerging
  composite_raw: 23.3
  developing: 1
  exemplar: 0
  rating: 17.8
  scored: 6
  spread: 61.6
  strength: 3
  strong: 1
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://www.snowflake.com/wp-content/themes/snowflake/assets/img/brand-guidelines/logo-sno-blue-example.svg
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 43.4
    api_count: 2
    api_count_basis: published
    immediate_parent: snowflake
    name: Observe
    relationship: product
    score_band: strong
    score_composite: 61.6
    slug: observeinc
    source: x-parent-company
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 37.7
    api_count: 23
    api_count_basis: split
    immediate_parent: snowflake
    name: Crunchy Data
    relationship: product
    score_band: developing
    score_composite: 46.2
    slug: crunchy-data
    source: x-parent-company
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: snowflake
    name: Datavolo
    relationship: acquisition
    score_band: emerging
    score_composite: 19.2
    slug: datavolo
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.6
    api_count: 1
    api_count_basis: split
    immediate_parent: snowflake
    name: TruEra (Snowflake)
    relationship: acquisition
    score_band: minimal
    score_composite: 9.1
    slug: truera
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: snowflake
    name: Ponder
    relationship: acquisition
    score_band: minimal
    score_composite: 3.7
    slug: ponder
    source: prose
  - &id006
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
  - &id007
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
member_on_network: 7
member_total: 7
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
members_unrated: []
name: Snowflake
overview: 'Snowflake publishes its API surface across 7 provider profiles indexed on the APIs.io network,
  of which 7 carry a rating. The rated members span 61.6 points, from 61.6 down to 0.0.


  Its highest-rated surfaces are Observe, Crunchy Data, Datavolo, TruEra (Snowflake), Ponder.'
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
