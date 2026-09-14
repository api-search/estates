---
api_total: 1
category: Estates
description: Discover Intel® Trust Authority, the independent attestation service for securing your confidential
  computing workloads.
estate_rating:
  agent_avg: 6.8
  agent_band: minimal
  agent_native: 0
  agent_raw: 3.3
  agent_ready: 0
  band: emerging
  best: 27.4
  composite_avg: 15.8
  composite_band: emerging
  composite_raw: 10.6
  developing: 0
  exemplar: 0
  rating: 12.2
  scored: 6
  spread: 26.5
  strength: 0
  strong: 0
  worst: 0.9
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/intel.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 20.0
    api_count: 1
    immediate_parent: intel
    name: Moovit
    relationship: product
    score_band: thin
    score_composite: 27.4
    slug: moovit
    source: prose
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: intel
    name: Granulate
    relationship: product
    score_band: emerging
    score_composite: 20.9
    slug: granulate
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 4
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: intel
    name: Habana Labs
    relationship: product
    score_band: minimal
    score_composite: 7.2
    slug: habana-labs
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: intel
    name: Mobileye
    relationship: product
    score_band: minimal
    score_composite: 5.5
    slug: mobileye
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: intel
    name: Aepona
    relationship: product
    score_band: minimal
    score_composite: 1.8
    slug: aepona
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: intel
    name: KNO
    relationship: product
    score_band: minimal
    score_composite: 0.9
    slug: kno
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 2
  items:
  - &id007
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: intel
    name: Nervana Systems
    relationship: product
    score_band: null
    score_composite: null
    slug: nervana-systems
    source: prose
  - &id008
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: intel
    name: SigOpt
    relationship: product
    score_band: null
    score_composite: null
    slug: sigopt
    source: prose
  label: Unrated
  open: false
member_on_network: 8
member_total: 8
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
members_unrated: []
name: Intel
overview: 'Intel publishes its API surface across 8 provider profiles indexed on the APIs.io network,
  of which 8 carry a rating. The rated members span 26.5 points, from 27.4 down to 0.9.


  Its highest-rated surfaces are Moovit, Granulate, Habana Labs, Mobileye, Aepona.'
parent_provider: intel
permalink: /estates/intel/
slug: intel
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/intel/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Fortune 100
title: Intel
---
