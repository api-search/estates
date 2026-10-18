---
api_total: 23
category: Estates
description: FIS (Fidelity National Information Services) is a global leader in financial technology providing
  APIs for core banking, payments, wealth management, and capital markets through the CodeConnect API
  marketplace. APIs connect financial institutions, fintechs, and enterprises to FIS banking and payment
  infrastructure.
estate_rating:
  agent_avg: 13.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 17.5
  agent_ready: 2
  band: emerging
  best: 61.3
  composite_avg: 25.8
  composite_band: thin
  composite_raw: 33.6
  developing: 0
  exemplar: 0
  rating: 20.8
  scored: 4
  spread: 54.0
  strength: 4
  strong: 2
  worst: 7.3
estate_root: null
estate_root_name: null
image: https://codeconnect.fisglobal.com/assets/FIS_codeConnect_logo_white.svg
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 34.6
    api_count: 4
    api_count_basis: published
    immediate_parent: fis
    name: Payrix
    relationship: acquisition
    score_band: strong
    score_composite: 61.3
    slug: payrix
    source: prose
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 32.4
    api_count: 18
    api_count_basis: published
    immediate_parent: fis
    name: Bond
    relationship: acquisition
    score_band: strong
    score_composite: 58.2
    slug: bond
    source: prose
  label: Strong
  open: true
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 0
    api_count_basis: split
    immediate_parent: fis
    name: IntelliMatch
    relationship: acquisition
    score_band: minimal
    score_composite: 7.8
    slug: intellimatch
    source: declared
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.6
    api_count: 1
    api_count_basis: split
    immediate_parent: fis
    name: SunGard Data Systems
    relationship: acquisition
    score_band: minimal
    score_composite: 7.3
    slug: sungard-data-systems
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
name: FIS Global
overview: 'FIS Global publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 54.0 points, from 61.3 down to 7.3.


  Its highest-rated surfaces are Payrix, Bond, IntelliMatch, SunGard Data Systems.'
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
- Financial Services
- Payments
- Fintech
title: FIS Global
---
