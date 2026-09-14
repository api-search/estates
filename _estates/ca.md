---
api_total: 2
category: Estates
description: CA Technologies (originally Computer Associates) was a major enterprise software vendor focused
  on infrastructure management, DevOps, security, and mainframe software. It was acquired by Broadcom
  in November 2018 and its products are now part of Broadcom's Enterprise Software Division, including
  Layer 7 API Management, AppDynamics (later spun out to Cisco), DX Application Performance Management,
  Rally / Agile Central, Clarity PPM, BlazeMeter, AutoSys workload automation, and mainframe management
  suites. The primary developer portal is developer.broadcom.com.
estate_rating:
  agent_avg: 10.6
  agent_band: emerging
  agent_native: 0
  agent_raw: 9.8
  agent_ready: 0
  band: emerging
  best: 29.6
  composite_avg: 20.2
  composite_band: emerging
  composite_raw: 15.6
  developing: 0
  exemplar: 0
  rating: 16.4
  scored: 2
  spread: 28.1
  strength: 0
  strong: 0
  worst: 1.5
estate_root: broadcom
estate_root_name: Broadcom
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ca.png
is_subfamily: true
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: 2013
    agent_band: agent-aware
    agent_score: 19.6
    api_count: 2
    immediate_parent: ca
    name: Flowdock (Discontinued)
    relationship: acquisition
    score_band: thin
    score_composite: 29.6
    slug: flowdock
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id002
    acquired: 2010
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: ca
    name: Arcot Systems
    relationship: acquisition
    score_band: minimal
    score_composite: 1.5
    slug: arcot-systems
    source: declared
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: ca
    name: Concord Data Systems
    relationship: product
    score_band: null
    score_composite: null
    slug: concord-data-systems
    source: prose
  label: Unrated
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
  the APIs.io network, of which 3 carry a rating. The rated members span 28.1 points, from 29.6 down to
  1.5.


  Its highest-rated surfaces are Flowdock (Discontinued), Arcot Systems, Concord Data Systems.'
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
