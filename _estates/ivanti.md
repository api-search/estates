---
api_total: 3
category: Estates
description: Ivanti is an IT asset management and security platform providing unified endpoint management,
  patch management, and IT service management. The Ivanti Neurons product family exposes REST APIs across
  People & Devices, MDM, ITSM, and Zero-Trust Access, alongside Endpoint Manager APIs for patch and software
  distribution.
estate_rating:
  agent_avg: 7.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 2.6
  agent_ready: 0
  band: emerging
  best: 37.3
  composite_avg: 20.3
  composite_band: emerging
  composite_raw: 16.7
  developing: 0
  exemplar: 0
  rating: 15.3
  scored: 3
  spread: 32.3
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ivanti.png
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
    api_count: 3
    immediate_parent: ivanti
    name: Pulse
    relationship: product
    score_band: thin
    score_composite: 37.3
    slug: pulse
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: ivanti
    name: MobileIron
    relationship: product
    score_band: minimal
    score_composite: 7.9
    slug: mobileiron
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: ivanti
    name: Cherwell Software
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: cherwell-software
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
name: Ivanti
overview: 'Ivanti publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 32.3 points, from 37.3 down to 5.0.


  Its highest-rated surfaces are Pulse, MobileIron, Cherwell Software.'
parent_provider: ivanti
permalink: /estates/ivanti/
slug: ivanti
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ivanti/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Endpoint Management
- IT Asset Management
- ITSM
- Patch Management
- Mobile Device Management
- Zero Trust
title: Ivanti
---
