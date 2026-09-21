---
api_total: 5
category: Estates
description: OpenText Cybersecurity is the security business of OpenText, assembled from the Micro Focus
  security portfolio (Fortify application security, ArcSight threat detection and response, NetIQ identity
  and access management, Voltage data privacy) and the SMB/MSP brands OpenText acquired through Webroot,
  Carbonite and Zix — endpoint protection, DNS protection, EDR/MDR, email threat protection and encryption,
  security awareness training, backup and disaster recovery. Two product lines expose a public developer
  surface. OpenText Core Application Security (Fortify on Demand) publishes a live Swagger 2.0 contract
  with 159 operations across applications, releases, static/dynamic/mobile scans, vulnerabilities, reports
  and tenant administration, served per region from api.ams / api.emea / api.apac.fortify.com. The Webroot
  Unity API is the multi-tenant REST platform managed service providers use to run Secure Cloud sites,
  endpoints, policies, licensing and near-real-time event notifications. Fortify also ships a first-party
  CLI (fcli), a first-party MCP server inside that CLI, and a published set of Agent Skills for Claude
  Code, GitHub Copilot, Codex and Gemini CLI.
estate_rating:
  agent_avg: 11.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 11.2
  agent_ready: 0
  band: emerging
  best: 55.4
  composite_avg: 26.0
  composite_band: thin
  composite_raw: 30.0
  developing: 0
  exemplar: 0
  rating: 20.2
  scored: 4
  spread: 47.5
  strength: 2
  strong: 1
  worst: 7.9
estate_root: null
estate_root_name: null
image: https://cari01mstrop62eprod.dxcloud.episerver.net/globalassets/smb-media/images/banners/csot-homepage-hero-2.webp
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
    agent_score: 20.7
    api_count: 3
    immediate_parent: opentext-cybersecurity
    name: Fortify
    relationship: product
    score_band: strong
    score_composite: 55.4
    slug: fortify
    source: declared
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    immediate_parent: opentext-cybersecurity
    name: CloudAlly
    relationship: acquisition
    score_band: thin
    score_composite: 32.4
    slug: cloudally
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: opentext-cybersecurity
    name: Webroot
    relationship: product
    score_band: emerging
    score_composite: 24.4
    slug: webroot
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: opentext-cybersecurity
    name: ArcSight
    relationship: acquisition
    score_band: minimal
    score_composite: 7.9
    slug: arcsight
    source: declared
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
name: OpenText Cybersecurity
overview: 'OpenText Cybersecurity publishes its API surface across 4 provider profiles indexed on the
  APIs.io network, of which 4 carry a rating. The rated members span 47.5 points, from 55.4 down to 7.9.


  Its highest-rated surfaces are Fortify, CloudAlly, Webroot, ArcSight.'
parent_provider: opentext-cybersecurity
permalink: /estates/opentext-cybersecurity/
slug: opentext-cybersecurity
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/opentext-cybersecurity/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Cybersecurity
- Application Security
- Vulnerability Management
- SAST
- DAST
- Endpoint Security
- Threat Detection
- Email Security
- Backup and Recovery
- Managed Service Providers
- Identity and Access
- Data Privacy
title: OpenText Cybersecurity
---
