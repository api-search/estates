---
api_total: 7
category: Estates
description: Tripadvisor is the world's largest travel guidance platform, helping hundreds of millions
  of travelers each month find places to stay, things to do, and restaurants through reviews, photos,
  and tools. The platform maintains over 7.5 million locations and 1 billion reviews across 43 markets
  and 29 languages. Tripadvisor provides APIs for content integration, hotel connectivity, and restaurant
  reservations.
estate_rating:
  agent_avg: 8.3
  agent_band: minimal
  agent_native: 0
  agent_raw: 6.1
  agent_ready: 1
  band: emerging
  best: 46.5
  composite_avg: 15.3
  composite_band: emerging
  composite_raw: 10.3
  developing: 1
  exemplar: 0
  rating: 12.5
  scored: 5
  spread: 46.5
  strength: 1
  strong: 0
  worst: 0.0
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
    agent_score: 30.4
    api_count: 7
    api_count_basis: published
    immediate_parent: tripadvisor
    name: TheFork
    relationship: product
    score_band: developing
    score_composite: 46.5
    slug: thefork
    source: prose
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 4
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: tripadvisor
    name: Oyster.com (TripAdvisor)
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: oystercom-tripadvisor
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: thefork
    name: bookatable
    relationship: product
    score_band: minimal
    score_composite: 1.6
    slug: bookatable
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: tripadvisor
    name: HouseTrip
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: housetrip
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: tripadvisor
    name: Restorando
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: restorando
    source: parent-company-property
  label: Minimal
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
  of which 5 carry a rating. The rated members span 46.5 points, from 46.5 down to 0.0.


  Its highest-rated surfaces are TheFork, Oyster.com (TripAdvisor), bookatable, HouseTrip, Restorando.'
parent_provider: tripadvisor
permalink: /estates/tripadvisor/
slug: tripadvisor
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: bookatable
    score_band: minimal
    score_composite: 1.6
    slug: bookatable
  name: TheFork
  on_network: true
  permalink: /estates/thefork/
  slug: thefork
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
