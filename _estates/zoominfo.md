---
api_total: 3
category: Estates
description: 'ZoomInfo is a B2B go-to-market intelligence platform whose contact and company database,
  buyer-intent signals, scoops and news feeds are sold to sales, marketing, operations and recruiting
  teams. Its API estate is mid-migration: the legacy Enterprise API on api.zoominfo.com is documented
  as deprecating, while the current GTM API on api.zoominfo.com/gtm ships six published OpenAPI specifications
  covering data, Copilot, GTM Studio, marketing, agents and platform. ZoomInfo also operates a hosted,
  OAuth-gated Model Context Protocol server at mcp.zoominfo.com and publishes 35 agent skills and a first-party
  CLI that talks to that MCP server rather than to REST.'
estate_rating:
  agent_avg: 10.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 8.5
  agent_ready: 0
  band: emerging
  best: 53.2
  composite_avg: 22.4
  composite_band: emerging
  composite_raw: 22.4
  developing: 1
  exemplar: 0
  rating: 17.5
  scored: 3
  spread: 47.9
  strength: 1
  strong: 0
  worst: 5.3
estate_root: null
estate_root_name: null
image: https://www.zoominfo.com/assets/img/zoominfo-logo.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 25.4
    api_count: 2
    immediate_parent: zoominfo
    name: Chorus.ai
    relationship: product
    score_band: developing
    score_composite: 53.2
    slug: chorus-ai
    source: prose
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: zoominfo
    name: Everstring
    relationship: product
    score_band: minimal
    score_composite: 8.6
    slug: everstring
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: zoominfo
    name: Datanyze *
    relationship: product
    score_band: minimal
    score_composite: 5.3
    slug: datanyze
    source: prose
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: ZoomInfo
overview: 'ZoomInfo publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 47.9 points, from 53.2 down to 5.3.


  Its highest-rated surfaces are Chorus.ai, Everstring, Datanyze *.'
parent_provider: zoominfo
permalink: /estates/zoominfo/
slug: zoominfo
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zoominfo/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- B2B
- B2B Data
- Company Data
- Contact Database
- Contacts
- Data
- Lead Generation
- Marketing Intelligence
- Sales Intelligence
- Intent Data
- Go-To-Market
- Data Enrichment
title: ZoomInfo
---
