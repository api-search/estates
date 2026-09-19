---
api_total: 2
category: Estates
description: Publicis Groupe is the French-headquartered global marketing, communications and business-transformation
  holding company behind Publicis Sapient, Publicis Media, Epsilon, CJ Affiliate, Leo Burnett, Saatchi
  & Saatchi, Digitas and Razorfish. The Groupe itself runs no public developer program and publishes no
  API at publicisgroupe.com; its machine-readable surface is produced by the operating units. The largest
  publicly readable one is the Publicis Sapient KnowHOW suite — an Apache-2.0 engineering-KPI platform
  (knowhow-api / knowhow-ui / knowhow-common / knowhow-processors on GitHub, container psknowhow/knowhow-api
  on Docker Hub) whose Spring Boot service self-documents an OpenAPI at /api/v3/api-docs on whatever host
  an operator deploys it to, plus knowhow-mcp, a self-hosted MCP server exposing the KnowHOW documentation
  assistant. Alongside it Publicis Sapient publishes the @psnext npm scope — the sling CLI for the Sapient
  Slingshot enterprise LLM gateway, the lscg local source-context-graph CLI and stdio MCP server, and
  the Block SDK for building iframe Blocks on Publicis Groupe's CoreAI platform. Epsilon and CJ Affiliate,
  which do publish hosted API contracts, are profiled in their own API Evangelist repositories.
estate_rating:
  agent_avg: 8.2
  agent_band: minimal
  agent_native: 0
  agent_raw: 3.5
  agent_ready: 0
  band: emerging
  best: 26.7
  composite_avg: 20.4
  composite_band: emerging
  composite_raw: 17.0
  developing: 0
  exemplar: 0
  rating: 15.5
  scored: 3
  spread: 16.5
  strength: 0
  strong: 0
  worst: 10.2
estate_root: null
estate_root_name: null
image: https://www.publicisgroupe.com/themes/custom/publicis/front/src/images/theme/share.jpg
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 7.9
    api_count: 2
    immediate_parent: publicis-groupe
    name: Lotame Solutions
    relationship: product
    score_band: thin
    score_composite: 26.7
    slug: lotame-solutions
    source: prose
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: publicis-groupe
    name: Yieldify *
    relationship: product
    score_band: emerging
    score_composite: 14.1
    slug: yieldify
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 0
    immediate_parent: publicis-groupe
    name: Profitero
    relationship: product
    score_band: minimal
    score_composite: 10.2
    slug: profitero
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
name: Publicis Groupe
overview: 'Publicis Groupe publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 16.5 points, from 26.7 down to 10.2.


  Its highest-rated surfaces are Lotame Solutions, Yieldify *, Profitero.'
parent_provider: publicis-groupe
permalink: /estates/publicis-groupe/
slug: publicis-groupe
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/publicis-groupe/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Company
- Advertising
- Marketing
- Media
- Digital Transformation
- Consulting
- Artificial Intelligence
- Developer Tools
- Engineering Metrics
- Open-Source
- MCP
- Agency Holding Company
title: Publicis Groupe
---
