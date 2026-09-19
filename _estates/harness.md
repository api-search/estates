---
api_total: 8
category: Estates
description: Harness is an AI-powered software delivery platform that automates and accelerates the entire
  software development lifecycle from code to production. The platform provides intelligent automation
  across DevOps, testing and resilience, security and compliance, and cost optimization, helping engineering
  teams ship code faster, safer, and smarter as they scale.
estate_rating:
  agent_avg: 16.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 24.6
  agent_ready: 1
  band: emerging
  best: 39.0
  composite_avg: 27.1
  composite_band: thin
  composite_raw: 35.0
  developing: 0
  exemplar: 0
  rating: 22.7
  scored: 3
  spread: 8.3
  strength: 0
  strong: 0
  worst: 30.7
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
    score_composite: 35.3
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
    score_composite: 30.7
    slug: overops
    source: x-parent-company
  label: Thin
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Harness
overview: 'Harness publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 8.3 points, from 39.0 down to 30.7.


  Its highest-rated surfaces are Harness Cloud Cost Management, Armory, Overops.'
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
