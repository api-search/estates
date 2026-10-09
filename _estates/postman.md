---
api_total: 19
category: Estates
description: Postman is the world's leading API platform, used by 35+ million developers to design, build,
  test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections,
  Workspaces, the API Client, Spec Hub, Mock Servers, Monitors, the Postman CLI, Newman, Flows, AI Agent
  Builder, the Postman MCP Server and MCP Generator, API Governance, the Private API Network, Live Collections,
  Insights, and a public Postman API Network with millions of public workspaces.
estate_rating:
  agent_avg: 9.8
  agent_band: minimal
  agent_native: 0
  agent_raw: 9.3
  agent_ready: 0
  band: emerging
  best: 47.6
  composite_avg: 20.3
  composite_band: emerging
  composite_raw: 20.3
  developing: 1
  exemplar: 0
  rating: 16.1
  scored: 6
  spread: 47.6
  strength: 1
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://www.postman.com/assets/logos/postman-logo-horizontal-orange.svg
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: 2025
    agent_band: agent-aware
    agent_score: 21.6
    api_count: 13
    api_count_basis: split
    immediate_parent: postman
    name: Liblab
    relationship: acquisition
    score_band: developing
    score_composite: 47.6
    slug: liblab
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id002
    acquired: 2023
    agent_band: agent-aware
    agent_score: 8.6
    api_count: 2
    api_count_basis: split
    immediate_parent: postman
    name: Akita Software
    relationship: acquisition
    score_band: thin
    score_composite: 27.5
    slug: akita-software
    source: declared
  - &id003
    acquired: 2026
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 1
    api_count_basis: published
    immediate_parent: postman
    name: Fern
    relationship: acquisition
    score_band: thin
    score_composite: 26.6
    slug: fern-api
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    api_count_basis: split
    immediate_parent: postman
    name: Newman
    relationship: product
    score_band: emerging
    score_composite: 15.1
    slug: newman
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    api_count_basis: split
    immediate_parent: postman
    name: Postman Echo
    relationship: product
    score_band: minimal
    score_composite: 5.1
    slug: postman-echo
    source: declared
  - &id006
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    api_count_basis: published
    immediate_parent: postman
    name: Orbit
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: orbit
    source: declared
  label: Minimal
  open: false
member_on_network: 6
member_total: 6
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
members_unrated: []
name: Postman
overview: 'Postman publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 47.6 points, from 47.6 down to 0.0.


  Its highest-rated surfaces are Liblab, Akita Software, Fern, Newman, Postman Echo.'
parent_provider: postman
permalink: /estates/postman/
slug: postman
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Environment
- Flow
- Specification
- Workspace
- Postman
- AI Agent Builder
- AI Agents
- API Catalog
- API Client
- API Design
- API Development
- API Documentation
title: Postman
---
