---
api_total: 1
category: Estates
description: 'Proofpoint is an enterprise cybersecurity company focused on human-centric security — email
  and collaboration security, data loss prevention, insider threat management, digital communications
  governance, security awareness training and threat intelligence. Its public API surface is substantial
  but gateway-shaped rather than developer-portal-shaped: the Targeted Attack Protection (TAP) v2 API,
  the Threat Protection dashboard Reports API, the Emerging Threats (ET) Intelligence Query API, the ZenGuide
  / Security Awareness Training Results API, the Secure Email Relay email submission API, the Proofpoint
  Essentials SIEM API and the Proofpoint on Demand (PoD) log stream. Every one of them is documented in
  public HTML and every one of them is credential-gated at runtime; Proofpoint publishes no OpenAPI, AsyncAPI,
  GraphQL or MCP contract for any of them.'
estate_rating:
  agent_avg: 9.3
  agent_band: minimal
  agent_native: 0
  agent_raw: 6.5
  agent_ready: 0
  band: emerging
  best: 31.7
  composite_avg: 18.5
  composite_band: emerging
  composite_raw: 13.2
  developing: 0
  exemplar: 0
  rating: 14.8
  scored: 4
  spread: 26.7
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-productions2.s3.amazonaws.com/api-evangelist-site/company-logos/proofpoint.png
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
    agent_score: 26.1
    api_count: 1
    immediate_parent: proofpoint
    name: Tessian
    relationship: product
    score_band: thin
    score_composite: 31.7
    slug: tessian
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
    immediate_parent: proofpoint
    name: ObserveIT (Proofpoint)
    relationship: acquisition
    score_band: emerging
    score_composite: 11.1
    slug: observeit-proofpoint
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: proofpoint
    name: Illusive Networks
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: illusive-networks
    source: declared
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: proofpoint
    name: Normalyze
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: normalyze
    source: prose
  label: Minimal
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Proofpoint
overview: 'Proofpoint publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 26.7 points, from 31.7 down to 5.0.


  Its highest-rated surfaces are Tessian, ObserveIT (Proofpoint), Illusive Networks, Normalyze.'
parent_provider: proofpoint
permalink: /estates/proofpoint/
slug: proofpoint
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/proofpoint/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Security
- Cybersecurity
- Email Security
- Threat Intelligence
- Data Loss Prevention
- Security Awareness Training
- Insider Threat
- SIEM
- Compliance
- Email
title: Proofpoint
---
