---
api_total: 16
category: Estates
description: Berkshire Hathaway is a multinational conglomerate holding company headquartered in Omaha,
  Nebraska. The company's diversified subsidiaries span insurance (GEICO, Berkshire Hathaway Specialty
  Insurance, National Indemnity), freight rail transportation (BNSF Railway), utilities and energy (Berkshire
  Hathaway Energy), manufacturing (Precision Castparts, Iscar), wholesale distribution (McLane Company),
  and services and retailing. BNSF Railway, one of North America's largest freight rail networks, operates
  a public API Center providing customer APIs for shipment tracking, pricing, scheduling, and waybill
  management.
estate_rating:
  agent_avg: 8.3
  agent_band: minimal
  agent_native: 0
  agent_raw: 6.0
  agent_ready: 1
  band: emerging
  best: 49.1
  composite_avg: 17.0
  composite_band: emerging
  composite_raw: 13.6
  developing: 1
  exemplar: 0
  rating: 13.5
  scored: 5
  spread: 46.6
  strength: 1
  strong: 0
  worst: 2.5
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/berkshire-hathaway.png
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
    agent_score: 30.0
    api_count: 16
    immediate_parent: berkshire-hathaway
    name: BNSF
    relationship: subsidiary
    score_band: developing
    score_composite: 49.1
    slug: bnsf
    source: declared
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
    immediate_parent: berkshire-hathaway
    name: GEICO
    relationship: subsidiary
    score_band: minimal
    score_composite: 9.4
    slug: geico
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: berkshire-hathaway
    name: Alleghany
    relationship: acquisition
    score_band: minimal
    score_composite: 3.8
    slug: alleghany
    source: declared
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: berkshire-hathaway
    name: Dairyqueen
    relationship: subsidiary
    score_band: minimal
    score_composite: 3.4
    slug: dairyqueen
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: berkshire-hathaway
    name: Precision Castparts
    relationship: acquisition
    score_band: minimal
    score_composite: 2.5
    slug: precision-castparts
    source: prose
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
name: Berkshire Hathaway
overview: 'Berkshire Hathaway publishes its API surface across 5 provider profiles indexed on the APIs.io
  network, of which 5 carry a rating. The rated members span 46.6 points, from 49.1 down to 2.5.


  Its highest-rated surfaces are BNSF, GEICO, Alleghany, Dairyqueen, Precision Castparts.'
parent_provider: berkshire-hathaway
permalink: /estates/berkshire-hathaway/
slug: berkshire-hathaway
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/berkshire-hathaway/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Conglomerate
- Energy
- Finance
- Freight Rail
- Insurance
- Investment
- Manufacturing
- Retail
- Utilities
- Fortune 100
title: Berkshire Hathaway
---
