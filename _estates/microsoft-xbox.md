---
api_total: 34
category: Estates
description: APIs for Xbox gaming platform including Xbox Live Services and Azure PlayFab backend for
  games.
estate_rating:
  agent_avg: 17.3
  agent_band: emerging
  agent_native: 1
  agent_raw: 22.8
  agent_ready: 1
  band: emerging
  best: 48.6
  composite_avg: 26.2
  composite_band: thin
  composite_raw: 29.7
  developing: 2
  exemplar: 0
  rating: 22.6
  scored: 6
  spread: 41.0
  strength: 2
  strong: 0
  worst: 7.6
estate_root: microsoft
estate_root_name: Microsoft
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/microsoft-xbox.png
is_subfamily: true
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: microsoft-xbox
    name: PlayFab
    relationship: product
    score_band: developing
    score_composite: 48.6
    slug: playfab
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 5
    immediate_parent: microsoft-xbox
    name: Blizzard Entertainment
    relationship: product
    score_band: developing
    score_composite: 46.7
    slug: blizzard-entertainment
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: agent-native
    agent_score: 38.8
    api_count: 12
    immediate_parent: microsoft-xbox
    name: Battle.net
    relationship: product
    score_band: thin
    score_composite: 27.0
    slug: battle-net
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 28.1
    api_count: 14
    immediate_parent: microsoft-xbox
    name: Mojang
    relationship: product
    score_band: thin
    score_composite: 26.9
    slug: mojang
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: agent-ready
    agent_score: 30.2
    api_count: 1
    immediate_parent: microsoft-xbox
    name: Activision Blizzard
    relationship: product
    score_band: emerging
    score_composite: 21.1
    slug: activision-blizzard
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: microsoft-xbox
    name: Halo
    relationship: product
    score_band: minimal
    score_composite: 7.6
    slug: halo
  label: Minimal
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
name: Microsoft Xbox
overview: 'Microsoft Xbox publishes its API surface across 6 provider profiles indexed on the APIs.io
  network, of which 6 carry a rating. The rated members span 41.0 points, from 48.6 down to 7.6.


  Its highest-rated surfaces are PlayFab, Blizzard Entertainment, Battle.net, Mojang, Activision Blizzard.'
parent_provider: microsoft-xbox
permalink: /estates/microsoft-xbox/
slug: microsoft-xbox
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-xbox/refs/heads/main/apis.yml
subfamilies: []
tags:
- Gaming
- Microsoft
- PlayFab
- Xbox
- Xbox Live
title: Microsoft Xbox
---
