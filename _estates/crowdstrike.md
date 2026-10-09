---
api_total: 2
category: Estates
description: 'CrowdStrike is a US cybersecurity company and Fortune 1000 constituent whose Falcon platform
  delivers endpoint, cloud, identity and data protection from a single cloud-native agent. Its developer
  surface is substantial and public: a 1,463-operation OAuth2 REST API spanning 128 service collections,
  documented operation by operation on developer.crowdstrike.com, with 187 named permission scopes; six
  official SDKs (Python, PowerShell, Go, TypeScript/JavaScript, Rust, Ruby); a Terraform provider for
  Configuration as Code; Falcon Foundry, an app platform with its own CLI; a first-party open-source MCP
  server (falcon-mcp) exposing 166 agent tools across 28 modules; and a published set of Agent Skills
  for building Foundry apps. CrowdStrike does not publish an OpenAPI document, and API access requires
  a Falcon subscription — the API itself is included in every paid bundle.'
estate_rating:
  agent_avg: 8.2
  agent_band: minimal
  agent_native: 0
  agent_raw: 2.5
  agent_ready: 0
  band: emerging
  best: 29.9
  composite_avg: 21.0
  composite_band: emerging
  composite_raw: 22.5
  developing: 0
  exemplar: 0
  rating: 15.9
  scored: 2
  spread: 14.8
  strength: 0
  strong: 0
  worst: 15.1
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/crowdstrike.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: 2024
    agent_band: human-only
    agent_score: 5.0
    api_count: 1
    api_count_basis: split
    immediate_parent: crowdstrike
    name: Adaptive Shield
    relationship: acquisition
    score_band: thin
    score_composite: 29.9
    slug: adaptive-shield
    source: declared
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
    api_count: 1
    api_count_basis: split
    immediate_parent: crowdstrike
    name: Humio
    relationship: product
    score_band: emerging
    score_composite: 15.1
    slug: humio
    source: parent-company-property
  label: Emerging
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: crowdstrike
    name: Bionic Stork
    relationship: product
    score_band: null
    score_composite: null
    slug: bionic-stork
    source: parent-company-property
  label: Unrated
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: CrowdStrike
overview: 'CrowdStrike publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 14.8 points, from 29.9 down to 15.1.


  Its highest-rated surfaces are Adaptive Shield, Humio, Bionic Stork.'
parent_provider: crowdstrike
permalink: /estates/crowdstrike/
slug: crowdstrike
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/crowdstrike/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Cybersecurity
- Endpoint Security
- EDR
- Threat Intelligence
- Cloud Security
- Identity Protection
- Vulnerability Management
- SIEM
- Security Operations
- MCP
title: CrowdStrike
---
