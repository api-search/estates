---
api_total: 17
category: Estates
description: Booking Holdings is the world's leading provider of online travel and related services, operating
  a portfolio of brands including Booking.com, Priceline, Agoda, KAYAK, OpenTable, Rentalcars.com, Rocketmiles,
  FareHarbor, HotelsCombined, Cheapflights, and Momondo. The company connects travelers with accommodations,
  flights, rental cars, restaurant reservations, and travel experiences worldwide.
estate_rating:
  agent_avg: 13.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 17.0
  agent_ready: 1
  band: emerging
  best: 70.8
  composite_avg: 28.2
  composite_band: thin
  composite_raw: 37.8
  developing: 0
  exemplar: 1
  rating: 22.2
  scored: 3
  spread: 51.5
  strength: 3
  strong: 0
  worst: 19.3
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/booking-holdings.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 46.1
    api_count: 15
    immediate_parent: booking-holdings
    name: Booking.com
    relationship: product
    score_band: exemplar
    score_composite: 70.8
    slug: booking-com
    source: prose
  label: Exemplar
  open: true
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 5.0
    api_count: 2
    immediate_parent: booking-holdings
    name: OpenTable
    relationship: product
    score_band: emerging
    score_composite: 23.2
    slug: opentable
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: booking-holdings
    name: Kayak
    relationship: product
    score_band: emerging
    score_composite: 19.3
    slug: kayak
    source: prose
  label: Emerging
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Booking Holdings
overview: 'Booking Holdings publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 51.5 points, from 70.8 down to 19.3.


  Its highest-rated surfaces are Booking.com, OpenTable, Kayak.'
parent_provider: booking-holdings
permalink: /estates/booking-holdings/
slug: booking-holdings
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/booking-holdings/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Accommodation
- Airlines
- Car Rentals
- Hospitality
- Hotels
- Restaurant
- Travel
title: Booking Holdings
---
