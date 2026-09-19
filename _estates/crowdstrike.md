---
api_total: 2
category: Estates
description: CrowdStrike is a major US corporation and Fortune 1000 company. The CrowdStrike API provides
  programmatic access to its platform services, data, and integrations for enterprise customers and partners.
estate_rating:
  agent_avg: 7.5
  agent_band: minimal
  agent_native: 0
  agent_raw: 1.7
  agent_ready: 0
  band: emerging
  best: 27.2
  composite_avg: 20.0
  composite_band: emerging
  composite_raw: 16.1
  developing: 0
  exemplar: 0
  rating: 15.0
  scored: 3
  spread: 22.2
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/crowdstrike.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: 2024
    agent_band: human-only
    agent_score: 5.0
    api_count: 1
    immediate_parent: crowdstrike
    name: Adaptive Shield
    relationship: acquisition
    score_band: thin
    score_composite: 27.2
    slug: adaptive-shield
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: crowdstrike
    name: Humio
    relationship: product
    score_band: emerging
    score_composite: 16.0
    slug: humio
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: crowdstrike
    name: Bionic Stork
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: bionic-stork
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
name: CrowdStrike
overview: 'CrowdStrike publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 22.2 points, from 27.2 down to 5.0.


  Its highest-rated surfaces are Adaptive Shield, Humio, Bionic Stork.'
parent_provider: crowdstrike
permalink: /estates/crowdstrike/
slug: crowdstrike
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/crowdstrike/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Cybersecurity
- Endpoint Security
title: CrowdStrike
---
