---
api_total: 4
category: Estates
description: Uber is a global technology platform offering transportation, food delivery, and logistics
  services. Its developer platform provides APIs for integrating ride requests, food ordering, on-demand
  delivery, voucher programs, and business travel management into third-party applications. APIs use OAuth
  2.0 authentication with scope-based access controls and support both production and sandbox environments.
estate_rating:
  agent_avg: 16.7
  agent_band: emerging
  agent_native: 0
  agent_raw: 23.1
  agent_ready: 2
  band: emerging
  best: 55.2
  composite_avg: 26.5
  composite_band: thin
  composite_raw: 31.4
  developing: 0
  exemplar: 0
  rating: 22.6
  scored: 4
  spread: 45.8
  strength: 2
  strong: 1
  worst: 9.4
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/uber.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 33.7
    api_count: 2
    immediate_parent: uber
    name: Uber Eats
    relationship: product
    score_band: strong
    score_composite: 55.2
    slug: uber-eats
    source: declared
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 35.9
    api_count: 1
    immediate_parent: uber
    name: SpotHero
    relationship: product
    score_band: thin
    score_composite: 35.1
    slug: spothero
    source: parent-company-property
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 22.7
    api_count: 1
    immediate_parent: uber
    name: Uber Direct
    relationship: product
    score_band: emerging
    score_composite: 25.7
    slug: uber-direct
    source: declared
  label: Emerging
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
    immediate_parent: uber
    name: Careem
    relationship: product
    score_band: minimal
    score_composite: 9.4
    slug: careem
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
name: Uber
overview: 'Uber publishes its API surface across 4 provider profiles indexed on the APIs.io network, of
  which 4 carry a rating. The rated members span 45.8 points, from 55.2 down to 9.4.


  Its highest-rated surfaces are Uber Eats, SpotHero, Uber Direct, Careem.'
parent_provider: uber
permalink: /estates/uber/
slug: uber
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Ridesharing
- Rides
- Taxis
- Transportation
- Food Delivery
- Delivery
- Logistics
title: Uber
---
