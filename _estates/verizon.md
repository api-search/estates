---
api_total: 2
category: Estates
description: Verizon is a leading telecommunications company providing wireless, wireline, broadband,
  and global enterprise services. Verizon offers developer APIs for IoT device management via ThingSpace,
  5G edge computing, TM Forum service management, dynamic network bandwidth, and communications platform
  APIs for contact center and SMS solutions.
estate_rating:
  agent_avg: 11.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 11.4
  agent_ready: 1
  band: emerging
  best: 43.6
  composite_avg: 22.7
  composite_band: emerging
  composite_raw: 22.8
  developing: 2
  exemplar: 0
  rating: 18.2
  scored: 5
  spread: 38.8
  strength: 2
  strong: 0
  worst: 4.8
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/verizon.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 34.7
    api_count: 1
    immediate_parent: verizon
    name: AOL
    relationship: product
    score_band: developing
    score_composite: 43.6
    slug: aol
    source: prose
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 20.0
    api_count: 1
    immediate_parent: aol
    name: TechCrunch
    relationship: product
    score_band: developing
    score_composite: 40.5
    slug: techcrunch
    source: parent-company-property
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 0
    immediate_parent: verizon
    name: Starry
    relationship: product
    score_band: emerging
    score_composite: 19.9
    slug: starry
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: aol
    name: Convertro, Inc.
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: convertro-inc
    source: parent-company-property
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: verizon
    name: ProtectWise
    relationship: product
    score_band: minimal
    score_composite: 4.8
    slug: protectwise
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 3
  items:
  - &id006
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: verizon
    name: CloudSwitch
    relationship: product
    score_band: null
    score_composite: null
    slug: cloudswitch
    source: prose
  - &id007
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: aol
    name: Outside.in
    relationship: product
    score_band: null
    score_composite: null
    slug: outsidein
    source: parent-company-property
  - &id008
    acquired: 2010-09
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: aol
    name: Thing Labs
    relationship: product
    score_band: null
    score_composite: null
    slug: thing-labs
    source: prose
  label: Unrated
  open: false
member_on_network: 8
member_total: 8
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
members_unrated: []
name: Verizon
overview: 'Verizon publishes its API surface across 8 provider profiles indexed on the APIs.io network,
  of which 8 carry a rating. The rated members span 38.8 points, from 43.6 down to 4.8.


  Its highest-rated surfaces are AOL, TechCrunch, Starry, Convertro, Inc., ProtectWise.'
parent_provider: verizon
permalink: /estates/verizon/
slug: verizon
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/verizon/refs/heads/main/apis.yml
subfamilies:
- has_page: true
  member_count: 4
  members:
  - name: TechCrunch
    score_band: developing
    score_composite: 40.5
    slug: techcrunch
  - name: Convertro, Inc.
    score_band: minimal
    score_composite: 5.0
    slug: convertro-inc
  - name: Outside.in
    score_band: null
    score_composite: null
    slug: outsidein
  - name: Thing Labs
    score_band: null
    score_composite: null
    slug: thing-labs
  name: AOL
  on_network: true
  permalink: /estates/aol/
  slug: aol
subfamily_page_count: 1
tags:
- Wireless
- Telecommunications
- IoT
- 5G
- Enterprise
- Network APIs
- Fortune 100
title: Verizon
---
