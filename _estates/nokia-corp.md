---
api_total: 8
category: Estates
description: Nokia (Nokia Oyj) is a Finnish multinational telecommunications, information technology,
  and consumer electronics corporation headquartered in Espoo, Finland. Nokia is a leading vendor of carrier-grade
  network equipment for communication service providers (CSPs), webscalers, and enterprises across mobile
  (5G/6G RAN, Core), fixed (broadband, fiber), IP (Service Router OS / SR Linux), optical (WaveSuite,
  1830 PSS/PSI), submarine cable, and cloud and network services. Nokia's developer surface spans (1)
  the Network Services Platform (NSP) automation suite, (2) the SR OS / SR Linux network operating systems
  with the pySROS SDK and YANG models for the 7x50 platform, (3) WaveSuite optical management REST APIs
  with Swagger documentation, (4) the CAMARA-compliant Network as Code platform exposing 16+ standardized
  network APIs (Quality on Demand, Device Location, SIM Swap, Number Verification, KYC, Geofencing, Slicing)
  for B2B and B2C developer consumption, and (5) the Network Exposure Platform that enables operators
  to expose their own network capabilities to developers. Nokia also operates Nokia Technologies (licensing),
  the Bell Labs research division, and a broad open-source presence (600+ GitHub repos) including TTCN-3
  tooling (ntt), Corteca CLI, Moler test framework, and YANG models.
estate_rating:
  agent_avg: 8.7
  agent_band: minimal
  agent_native: 0
  agent_raw: 7.2
  agent_ready: 0
  band: emerging
  best: 41.7
  composite_avg: 17.7
  composite_band: emerging
  composite_raw: 15.4
  developing: 1
  exemplar: 0
  rating: 14.1
  scored: 6
  spread: 41.7
  strength: 1
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/nokia-corp.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: 2024
    agent_band: agent-aware
    agent_score: 20.8
    api_count: 6
    api_count_basis: published
    immediate_parent: nokia-corp
    name: RapidAPI
    relationship: acquisition
    score_band: developing
    score_composite: 41.7
    slug: rapidapi
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 1
    api_count_basis: published
    immediate_parent: nokia-corp
    name: Nokia NetAct
    relationship: product
    score_band: thin
    score_composite: 31.0
    slug: nokia-netact
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: 2025
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: nokia-corp
    name: Infinera
    relationship: acquisition
    score_band: emerging
    score_composite: 17.2
    slug: infinera
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id004
    acquired: 2016
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: nokia-corp
    name: Alcatel-lucent
    relationship: acquisition
    score_band: minimal
    score_composite: 2.5
    slug: alcatel-lucent
    source: declared
  - &id005
    acquired: 2000
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: nokia-corp
    name: Network Alchemy
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: network-alchemy
    source: declared
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    api_count_basis: split
    immediate_parent: alcatel-lucent
    name: ProgrammableWeb
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: programmableweb
    source: parent-company-property
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id007
    acquired: 2016
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: nokia-corp
    name: Gainspeed
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: gainspeed
    source: declared
  label: Unrated
  open: false
member_on_network: 7
member_total: 7
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
members_unrated: []
name: Nokia
overview: 'Nokia publishes its API surface across 7 provider profiles indexed on the APIs.io network,
  of which 7 carry a rating. The rated members span 41.7 points, from 41.7 down to 0.0.


  Its highest-rated surfaces are RapidAPI, Nokia NetAct, Infinera, Alcatel-lucent, Network Alchemy.'
parent_provider: nokia-corp
permalink: /estates/nokia-corp/
slug: nokia-corp
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nokia-corp/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: ProgrammableWeb
    score_band: minimal
    score_composite: 0.0
    slug: programmableweb
  name: Alcatel-lucent
  on_network: true
  permalink: /estates/alcatel-lucent/
  slug: alcatel-lucent
subfamily_page_count: 0
tags:
- Telecommunications
- 5G
- 6G
- Mobile Network
- Network Infrastructure
- IP Networks
- Optical Networks
- Fixed Networks
- Broadband
- Service Router
- SR OS
- SR Linux
title: Nokia
---
