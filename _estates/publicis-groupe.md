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
  agent_avg: 7.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 3.5
  agent_ready: 0
  band: emerging
  best: 28.5
  composite_avg: 19.3
  composite_band: emerging
  composite_raw: 17.3
  developing: 0
  exemplar: 0
  rating: 14.7
  scored: 3
  spread: 19.4
  strength: 0
  strong: 0
  worst: 9.1
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
    relationship: acquisition
    score_band: thin
    score_composite: 28.5
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
    relationship: acquisition
    score_band: emerging
    score_composite: 14.4
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
    relationship: acquisition
    score_band: minimal
    score_composite: 9.1
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
  network, of which 3 carry a rating. The rated members span 19.4 points, from 28.5 down to 9.1.


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
- Open Source
- MCP
- Agency Holding Company
title: Publicis Groupe
---
