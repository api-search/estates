---
api_total: 2
category: Estates
description: PTC is an industrial technology company providing software platforms and APIs for Industrial
  IoT (ThingWorx), Product Lifecycle Management (Windchill, Arena), Augmented Reality (Vuforia), Field
  Service Management (ServiceMax), and industrial connectivity (Kepware) in manufacturing environments.
estate_rating:
  agent_avg: 15.7
  agent_band: emerging
  agent_native: 0
  agent_raw: 23.7
  agent_ready: 1
  band: emerging
  best: 51.0
  composite_avg: 26.4
  composite_band: thin
  composite_raw: 33.6
  developing: 1
  exemplar: 0
  rating: 22.1
  scored: 3
  spread: 36.5
  strength: 1
  strong: 0
  worst: 14.5
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ptc.png
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
    agent_score: 37.2
    api_count: 1
    immediate_parent: ptc
    name: Onshape
    relationship: product
    score_band: developing
    score_composite: 51.0
    slug: onshape
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
    agent_score: 23.0
    api_count: 1
    immediate_parent: ptc
    name: PTC ThingWorx
    relationship: product
    score_band: thin
    score_composite: 35.4
    slug: ptc-thingworx
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 10.8
    api_count: 0
    immediate_parent: ptc
    name: ServiceMax
    relationship: product
    score_band: emerging
    score_composite: 14.5
    slug: servicemax
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
name: PTC
overview: 'PTC publishes its API surface across 3 provider profiles indexed on the APIs.io network, of
  which 3 carry a rating. The rated members span 36.5 points, from 51.0 down to 14.5.


  Its highest-rated surfaces are Onshape, PTC ThingWorx, ServiceMax.'
parent_provider: ptc
permalink: /estates/ptc/
slug: ptc
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ptc/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Industrial IoT
- PLM
- Augmented Reality
- Field Service Management
- Manufacturing
- IIoT
- CAD
- Digital Transformation
title: PTC
---
