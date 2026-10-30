---
api_total: 7
category: Estates
description: Freshworks is a software company that develops cloud-based business software including customer
  support, IT service management, sales force automation, marketing automation, and HR applications.
estate_rating:
  agent_avg: 17.6
  agent_band: emerging
  agent_native: 0
  agent_raw: 22.6
  agent_ready: 2
  band: emerging
  best: 64.9
  composite_avg: 25.5
  composite_band: thin
  composite_raw: 29.7
  developing: 0
  exemplar: 0
  rating: 22.3
  scored: 7
  spread: 64.9
  strength: 2
  strong: 1
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/freshworks.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 35.1
    api_count: 2
    api_count_basis: published
    immediate_parent: freshworks
    name: FireHydrant
    relationship: product
    score_band: strong
    score_composite: 64.9
    slug: firehydrant
    source: prose
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 22.8
    api_count: 1
    api_count_basis: published
    immediate_parent: freshworks
    name: Freshchat
    relationship: product
    score_band: thin
    score_composite: 35.7
    slug: freshchat
    source: declared
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 43.3
    api_count: 1
    api_count_basis: published
    immediate_parent: freshworks
    name: Freshservice
    relationship: product
    score_band: thin
    score_composite: 34.6
    slug: freshservice
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 19.0
    api_count: 1
    api_count_basis: published
    immediate_parent: freshworks
    name: Freshsales
    relationship: product
    score_band: thin
    score_composite: 34.5
    slug: freshsales
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 20.6
    api_count: 1
    api_count_basis: published
    immediate_parent: freshworks
    name: Freshteam
    relationship: product
    score_band: emerging
    score_composite: 24.2
    slug: freshteam
    source: declared
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 17.6
    api_count: 1
    api_count_basis: split
    immediate_parent: firehydrant
    name: Blameless
    relationship: product
    score_band: emerging
    score_composite: 13.7
    slug: blameless
    source: parent-company-property
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: freshworks
    name: Natero
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: natero
    source: prose
  label: Minimal
  open: false
member_on_network: 7
member_total: 7
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
members_unrated: []
name: Freshworks
overview: 'Freshworks publishes its API surface across 7 provider profiles indexed on the APIs.io network,
  of which 7 carry a rating. The rated members span 64.9 points, from 64.9 down to 0.0.


  Its highest-rated surfaces are FireHydrant, Freshchat, Freshservice, Freshsales, Freshteam.'
parent_provider: freshworks
permalink: /estates/freshworks/
slug: freshworks
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/freshworks/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Blameless
    score_band: emerging
    score_composite: 13.7
    slug: blameless
  name: FireHydrant
  on_network: true
  permalink: /estates/firehydrant/
  slug: firehydrant
subfamily_page_count: 0
tags:
- Analytics
- Campaigns
- Email Marketing
- Marketing
- Marketing Automation
- Freshworks
title: Freshworks
---
