---
api_total: 2
category: Estates
description: Verizon is a leading telecommunications company providing wireless, wireline, broadband,
  and global enterprise services. Verizon offers developer APIs for IoT device management via ThingSpace,
  5G edge computing, TM Forum service management, dynamic network bandwidth, and communications platform
  APIs for contact center and SMS solutions.
estate_rating:
  agent_avg: 8.5
  agent_band: minimal
  agent_native: 0
  agent_raw: 6.9
  agent_ready: 1
  band: emerging
  best: 45.6
  composite_avg: 17.2
  composite_band: emerging
  composite_raw: 14.6
  developing: 1
  exemplar: 0
  rating: 13.7
  scored: 6
  spread: 45.6
  strength: 1
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/verizon.png
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
    agent_score: 34.7
    api_count: 1
    api_count_basis: published
    immediate_parent: verizon
    name: AOL
    relationship: acquisition
    score_band: developing
    score_composite: 45.6
    slug: aol
    source: prose
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 4.3
    api_count: 1
    api_count_basis: published
    immediate_parent: aol
    name: TechCrunch
    relationship: product
    score_band: emerging
    score_composite: 21.8
    slug: techcrunch
    source: parent-company-property
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 0
    api_count_basis: split
    immediate_parent: verizon
    name: Starry
    relationship: acquisition
    score_band: emerging
    score_composite: 20.0
    slug: starry
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: verizon
    name: CloudSwitch
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: cloudswitch
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: aol
    name: Outside.in
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: outsidein
    source: parent-company-property
  - &id006
    acquired: 2010-09
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: aol
    name: Thing Labs
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: thing-labs
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 2
  items:
  - &id007
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: aol
    name: Convertro, Inc.
    relationship: product
    score_band: null
    score_composite: null
    slug: convertro-inc
    source: parent-company-property
  - &id008
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: verizon
    name: ProtectWise
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: protectwise
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
  of which 8 carry a rating. The rated members span 45.6 points, from 45.6 down to 0.0.


  Its highest-rated surfaces are AOL, TechCrunch, Starry, CloudSwitch, Outside.in.'
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
    score_band: emerging
    score_composite: 21.8
    slug: techcrunch
  - name: Outside.in
    score_band: minimal
    score_composite: 0.0
    slug: outsidein
  - name: Thing Labs
    score_band: minimal
    score_composite: 0.0
    slug: thing-labs
  - name: Convertro, Inc.
    score_band: null
    score_composite: null
    slug: convertro-inc
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
