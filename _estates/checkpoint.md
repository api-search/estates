---
api_total: 48
category: Estates
description: Check Point Software Technologies is a global cybersecurity vendor providing network, cloud,
  endpoint, mobile, and email security through its Quantum, CloudGuard, and Harmony product families.
  Check Point exposes a wide range of REST APIs for security automation, including the Smart-1 Management
  API, Gaia OS API, CloudGuard cloud security posture API, Identity Awareness API, Spark and Zero Touch
  device management APIs, Harmony Email and Collaboration API, Threat Hunting (TH) API, and CloudGuard
  WAF API.
estate_rating:
  agent_avg: 15.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 21.9
  agent_ready: 1
  band: emerging
  best: 53.2
  composite_avg: 26.9
  composite_band: thin
  composite_raw: 32.4
  developing: 2
  exemplar: 0
  rating: 22.5
  scored: 4
  spread: 48.2
  strength: 2
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/checkpoint.png
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
    agent_score: 33.5
    api_count: 46
    immediate_parent: checkpoint
    name: CloudGuard
    relationship: product
    score_band: developing
    score_composite: 53.2
    slug: cloudguard
    source: declared
  - &id002
    acquired: 2018
    agent_band: agent-aware
    agent_score: 28.2
    api_count: 1
    immediate_parent: checkpoint
    name: Dome9
    relationship: acquisition
    score_band: developing
    score_composite: 41.3
    slug: dome9
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 26.1
    api_count: 1
    immediate_parent: checkpoint
    name: Perimeter 81
    relationship: product
    score_band: thin
    score_composite: 30.1
    slug: perimeter-81
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: checkpoint
    name: Veriti.ai
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: veritiai
    source: prose
  label: Minimal
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Check Point
overview: 'Check Point publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 48.2 points, from 53.2 down to 5.0.


  Its highest-rated surfaces are CloudGuard, Dome9, Perimeter 81, Veriti.ai.'
parent_provider: checkpoint
permalink: /estates/checkpoint/
slug: checkpoint
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Cloud Security
- Cybersecurity
- Endpoint Security
- Firewall
- Identity Awareness
- Mobile Security
- Network Security
- Security
- Threat Prevention
- WAF
title: Check Point
---
