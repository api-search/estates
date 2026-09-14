---
api_total: 10
category: Estates
description: FIS (Fidelity National Information Services) is a global leader in financial technology providing
  APIs for core banking, payments, wealth management, and capital markets through the CodeConnect API
  marketplace. APIs connect financial institutions, fintechs, and enterprises to FIS banking and payment
  infrastructure.
estate_rating:
  agent_avg: 10.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 9.2
  agent_ready: 0
  band: emerging
  best: 51.0
  composite_avg: 22.4
  composite_band: emerging
  composite_raw: 22.9
  developing: 1
  exemplar: 0
  rating: 17.6
  scored: 3
  spread: 43.9
  strength: 1
  strong: 0
  worst: 7.1
estate_root: null
estate_root_name: null
image: https://codeconnect.fisglobal.com/assets/FIS_codeConnect_logo_white.svg
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 22.7
    api_count: 9
    immediate_parent: fis
    name: Bond
    relationship: product
    score_band: developing
    score_composite: 51.0
    slug: bond
    source: prose
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: fis
    name: SunGard Data Systems
    relationship: acquisition
    score_band: minimal
    score_composite: 10.5
    slug: sungard-data-systems
    source: declared
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 0
    immediate_parent: fis
    name: IntelliMatch
    relationship: acquisition
    score_band: minimal
    score_composite: 7.1
    slug: intellimatch
    source: declared
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: FIS Global
overview: 'FIS Global publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 43.9 points, from 51.0 down to 7.1.


  Its highest-rated surfaces are Bond, SunGard Data Systems, IntelliMatch.'
parent_provider: fis
permalink: /estates/fis/
slug: fis
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fis/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Banking
- Core Banking
- Financial-Services
- Payments
- Fintech
title: FIS Global
---
