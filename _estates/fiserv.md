---
api_total: 2
category: Estates
description: Fiserv is a global provider of financial services technology solutions, offering a wide range
  of products and services to help clients in the banking, payments, and wealth management industries.
estate_rating:
  agent_avg: 7.4
  agent_band: minimal
  agent_native: 0
  agent_raw: 2.8
  agent_ready: 0
  band: emerging
  best: 18.8
  composite_avg: 16.2
  composite_band: emerging
  composite_raw: 8.5
  developing: 0
  exemplar: 0
  rating: 12.7
  scored: 4
  spread: 18.7
  strength: 0
  strong: 0
  worst: 0.1
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
    agent_score: 11.2
    api_count: 2
    immediate_parent: fiserv
    name: First Data (Fiserv)
    relationship: acquisition
    score_band: emerging
    score_composite: 18.8
    slug: first-data
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: first-data
    name: Salido
    relationship: product
    score_band: minimal
    score_composite: 10.4
    slug: salido
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: fiserv
    name: BentoBox
    relationship: product
    score_band: minimal
    score_composite: 4.7
    slug: bentobox
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: first-data
    name: Clover Networks
    relationship: product
    score_band: minimal
    score_composite: 0.1
    slug: clover-networks
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: fiserv
    name: Corillian
    relationship: product
    score_band: null
    score_composite: null
    slug: corillian
    source: prose
  label: Unrated
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
name: Fiserv
overview: 'Fiserv publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 18.7 points, from 18.8 down to 0.1.


  Its highest-rated surfaces are First Data (Fiserv), Salido, BentoBox, Clover Networks, Corillian.'
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
    score_composite: 10.4
    slug: salido
  - name: Clover Networks
    score_band: minimal
    score_composite: 0.1
    slug: clover-networks
  name: First Data (Fiserv)
  on_network: true
  permalink: /estates/first-data/
  slug: first-data
subfamily_page_count: 0
tags:
- Banking
- Financial
- Payments
- Wealth Management
- Fortune 500
title: Fiserv
---
