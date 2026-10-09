---
api_total: 0
category: Estates
description: 'Avago Technologies Limited was the Singapore-headquartered semiconductor company spun out
  of Agilent Technologies'' semiconductor products group in 2005 that acquired Broadcom Corporation for
  $37 billion on February 1, 2016 and renamed itself Broadcom Limited, today Broadcom Inc. (NASDAQ: AVGO).
  Avago is therefore not a subsidiary of Broadcom but its legal predecessor and former corporate name.
  The brand is retired: every path on avagotech.com returns an HTTP 301 to broadcom.com, avago.com is
  a third-party domain-brokerage landing page rather than a company site, and no Avago-branded developer
  portal, documentation, OpenAPI, SDK, package or GitHub organization exists. API surfaces once associated
  with Avago product lines (LSI and Emulex storage controllers, fiber optics, RF) are published today
  by Broadcom and are profiled under the broadcom record.'
estate_rating:
  agent_avg: 7.5
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 0.0
  composite_avg: 14.5
  composite_band: emerging
  composite_raw: 0.0
  developing: 0
  exemplar: 0
  rating: 11.7
  scored: 2
  spread: 0.0
  strength: 0
  strong: 0
  worst: 0.0
estate_root: broadcom
estate_root_name: Broadcom
image: ''
is_subfamily: true
layout: estate
member_bands:
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: avago-technologies
    name: LSI Logic
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: lsi-logic
    source: prose
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: lsi
    name: Sandforce
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: sandforce
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: avago-technologies
    name: LSI
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: lsi
    source: prose
  label: Unrated
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Avago Technologies
overview: 'Avago Technologies publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 0.0 points, from 0.0 down to 0.0.


  Its highest-rated surfaces are LSI Logic, Sandforce, LSI.'
parent_provider: avago-technologies
permalink: /estates/avago-technologies/
slug: avago-technologies
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/avago-technologies/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Sandforce
    score_band: minimal
    score_composite: 0.0
    slug: sandforce
  name: LSI
  on_network: true
  permalink: /estates/lsi/
  slug: lsi
tags:
- Company
- Semiconductors
- Hardware
- Electronic Components
- Acquired
- Legacy Brand
- Broadcom
title: Avago Technologies
---
