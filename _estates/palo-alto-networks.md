---
api_total: 9
category: Estates
description: Palo Alto Networks is a global cybersecurity leader providing advanced security platforms
  and services across network security, cloud security, and security operations. Its developer platform
  at pan.dev offers REST and XML APIs for PAN-OS firewalls, Strata Cloud Manager, Prisma Cloud (CSPM,
  CWPP, code security), Prisma Access and SD-WAN for SASE, Cortex XDR/XSOAR/XSIAM for security operations,
  and cloud-delivered security services including WildFire, Threat Vault, IoT Security, and DLP.
estate_rating:
  agent_avg: 13.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 15.8
  agent_ready: 1
  band: emerging
  best: 43.1
  composite_avg: 22.4
  composite_band: emerging
  composite_raw: 23.4
  developing: 1
  exemplar: 0
  rating: 19.0
  scored: 9
  spread: 43.1
  strength: 1
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/palo-alto-networks.png
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
    agent_score: 33.2
    api_count: 4
    immediate_parent: palo-alto-networks
    name: Venafi
    relationship: product
    score_band: developing
    score_composite: 43.1
    slug: venafi
    source: parent-company-property
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 4
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 18.9
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Demisto
    relationship: product
    score_band: thin
    score_composite: 36.2
    slug: demisto
    source: parent-company-property
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 27.2
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Koi Security
    relationship: product
    score_band: thin
    score_composite: 34.8
    slug: koi-security
    source: parent-company-property
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 22.9
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Prisma Cloud
    relationship: product
    score_band: thin
    score_composite: 31.0
    slug: prisma-cloud
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Protect AI
    relationship: product
    score_band: thin
    score_composite: 30.0
    slug: protectai
    source: parent-company-property
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: palo-alto-networks
    name: Panorama
    relationship: product
    score_band: emerging
    score_composite: 22.9
    slug: panorama
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Prosimo
    relationship: product
    score_band: minimal
    score_composite: 9.5
    slug: prosimo
    source: parent-company-property
  - &id008
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Expanse
    relationship: product
    score_band: minimal
    score_composite: 3.4
    slug: expanse
    source: parent-company-property
  - &id009
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Morta Security
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: morta-security
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 3
  items:
  - &id010
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Aporeto
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: aporeto
    source: prose
  - &id011
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Cyvera
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: cyvera
    source: prose
  - &id012
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: palo-alto-networks
    name: Talon
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: talon
    source: prose
  label: Unrated
  open: false
member_on_network: 12
member_total: 12
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
- *id011
- *id012
members_unrated: []
name: Palo Alto Networks
overview: 'Palo Alto Networks publishes its API surface across 12 provider profiles indexed on the APIs.io
  network, of which 12 carry a rating. The rated members span 43.1 points, from 43.1 down to 0.0.


  Its highest-rated surfaces are Venafi, Demisto, Koi Security, Prisma Cloud, Protect AI.'
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
