---
api_total: 0
category: Estates
description: Yahoo is a consumer internet and advertising-technology company operating Yahoo Mail, Yahoo
  Finance, Yahoo Sports and Yahoo Search alongside one of the largest independent demand-side platforms
  in programmatic advertising. Its public API surface splits cleanly in two. On the consumer side, the
  Yahoo Fantasy Sports API exposes fantasy football, baseball, basketball and hockey game, league, team,
  player, roster and transaction data over a composed URI tree at fantasysports.yahooapis.com, secured
  by a three-legged OAuth 2.0 flow against the Yahoo identity service, which itself publishes a full OpenID
  Connect discovery document. On the enterprise side, Yahoo Ad Tech ships the DSP Traffic API for programmatic
  campaign management, the DSP Reporting API for large-scale campaign measurement, the server-to-server
  Yahoo Conversion API, and the DataX API for audience and taxonomy exchange with data partners - all
  gated behind an existing DSP seat or a partner onboarding agreement and authenticated with a two-legged
  client-credentials JWT flow. Yahoo publishes no OpenAPI for any of these surfaces, distributing a public
  Postman collection and an llms.txt documentation index instead.
estate_rating:
  agent_avg: 4.0
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: minimal
  best: 20.5
  composite_avg: 9.4
  composite_band: minimal
  composite_raw: 2.6
  developing: 0
  exemplar: 0
  rating: 7.2
  scored: 8
  spread: 20.5
  strength: 0
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/yahoo.png
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: Flurry
    relationship: product
    score_band: emerging
    score_composite: 20.5
    slug: flurry
    source: parent-company-property
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 7
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: Aviate
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: aviate
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: Bix
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: bix
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: Dapper
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: dapper
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: MessageMe *
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: messageme
    source: parent-company-property
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: Polyvore
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: polyvore
    source: parent-company-property
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: Rockmelt
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: rockmelt
    source: prose
  - &id008
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: Tomfoolery
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: tomfoolery
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id009
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: yahoo
    name: BrightRoll
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: brightroll
    source: prose
  label: Unrated
  open: false
member_on_network: 9
member_total: 9
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
- *id009
members_unrated: []
name: Yahoo
overview: 'Yahoo publishes its API surface across 9 provider profiles indexed on the APIs.io network,
  of which 9 carry a rating. The rated members span 20.5 points, from 20.5 down to 0.0.


  Its highest-rated surfaces are Flurry, Aviate, Bix, Dapper, MessageMe *.'
parent_provider: yahoo
permalink: /estates/yahoo/
slug: yahoo
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/yahoo/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Advertising
- Programmatic Advertising
- DSP
- Fantasy Sports
- Sports Data
- Identity
- OpenID Connect
- Authentication
- Audience Data
- Media
- Reporting
- Conversion Tracking
title: Yahoo
---
