---
api_total: 3
category: Estates
description: CA Technologies (originally Computer Associates) was a major enterprise software vendor focused
  on infrastructure management, DevOps, security, and mainframe software. It was acquired by Broadcom
  in November 2018 and its products are now part of Broadcom's Enterprise Software Division, including
  Layer 7 API Management, AppDynamics (later spun out to Cisco), DX Application Performance Management,
  Rally / Agile Central, Clarity PPM, BlazeMeter, AutoSys workload automation, and mainframe management
  suites. The primary developer portal is developer.broadcom.com.
estate_rating:
  agent_avg: 6.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.8
  agent_ready: 0
  band: emerging
  best: 19.2
  composite_avg: 15.5
  composite_band: emerging
  composite_raw: 7.3
  developing: 0
  exemplar: 0
  rating: 12.1
  scored: 3
  spread: 19.2
  strength: 0
  strong: 0
  worst: 0.0
estate_root: broadcom
estate_root_name: Broadcom
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ca.png
is_subfamily: true
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    api_count_basis: split
    immediate_parent: ca
    name: Runscope
    relationship: acquisition
    score_band: emerging
    score_composite: 19.2
    slug: runscope
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: 2010
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: ca
    name: Arcot Systems
    relationship: acquisition
    score_band: minimal
    score_composite: 2.7
    slug: arcot-systems
    source: declared
  - &id003
    acquired: 2013
    agent_band: human-only
    agent_score: 0.0
    api_count: 2
    api_count_basis: published
    immediate_parent: ca
    name: Flowdock (Discontinued)
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: flowdock
    source: declared
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: CA Technologies (Broadcom)
overview: 'CA Technologies (Broadcom) publishes its API surface across 3 provider profiles indexed on
  the APIs.io network, of which 3 carry a rating. The rated members span 19.2 points, from 19.2 down to
  0.0.


  Its highest-rated surfaces are Runscope, Arcot Systems, Flowdock (Discontinued).'
parent_provider: ca
permalink: /estates/ca/
slug: ca
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ca/refs/heads/main/apis.yml
subfamilies: []
tags:
- API Management
- Application Performance
- DevOps
- Enterprise Software
- Infrastructure
- Mainframe
- Monitoring
- Security
- Fortune 1000
title: CA Technologies (Broadcom)
---
