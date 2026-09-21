---
api_total: 0
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
  agent_avg: 7.3
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 17.6
  composite_avg: 17.1
  composite_band: emerging
  composite_raw: 7.7
  developing: 0
  exemplar: 0
  rating: 13.2
  scored: 3
  spread: 17.0
  strength: 0
  strong: 0
  worst: 0.6
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/nokia-corp.png
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nokia-corp
    name: Infinera
    relationship: product
    score_band: emerging
    score_composite: 17.6
    slug: infinera
    source: prose
  label: Emerging
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
    immediate_parent: nokia-corp
    name: Luminous Computing
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: luminous-computing
    source: parent-company-property
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nokia-corp
    name: Gainspeed
    relationship: product
    score_band: minimal
    score_composite: 0.6
    slug: gainspeed
    source: parent-company-property
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: nokia-corp
    name: Network Alchemy
    relationship: product
    score_band: null
    score_composite: null
    slug: network-alchemy
    source: prose
  label: Unrated
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Nokia
overview: 'Nokia publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 17.0 points, from 17.6 down to 0.6.


  Its highest-rated surfaces are Infinera, Luminous Computing, Gainspeed, Network Alchemy.'
parent_provider: nokia-corp
permalink: /estates/nokia-corp/
slug: nokia-corp
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nokia-corp/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Telecommunications
- Telecom
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
title: Nokia
---
