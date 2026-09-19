---
api_total: 3
category: Estates
description: 'Moody''s Corporation (NYSE: MCO) is a global integrated risk-assessment firm operating through
  two segments: Moody''s Ratings (Moody''s Investors Service), which publishes credit ratings and assessment
  services on debt obligations, and Moody''s Analytics, which provides data, software, research, and APIs
  spanning economic data, credit risk, KYC/AML, ESG, climate, and catastrophe modeling. Moody''s Analytics
  products are exposed through multiple developer APIs and a portal at developer.moodys.com, with deeper
  API surfaces published at api.economy.com (Data Buffet, Scenario Studio, AutoCycle, ECCL) and through
  subsidiary brands including Bureau van Dijk (Orbis), RMS (catastrophe risk), Kompany / Passfort (KYC),
  and Four Twenty Seven (climate).'
estate_rating:
  agent_avg: 11.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 11.6
  agent_ready: 1
  band: emerging
  best: 35.9
  composite_avg: 19.8
  composite_band: emerging
  composite_raw: 15.3
  developing: 0
  exemplar: 0
  rating: 16.4
  scored: 3
  spread: 30.9
  strength: 0
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/moodys-corporation.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 34.9
    api_count: 3
    immediate_parent: moodys-corporation
    name: Moody's RMS
    relationship: product
    score_band: thin
    score_composite: 35.9
    slug: moodys-rms
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: moodys-corporation
    name: Cortera
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: cortera
    source: declared
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: moodys-corporation
    name: Regulatory DataCorp
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: regulatory-datacorp
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
name: Moody's Corporation
overview: 'Moody''s Corporation publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 30.9 points, from 35.9 down to 5.0.


  Its highest-rated surfaces are Moody''s RMS, Cortera, Regulatory DataCorp.'
parent_provider: moodys-corporation
permalink: /estates/moodys-corporation/
slug: moodys-corporation
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/moodys-corporation/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Analytics
- Catastrophe Risk
- Climate Risk
- Compliance
- Credit Ratings
- Economic Data
- ESG
- Financial Data
- KYC
- Risk
- Fortune 1000
title: Moody's Corporation
---
