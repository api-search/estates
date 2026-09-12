---
api_total: 6
category: Estates
description: NASA (National Aeronautics and Space Administration) provides a suite of public APIs at api.nasa.gov
  offering access to space, Earth science, and aeronautics data. Key APIs include Astronomy Picture of
  the Day (APOD), Mars Rover Photos, Near Earth Object Web Service (NeoWs), DONKI space weather events,
  EPIC Earth imagery, and the NASA Image and Video Library. All APIs are free and accessible with an API
  key.
estate_rating:
  agent_avg: 18.7
  agent_band: emerging
  agent_native: 0
  agent_raw: 26.6
  agent_ready: 3
  band: thin
  best: 49.4
  composite_avg: 33.9
  composite_band: thin
  composite_raw: 45.7
  developing: 5
  exemplar: 0
  rating: 27.8
  scored: 5
  spread: 6.6
  strength: 5
  strong: 0
  worst: 42.8
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/nasa.png
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 5
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 28.7
    api_count: 1
    immediate_parent: nasa
    name: NASA FIRMS
    relationship: product
    score_band: developing
    score_composite: 49.4
    slug: nasa-firms
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 22.9
    api_count: 1
    immediate_parent: nasa
    name: NASA NeoWs
    relationship: product
    score_band: developing
    score_composite: 48.1
    slug: nasa-neows
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 35.4
    api_count: 1
    immediate_parent: nasa
    name: NASA APOD
    relationship: product
    score_band: developing
    score_composite: 44.7
    slug: nasa-apod
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 17.3
    api_count: 2
    immediate_parent: nasa
    name: NASA CMR
    relationship: product
    score_band: developing
    score_composite: 43.7
    slug: nasa-cmr
  - &id005
    acquired: null
    agent_band: agent-ready
    agent_score: 28.7
    api_count: 1
    immediate_parent: nasa
    name: NASA Mars Rovers
    relationship: product
    score_band: developing
    score_composite: 42.8
    slug: nasa-mars
  label: Developing
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
name: NASA
overview: 'NASA publishes its API surface across 5 provider profiles indexed on the APIs.io network, of
  which 5 carry a rating. The rated members span 6.6 points, from 49.4 down to 42.8.


  Its highest-rated surfaces are NASA FIRMS, NASA NeoWs, NASA APOD, NASA CMR, NASA Mars Rovers.'
parent_provider: nasa
permalink: /estates/nasa/
slug: nasa
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/apis.yml
subfamilies: []
tags:
- Government
- Science
- Space
title: NASA
---
