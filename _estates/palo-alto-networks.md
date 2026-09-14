---
api_total: 4
category: Estates
description: Palo Alto Networks is a global cybersecurity leader providing advanced security platforms
  and services across network security, cloud security, and security operations. Its developer platform
  at pan.dev offers REST and XML APIs for PAN-OS firewalls, Strata Cloud Manager, Prisma Cloud (CSPM,
  CWPP, code security), Prisma Access and SD-WAN for SASE, Cortex XDR/XSOAR/XSIAM for security operations,
  and cloud-delivered security services including WildFire, Threat Vault, IoT Security, and DLP.
estate_rating:
  agent_avg: 10.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.1
  agent_ready: 0
  band: emerging
  best: 37.5
  composite_avg: 19.4
  composite_band: emerging
  composite_raw: 17.8
  developing: 0
  exemplar: 0
  rating: 15.8
  scored: 9
  spread: 32.5
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/palo-alto-networks.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 21.0
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Demisto
    relationship: product
    score_band: thin
    score_composite: 37.5
    slug: demisto
    source: prose
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 27.2
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Koi Security
    relationship: product
    score_band: thin
    score_composite: 35.0
    slug: koi-security
    source: prose
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Prisma Cloud
    relationship: product
    score_band: thin
    score_composite: 33.3
    slug: prisma-cloud
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Panorama
    relationship: product
    score_band: emerging
    score_composite: 24.1
    slug: panorama
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 5
  items:
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Prosimo
    relationship: product
    score_band: minimal
    score_composite: 10.6
    slug: prosimo
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Aporeto
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: aporeto
    source: prose
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Cyvera
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: cyvera
    source: prose
  - &id008
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Expanse
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: expanse
    source: prose
  - &id009
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Talon
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: talon
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id010
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Morta Security
    relationship: product
    score_band: null
    score_composite: null
    slug: morta-security
    source: prose
  label: Unrated
  open: false
member_on_network: 10
member_total: 10
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
- *id009
- *id010
members_unrated: []
name: Palo Alto Networks
overview: 'Palo Alto Networks publishes its API surface across 10 provider profiles indexed on the APIs.io
  network, of which 10 carry a rating. The rated members span 32.5 points, from 37.5 down to 5.0.


  Its highest-rated surfaces are Demisto, Koi Security, Prisma Cloud, Panorama, Prosimo.'
parent_provider: palo-alto-networks
permalink: /estates/palo-alto-networks/
slug: palo-alto-networks
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
title: Palo Alto Networks
---
