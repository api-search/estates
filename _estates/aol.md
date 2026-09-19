---
api_total: 1
category: Estates
description: AOL is a consumer internet media and communications brand — AOL.com news, AOL Mail, AOL Search
  and AOL Desktop — operated by AOL Media LLC. Founded as America Online, it was acquired by Verizon in
  2015, folded into Oath and then Yahoo, and sold on to the Italian software company Bending Spoons in
  2026; the security.txt AOL serves today points its PGP key at bendingspoons.com. AOL runs no developer
  program and publishes no product API. Its one publicly callable, machine-readable contract is the OpenID
  Connect provider at api.login.aol.com, which serves a full discovery document under its own issuer and
  lets a third-party application sign a user in with their AOL account. The legacy developer documentation
  for that identity stack is hosted by Yahoo Inc., which runs a sibling deployment of the same Oath-era
  OAuth 2.0 / OIDC platform.
estate_rating:
  agent_avg: 10.8
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.0
  agent_ready: 0
  band: emerging
  best: 40.5
  composite_avg: 22.5
  composite_band: emerging
  composite_raw: 22.8
  developing: 1
  exemplar: 0
  rating: 17.8
  scored: 2
  spread: 35.5
  strength: 1
  strong: 0
  worst: 5.0
estate_root: verizon
estate_root_name: Verizon
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/aol.png
is_subfamily: true
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 20.0
    api_count: 1
    immediate_parent: aol
    name: TechCrunch
    relationship: product
    score_band: developing
    score_composite: 40.5
    slug: techcrunch
    source: prose
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: aol
    name: Convertro, Inc.
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: convertro-inc
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: aol
    name: Outside.in
    relationship: product
    score_band: null
    score_composite: null
    slug: outsidein
    source: prose
  - &id004
    acquired: 2010-09
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: aol
    name: Thing Labs
    relationship: product
    score_band: null
    score_composite: null
    slug: thing-labs
    source: prose
  label: Unrated
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: AOL
overview: 'AOL publishes its API surface across 4 provider profiles indexed on the APIs.io network, of
  which 4 carry a rating. The rated members span 35.5 points, from 40.5 down to 5.0.


  Its highest-rated surfaces are TechCrunch, Convertro, Inc., Outside.in, Thing Labs.'
parent_provider: aol
permalink: /estates/aol/
slug: aol
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aol/refs/heads/main/apis.yml
subfamilies: []
tags:
- Digital Media
- News
- Entertainment
- Advertising
- Identity
- OpenID Connect
- Authentication
- Email
- Consumer Internet
- Fortune 1000
title: AOL
---
