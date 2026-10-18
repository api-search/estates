---
api_total: 17
category: Estates
description: SmartBear is a software company that provides AI-powered tools for API lifecycle management
  including design, testing, documentation, and governance. Their product portfolio includes SwaggerHub
  for API design and documentation, ReadyAPI for API testing, PactFlow for contract testing, and other
  tools for software quality and performance. SmartBear's developer API enables programmatic access to
  manage API definitions, automate lifecycle workflows, and integrate SwaggerHub with CI/CD pipelines
  and third-party services.
estate_rating:
  agent_avg: 14.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 17.8
  agent_ready: 2
  band: thin
  best: 76.9
  composite_avg: 34.0
  composite_band: thin
  composite_raw: 43.0
  developing: 2
  exemplar: 2
  rating: 26.4
  scored: 8
  spread: 64.4
  strength: 10
  strong: 1
  worst: 12.5
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/smartbear.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 2
  items:
  - &id001
    acquired: 2021
    agent_band: agent-ready
    agent_score: 52.2
    api_count: 5
    api_count_basis: published
    immediate_parent: smartbear
    name: Bugsnag
    relationship: acquisition
    score_band: exemplar
    score_composite: 76.9
    slug: bugsnag
    source: declared
  - &id002
    acquired: 2023
    agent_band: agent-ready
    agent_score: 31.5
    api_count: 2
    api_count_basis: published
    immediate_parent: smartbear
    name: Stoplight
    relationship: acquisition
    score_band: exemplar
    score_composite: 74.8
    slug: stoplight
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 21.7
    api_count: 5
    api_count_basis: published
    immediate_parent: swagger
    name: Swagger Codegen
    relationship: product
    score_band: strong
    score_composite: 56.2
    slug: swagger-codegen
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 17.9
    api_count: 2
    api_count_basis: published
    immediate_parent: smartbear
    name: SwaggerHub
    relationship: acquisition
    score_band: developing
    score_composite: 48.5
    slug: swaggerhub
    source: declared
  - &id005
    acquired: 2024
    agent_band: agent-aware
    agent_score: 17.9
    api_count: 1
    api_count_basis: published
    immediate_parent: smartbear
    name: Reflect
    relationship: acquisition
    score_band: developing
    score_composite: 41.3
    slug: reflect
    source: declared
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 3
  items:
  - &id006
    acquired: 2023
    agent_band: human-only
    agent_score: 0.6
    api_count: 1
    api_count_basis: split
    immediate_parent: stoplight
    name: Spectral
    relationship: acquisition
    score_band: emerging
    score_composite: 20.5
    slug: spectral
    source: declared
  - &id007
    acquired: 2023
    agent_band: human-only
    agent_score: 0.6
    api_count: 1
    api_count_basis: split
    immediate_parent: stoplight
    name: Prism
    relationship: acquisition
    score_band: emerging
    score_composite: 13.6
    slug: prism
    source: declared
  - &id008
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: smartbear
    name: ReadyAPI
    relationship: product
    score_band: emerging
    score_composite: 12.5
    slug: readyapi
    source: declared
  label: Emerging
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id009
    acquired: 2015
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: null
    immediate_parent: smartbear
    name: Swagger
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: swagger
    source: declared
  label: Unrated
  open: false
member_on_network: 9
member_total: 9
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
- *id009
members_unrated: []
name: SmartBear
overview: 'SmartBear publishes its API surface across 9 provider profiles indexed on the APIs.io network,
  of which 9 carry a rating. The rated members span 64.4 points, from 76.9 down to 12.5.


  Its highest-rated surfaces are Bugsnag, Stoplight, Swagger Codegen, SwaggerHub, Reflect.'
parent_provider: smartbear
permalink: /estates/smartbear/
slug: smartbear
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/smartbear/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 2
  members:
  - name: Spectral
    score_band: emerging
    score_composite: 20.5
    slug: spectral
  - name: Prism
    score_band: emerging
    score_composite: 13.6
    slug: prism
  name: Stoplight
  on_network: true
  permalink: /estates/stoplight/
  slug: stoplight
- has_page: false
  member_count: 1
  members:
  - name: Swagger Codegen
    score_band: strong
    score_composite: 56.2
    slug: swagger-codegen
  name: swagger
  on_network: true
  permalink: /estates/swagger/
  slug: swagger
subfamily_page_count: 0
tags:
- API Design
- API Documentation
- API Testing
- Contract Testing
- Developer Tools
- Governance
- Monitoring
- Platform
- Testing
title: SmartBear
---
