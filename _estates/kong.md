---
api_total: 23
category: Estates
description: Kong is the AI Connectivity Company. Its platform spans Kong Gateway (the open-source API
  gateway built on NGINX and Lua), Kong Konnect (the SaaS control plane), Kong AI Gateway (LLM, MCP, and
  agent-to-agent traffic governance with semantic caching, token budgeting, and prompt firewalls), Kong
  Agent Gateway, Kong Event Gateway (Kafka-native governance), Kong Mesh (service mesh on Kuma and Envoy),
  Kong MCP Registry (centralized directory of MCP servers and tools for AI agents), Kong Context Mesh,
  and Kong Insomnia (API design and testing). Together they unify governance across APIs, real-time event
  streams, LLM calls, MCP tools, and agent-to-agent communication for the agentic era.
estate_rating:
  agent_avg: 12.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 15.5
  agent_ready: 0
  band: emerging
  best: 53.9
  composite_avg: 28.9
  composite_band: thin
  composite_raw: 43.1
  developing: 1
  exemplar: 0
  rating: 22.3
  scored: 3
  spread: 16.2
  strength: 1
  strong: 0
  worst: 37.7
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/kong.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: 2019
    agent_band: agent-aware
    agent_score: 19.5
    api_count: 1
    api_count_basis: published
    immediate_parent: kong
    name: Insomnia
    relationship: acquisition
    score_band: developing
    score_composite: 53.9
    slug: insomnia
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 5.6
    api_count: 21
    api_count_basis: split
    immediate_parent: kong
    name: Kong AI Gateway
    relationship: product
    score_band: thin
    score_composite: 37.7
    slug: kong-ai-gateway
    source: declared
  - &id003
    acquired: 2025
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    api_count_basis: published
    immediate_parent: kong
    name: OpenMeter
    relationship: acquisition
    score_band: thin
    score_composite: 37.7
    slug: openmeter
    source: declared
  label: Thin
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Kong
overview: 'Kong publishes its API surface across 3 provider profiles indexed on the APIs.io network, of
  which 3 carry a rating. The rated members span 16.2 points, from 53.9 down to 37.7.


  Its highest-rated surfaces are Insomnia, Kong AI Gateway, OpenMeter.'
parent_provider: kong
permalink: /estates/kong/
slug: kong
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Kong
- API Gateway
- AI Gateway
- AI Connectivity
- Agent Gateway
- Event Gateway
- MCP Registry
- Service Mesh
- LLM
- Kafka
- Konnect
- Open Source
title: Kong
---
