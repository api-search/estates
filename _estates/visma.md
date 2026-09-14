---
api_total: 3
category: Estates
description: 'Visma is a Nordic business-software group headquartered in Oslo, Norway, supplying cloud
  ERP, accounting, invoicing, payroll, HR and public-sector software to more than a million customers
  across Europe and Latin America. Its developer surface is federated across product lines rather than
  centralised: Visma.net ERP publishes a 511-operation OpenAPI 3.0 contract at api.finance.visma.net in
  service (client-credentials) and interactive (authorization-code) flavours; Bookkeeping & Invoicing/eAccounting
  and Cloud Payroll (Spiris, formerly Visma Spcs) publish OpenAPI 3.0 contracts at eaccountingapi.vismaonline.com
  and vlsapi.vismaonline.com; and Business NXT exposes a GraphQL API at business.visma.net. Identity is
  centralised on Visma Connect (connect.visma.com), an OpenID Connect provider advertising 129 scopes,
  with a second IdentityServer at identity.vismaonline.com for the Spiris product line. Visma ships two
  first-party remote MCP servers — Business NXT at mcp.business.visma.net and Spiris at mcp.spiris.se
  — both OAuth-protected and discoverable via RFC 9728.'
estate_rating:
  agent_avg: 14.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 19.1
  agent_ready: 1
  band: emerging
  best: 50.1
  composite_avg: 24.8
  composite_band: emerging
  composite_raw: 29.3
  developing: 1
  exemplar: 0
  rating: 20.5
  scored: 3
  spread: 45.1
  strength: 1
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 33.6
    api_count: 2
    immediate_parent: visma
    name: Bokio
    relationship: product
    score_band: developing
    score_composite: 50.1
    slug: bokio
    source: x-parent-company
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 23.6
    api_count: 1
    immediate_parent: visma
    name: Silverfin
    relationship: product
    score_band: thin
    score_composite: 32.9
    slug: silverfin
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: visma
    name: Mamut
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: mamut
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
name: Visma
overview: 'Visma publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 45.1 points, from 50.1 down to 5.0.


  Its highest-rated surfaces are Bokio, Silverfin, Mamut.'
parent_provider: visma
permalink: /estates/visma/
slug: visma
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/visma/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Accounting
- Business-Software
- ERP
- Enterprise
- Financial-Services
- Human-Resources
- Invoicing
- Nordic
- Payroll
- SaaS
title: Visma
---
