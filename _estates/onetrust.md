---
api_total: 2
category: Estates
description: OneTrust is an enterprise trust, privacy, and AI-governance platform. Its developer portal
  publishes 37 downloadable OpenAPI definitions covering roughly 631 operations across Universal Consent
  & Preference Management, Cookie Consent / CMP, Consent Receipts, Data Subject Request (DSR) Automation,
  Assessment Automation (PIA/DPIA), Data Mapping, Data Catalog and Data Discovery, Incident Management,
  IT & Security Risk Management, Audit Management, Issues Management, Enterprise Policy Management, Compliance
  Automation, Third-Party Risk Management, ESG Program Reporting, AI Governance, and the shared platform
  services (Access Management, SCIM 2.0 User Provisioning, Object Manager, Inventory, Bulk Export, Documents,
  Integrations, Task Management, Global Activity). Every API is authorized with OAuth 2.0 client credentials
  against a per-tenant environment host, and the portal also serves an RFC 9727 /.well-known/api-catalog,
  an llms.txt, and a public remote MCP server.
estate_rating:
  agent_avg: 7.0
  agent_band: minimal
  agent_native: 0
  agent_raw: 1.0
  agent_ready: 0
  band: emerging
  best: 26.0
  composite_avg: 17.7
  composite_band: emerging
  composite_raw: 13.1
  developing: 0
  exemplar: 0
  rating: 13.4
  scored: 3
  spread: 23.5
  strength: 0
  strong: 0
  worst: 2.5
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/onetrust.png
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: onetrust
    name: Convercent
    relationship: acquisition
    score_band: emerging
    score_composite: 26.0
    slug: convercent
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.6
    api_count: 1
    immediate_parent: onetrust
    name: Tugboat Logic
    relationship: product
    score_band: minimal
    score_composite: 10.9
    slug: tugboat-logic
    source: declared
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: onetrust
    name: Planetly
    relationship: product
    score_band: minimal
    score_composite: 2.5
    slug: planetly
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: OneTrust
overview: 'OneTrust publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 23.5 points, from 26.0 down to 2.5.


  Its highest-rated surfaces are Convercent, Tugboat Logic, Planetly.'
parent_provider: onetrust
permalink: /estates/onetrust/
slug: onetrust
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/onetrust/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Privacy
- GRC
- Compliance
- Consent
- Third-Party Risk Management
- AI Governance
- Data Governance
- Risk Management
- Data Discovery
- ESG
- Security
- SCIM
title: OneTrust
---
