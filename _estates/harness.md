---
api_total: 8
category: Estates
description: Harness is an AI-powered software delivery platform that automates and accelerates the entire
  software development lifecycle from code to production. The platform provides intelligent automation
  across DevOps, testing and resilience, security and compliance, and cost optimization, helping engineering
  teams ship code faster, safer, and smarter as they scale.
estate_rating:
  agent_avg: 14.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 18.4
  agent_ready: 1
  band: emerging
  best: 39.0
  composite_avg: 25.2
  composite_band: thin
  composite_raw: 29.1
  developing: 0
  exemplar: 0
  rating: 20.8
  scored: 4
  spread: 29.6
  strength: 0
  strong: 0
  worst: 9.4
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/harness.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: harness
    name: Harness Cloud Cost Management
    relationship: product
    score_band: thin
    score_composite: 39.0
    slug: harness-cloud-cost
    source: declared
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 30.3
    api_count: 6
    immediate_parent: harness
    name: Armory
    relationship: product
    score_band: thin
    score_composite: 36.4
    slug: armory
    source: prose
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 23.6
    api_count: 1
    immediate_parent: harness
    name: Overops
    relationship: product
    score_band: thin
    score_composite: 31.5
    slug: overops
    source: x-parent-company
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: harness
    name: Armory.io
    relationship: product
    score_band: minimal
    score_composite: 9.4
    slug: armoryio
    source: prose
  label: Minimal
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Harness
overview: 'Harness publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 29.6 points, from 39.0 down to 9.4.


  Its highest-rated surfaces are Harness Cloud Cost Management, Armory, Overops, Armory.io.'
parent_provider: harness
permalink: /estates/harness/
slug: harness
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/harness/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- DevOps
- GitOps
- Internal Developer Portal
- Lifecycle
- Software Delivery
title: Harness
---
