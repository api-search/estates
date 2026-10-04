---
api_total: 24
category: Estates
description: LexisNexis is a global provider of legal, regulatory, and business information and analytics.
  Through the LexisNexis Developer Portal and LexisNexis Risk Solutions, partners can integrate access
  to legal research, fraud detection, identity verification, and risk assessment capabilities into their
  applications. Most LexisNexis APIs are partner-access only and require contractual agreements before
  credentials and OpenAPI specifications are released.
estate_rating:
  agent_avg: 14.6
  agent_band: emerging
  agent_native: 0
  agent_raw: 18.7
  agent_ready: 1
  band: emerging
  best: 51.7
  composite_avg: 24.6
  composite_band: emerging
  composite_raw: 28.7
  developing: 1
  exemplar: 0
  rating: 20.6
  scored: 5
  spread: 47.6
  strength: 1
  strong: 0
  worst: 4.1
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/lexisnexis.png
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
    agent_score: 28.2
    api_count: 15
    immediate_parent: lexisnexis-risk-solutions
    name: Human API
    relationship: product
    score_band: developing
    score_composite: 51.7
    slug: human-api
    source: parent-company-property
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 7
    immediate_parent: lexisnexis
    name: LexisNexis Risk Solutions
    relationship: product
    score_band: thin
    score_composite: 35.0
    slug: lexisnexis-risk-solutions
    source: declared
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 47.1
    api_count: 1
    immediate_parent: lexisnexis
    name: Lex Machina
    relationship: acquisition
    score_band: thin
    score_composite: 29.9
    slug: lex-machina
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 1
    immediate_parent: lexisnexis
    name: Henchman
    relationship: product
    score_band: emerging
    score_composite: 22.9
    slug: henchman
    source: parent-company-property
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: lexisnexis-risk-solutions
    name: BehavioSec
    relationship: product
    score_band: minimal
    score_composite: 4.1
    slug: behaviosec
    source: parent-company-property
  label: Minimal
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
name: LexisNexis
overview: 'LexisNexis publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 47.6 points, from 51.7 down to 4.1.


  Its highest-rated surfaces are Human API, LexisNexis Risk Solutions, Lex Machina, Henchman, BehavioSec.'
parent_provider: lexisnexis
permalink: /estates/lexisnexis/
slug: lexisnexis
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lexisnexis/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 2
  members:
  - name: Human API
    score_band: developing
    score_composite: 51.7
    slug: human-api
  - name: BehavioSec
    score_band: minimal
    score_composite: 4.1
    slug: behaviosec
  name: LexisNexis Risk Solutions
  on_network: true
  permalink: /estates/lexisnexis-risk-solutions/
  slug: lexisnexis-risk-solutions
subfamily_page_count: 0
tags:
- Legal
- Risk Management
- Identity Verification
- Fraud Prevention
- Compliance
- Analytics
- Data
title: LexisNexis
---
