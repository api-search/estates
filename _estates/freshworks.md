---
api_total: 7
category: Estates
description: Freshworks is a software company that develops cloud-based business software including customer
  support, IT service management, sales force automation, marketing automation, and HR applications.
estate_rating:
  agent_avg: 20.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 27.9
  agent_ready: 3
  band: thin
  best: 66.1
  composite_avg: 31.1
  composite_band: thin
  composite_raw: 38.2
  developing: 0
  exemplar: 0
  rating: 26.9
  scored: 6
  spread: 43.0
  strength: 2
  strong: 1
  worst: 23.1
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
    agent_score: 34.2
    api_count: 2
    immediate_parent: freshworks
    name: FireHydrant
    relationship: product
    score_band: strong
    score_composite: 66.1
    slug: firehydrant
    source: prose
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 4
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    immediate_parent: freshworks
    name: Freshteam
    relationship: product
    score_band: thin
    score_composite: 37.0
    slug: freshteam
    source: declared
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 21.6
    api_count: 1
    immediate_parent: freshworks
    name: Freshchat
    relationship: product
    score_band: thin
    score_composite: 35.2
    slug: freshchat
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 17.3
    api_count: 1
    immediate_parent: freshworks
    name: Freshsales
    relationship: product
    score_band: thin
    score_composite: 34.2
    slug: freshsales
    source: declared
  - &id005
    acquired: null
    agent_band: agent-ready
    agent_score: 42.1
    api_count: 1
    immediate_parent: freshworks
    name: Freshservice
    relationship: product
    score_band: thin
    score_composite: 33.4
    slug: freshservice
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id006
    acquired: null
    agent_band: agent-ready
    agent_score: 30.6
    api_count: 1
    immediate_parent: firehydrant
    name: Blameless
    relationship: product
    score_band: emerging
    score_composite: 23.1
    slug: blameless
    source: parent-company-property
  label: Emerging
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id007
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: freshworks
    name: Natero
    relationship: product
    score_band: null
    score_composite: null
    slug: natero
    source: prose
  label: Unrated
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
  of which 7 carry a rating. The rated members span 43.0 points, from 66.1 down to 23.1.


  Its highest-rated surfaces are FireHydrant, Freshteam, Freshchat, Freshsales, Freshservice.'
parent_provider: freshworks
permalink: /estates/freshworks/
slug: freshworks
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Blameless
    score_band: emerging
    score_composite: 23.1
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
