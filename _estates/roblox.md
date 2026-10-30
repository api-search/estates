---
api_total: 2
category: Estates
description: 'Roblox is a user-generated content platform where creators build, publish, and monetize
  immersive 3D experiences using Roblox Studio and the Luau scripting language. Roblox exposes three distinct
  developer surfaces: the in-engine Luau scripting API (Roblox Engine API) running inside experiences
  and Studio plugins, the Roblox Studio plugin API for editor tooling, and the Open Cloud API (apis.roblox.com)
  for external programmatic access from servers, build pipelines, and back-office tools. The Open Cloud
  surface covers DataStores, Memory Stores, Messaging Service, Place Publishing, Universes, Assets, Inventory,
  Users, Groups, Notifications, Subscriptions, and Luau Execution, authenticated either with API keys
  scoped per-resource or with OAuth 2.0 for third-party apps. Roblox also publishes deep documentation
  for the Engine API at create.roblox.com/docs and the legacy ROBLOX Web APIs that power the website (subdomains
  such as users.roblox.com, groups.roblox.com, inventory.roblox.com), which remain undocumented for third
  parties.'
estate_rating:
  agent_avg: 11.6
  agent_band: emerging
  agent_native: 0
  agent_raw: 13.2
  agent_ready: 0
  band: emerging
  best: 41.5
  composite_avg: 19.0
  composite_band: emerging
  composite_raw: 17.7
  developing: 1
  exemplar: 0
  rating: 16.0
  scored: 3
  spread: 41.5
  strength: 1
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/roblox.png
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
    agent_score: 19.6
    api_count: 1
    api_count_basis: published
    immediate_parent: roblox
    name: Roblox Engine API
    relationship: product
    score_band: developing
    score_composite: 41.5
    slug: roblox-engine-api
    source: declared
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 20.0
    api_count: 0
    api_count_basis: split
    immediate_parent: roblox
    name: Guilded
    relationship: acquisition
    score_band: emerging
    score_composite: 11.7
    slug: guilded
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    api_count_basis: split
    immediate_parent: roblox
    name: Speechly
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: speechly
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Roblox
overview: 'Roblox publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 41.5 points, from 41.5 down to 0.0.


  Its highest-rated surfaces are Roblox Engine API, Guilded, Speechly.'
parent_provider: roblox
permalink: /estates/roblox/
slug: roblox
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/roblox/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Assets
- Datastores
- Game Development
- Games
- Luau
- Messaging
- Open Cloud
- Roblox
- Scripting
- Studio
- UGC
- Universes
title: Roblox
---
