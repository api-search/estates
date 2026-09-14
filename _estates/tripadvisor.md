---
api_total: 4
category: Estates
description: Tripadvisor is the world's largest travel guidance platform, helping hundreds of millions
  of travelers each month find places to stay, things to do, and restaurants through reviews, photos,
  and tools. The platform maintains over 7.5 million locations and 1 billion reviews across 43 markets
  and 29 languages. Tripadvisor provides APIs for content integration, hotel connectivity, and restaurant
  reservations.
estate_rating:
  agent_avg: 14.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 18.7
  agent_ready: 1
  band: emerging
  best: 42.1
  composite_avg: 22.3
  composite_band: emerging
  composite_raw: 22.5
  developing: 1
  exemplar: 0
  rating: 19.1
  scored: 4
  spread: 37.1
  strength: 1
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/tripadvisor.png
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
    agent_score: 47.2
    api_count: 2
    immediate_parent: tripadvisor
    name: LaFourchette
    relationship: product
    score_band: developing
    score_composite: 42.1
    slug: lafourchette
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 27.7
    api_count: 2
    immediate_parent: tripadvisor
    name: TheFork
    relationship: product
    score_band: thin
    score_composite: 37.7
    slug: thefork
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: tripadvisor
    name: HouseTrip
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: housetrip
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: tripadvisor
    name: Oyster.com (TripAdvisor)
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: oystercom-tripadvisor
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: tripadvisor
    name: Restorando
    relationship: product
    score_band: null
    score_composite: null
    slug: restorando
    source: prose
  label: Unrated
  open: false
member_on_network: 5
member_total: 5
members:
- *id001
- *id002
- *id003
- *id004
- *id005
members_unrated: []
name: Tripadvisor
overview: 'Tripadvisor publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 37.1 points, from 42.1 down to 5.0.


  Its highest-rated surfaces are LaFourchette, TheFork, HouseTrip, Oyster.com (TripAdvisor), Restorando.'
parent_provider: tripadvisor
permalink: /estates/tripadvisor/
slug: tripadvisor
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Attractions
- Hotels
- Hospitality
- Restaurant
- Reviews
- Travel
title: Tripadvisor
---
