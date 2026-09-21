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
  agent_avg: 11.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 11.2
  agent_ready: 1
  band: emerging
  best: 49.1
  composite_avg: 21.2
  composite_band: emerging
  composite_raw: 19.3
  developing: 1
  exemplar: 0
  rating: 17.3
  scored: 4
  spread: 46.1
  strength: 1
  strong: 0
  worst: 3.0
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
    agent_score: 32.1
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
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 12.9
    api_count: 0
    immediate_parent: berkshire-hathaway
    name: GEICO
    relationship: product
    score_band: emerging
    score_composite: 20.2
    slug: geico
    source: prose
  label: Emerging
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
    immediate_parent: berkshire-hathaway
    name: Precision Castparts
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: precision-castparts
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: berkshire-hathaway
    name: Alleghany Corporation
    relationship: acquisition
    score_band: minimal
    score_composite: 3.0
    slug: alleghany
    source: declared
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
name: Berkshire Hathaway
overview: 'Berkshire Hathaway publishes its API surface across 4 provider profiles indexed on the APIs.io
  network, of which 4 carry a rating. The rated members span 46.1 points, from 49.1 down to 3.0.


  Its highest-rated surfaces are BNSF, GEICO, Precision Castparts, Alleghany Corporation.'
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
