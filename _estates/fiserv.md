---
api_total: 2
category: Estates
description: Fiserv is a global provider of financial services technology solutions, offering a wide range
  of products and services to help clients in the banking, payments, and wealth management industries.
estate_rating:
  agent_avg: 6.0
  agent_band: minimal
  agent_native: 0
  agent_raw: 1.4
  agent_ready: 0
  band: emerging
  best: 18.2
  composite_avg: 13.7
  composite_band: emerging
  composite_raw: 7.0
  developing: 0
  exemplar: 0
  rating: 10.6
  scored: 5
  spread: 18.2
  strength: 0
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/fiserv.png
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 7.1
    api_count: 2
    api_count_basis: split
    immediate_parent: fiserv
    name: First Data (Fiserv)
    relationship: acquisition
    score_band: emerging
    score_composite: 18.2
    slug: first-data
    source: declared
  label: Emerging
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
    immediate_parent: first-data
    name: Salido
    relationship: acquisition
    score_band: minimal
    score_composite: 10.7
    slug: salido
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: fiserv
    name: BentoBox
    relationship: product
    score_band: minimal
    score_composite: 5.9
    slug: bentobox
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: fiserv
    name: Corillian
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: corillian
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: fiserv
    name: Fincentric
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: fincentric
    source: parent-company-property
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id006
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: first-data
    name: Clover Networks
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: clover-networks
    source: prose
  label: Unrated
  open: false
member_on_network: 6
member_total: 6
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
members_unrated: []
name: Fiserv
overview: 'Fiserv publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 18.2 points, from 18.2 down to 0.0.


  Its highest-rated surfaces are First Data (Fiserv), Salido, BentoBox, Corillian, Fincentric.'
parent_provider: fiserv
permalink: /estates/fiserv/
slug: fiserv
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 2
  members:
  - name: Salido
    score_band: minimal
    score_composite: 10.7
    slug: salido
  - name: Clover Networks
    score_band: null
    score_composite: null
    slug: clover-networks
  name: First Data (Fiserv)
  on_network: true
  permalink: /estates/first-data/
  slug: first-data
subfamily_page_count: 0
tags:
- Banking
- Finance
- Payments
- Wealth Management
- Fortune 500
- Payment Processing
title: Fiserv
---
