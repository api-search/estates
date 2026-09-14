---
api_total: 0
category: Estates
description: SentinelOne is an AI-driven extended detection and response (XDR) cloud security platform
  delivering autonomous endpoint protection, EDR, identity security, cloud workload protection, and threat
  hunting through its Singularity Platform. The Management API exposes the same operations as the web
  console for agents, threats, alerts, sites, accounts, exclusions, and policy management. Authentication
  uses tenant-issued API tokens passed in the Authorization header as `ApiToken <token>`.
estate_rating:
  agent_avg: 6.8
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 6.3
  composite_avg: 15.9
  composite_band: emerging
  composite_raw: 5.4
  developing: 0
  exemplar: 0
  rating: 12.3
  scored: 3
  spread: 1.3
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/sentinelone.png
is_subfamily: false
layout: estate
member_bands:
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: sentinelone
    name: Scalyr
    relationship: product
    score_band: minimal
    score_composite: 6.3
    slug: scalyr
    source: prose
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: sentinelone
    name: Observo
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: observo
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: sentinelone
    name: Observo Ai
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: observo-ai
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
name: SentinelOne
overview: 'SentinelOne publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 1.3 points, from 6.3 down to 5.0.


  Its highest-rated surfaces are Scalyr, Observo, Observo Ai.'
parent_provider: sentinelone
permalink: /estates/sentinelone/
slug: sentinelone
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sentinelone/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Security
- XDR
- EDR
- Endpoint Protection
- Threat Detection
- Incident Response
- Cloud Security
- Identity Security
title: SentinelOne
---
