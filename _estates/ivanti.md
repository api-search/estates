---
api_total: 3
category: Estates
description: Ivanti is an IT asset management and security platform providing unified endpoint management,
  patch management, and IT service management. The Ivanti Neurons product family exposes REST APIs across
  People & Devices, MDM, ITSM, and Zero-Trust Access, alongside Endpoint Manager APIs for patch and software
  distribution.
estate_rating:
  agent_avg: 7.6
  agent_band: minimal
  agent_native: 0
  agent_raw: 2.6
  agent_ready: 0
  band: emerging
  best: 40.0
  composite_avg: 19.0
  composite_band: emerging
  composite_raw: 16.5
  developing: 1
  exemplar: 0
  rating: 14.4
  scored: 3
  spread: 36.6
  strength: 1
  strong: 0
  worst: 3.4
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ivanti.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
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
    score_band: developing
    score_composite: 40.0
    slug: pulse
    source: declared
  label: Developing
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
    relationship: acquisition
    score_band: minimal
    score_composite: 6.2
    slug: mobileiron
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: ivanti
    name: Cherwell Software
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
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
  of which 3 carry a rating. The rated members span 36.6 points, from 40.0 down to 3.4.


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
