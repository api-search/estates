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
  agent_avg: 9.5
  agent_band: minimal
  agent_native: 0
  agent_raw: 7.7
  agent_ready: 0
  band: emerging
  best: 54.6
  composite_avg: 20.9
  composite_band: emerging
  composite_raw: 21.7
  developing: 0
  exemplar: 0
  rating: 16.3
  scored: 3
  spread: 50.9
  strength: 2
  strong: 1
  worst: 3.7
estate_root: null
estate_root_name: null
image: https://www.zoominfo.com/assets/img/zoominfo-logo.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 2
    immediate_parent: zoominfo
    name: Chorus.ai
    relationship: product
    score_band: strong
    score_composite: 54.6
    slug: chorus-ai
    source: parent-company-property
  label: Strong
  open: true
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
    relationship: acquisition
    score_band: minimal
    score_composite: 6.8
    slug: everstring
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: zoominfo
    name: Datanyze *
    relationship: acquisition
    score_band: minimal
    score_composite: 3.7
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
  of which 3 carry a rating. The rated members span 50.9 points, from 54.6 down to 3.7.


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
