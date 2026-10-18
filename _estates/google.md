---
api_total: 2
category: Estates
description: Google Docs is an online word processing and PDF editing tool that is part of Google Workspace.
  It provides cloud‑based document creation, real‑time collaboration, and AI‑powered features such as
  Gemini in Docs for drafting and formatting. The service is offered to individuals, small businesses,
  startups, and enterprise customers for secure, cloud‑native productivity.
estate_rating:
  agent_avg: 13.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 17.8
  agent_ready: 0
  band: emerging
  best: 59.0
  composite_avg: 24.8
  composite_band: emerging
  composite_raw: 33.5
  developing: 0
  exemplar: 0
  rating: 20.1
  scored: 3
  spread: 49.5
  strength: 2
  strong: 1
  worst: 9.5
estate_root: null
estate_root_name: null
image: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 26.1
    api_count: 1
    api_count_basis: published
    immediate_parent: google
    name: Google Workspace
    relationship: product
    score_band: strong
    score_composite: 59.0
    slug: google-workspace
    source: declared
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 27.3
    api_count: 1
    api_count_basis: published
    immediate_parent: google-workspace
    name: Google Chat Integrations for Workspace
    relationship: product
    score_band: thin
    score_composite: 32.0
    slug: google-chat-integrations-for-workspace
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: google-workspace
    name: Google Vids
    relationship: product
    score_band: minimal
    score_composite: 9.5
    slug: vids
    source: declared
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Google
overview: 'Google publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 49.5 points, from 59.0 down to 9.5.


  Its highest-rated surfaces are Google Workspace, Google Chat Integrations for Workspace, Google Vids.'
parent_provider: google
permalink: /estates/google/
slug: google
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 3
  members:
  - name: Google Workspace
    score_band: strong
    score_composite: 59.0
    slug: google-workspace
  - name: Google Chat Integrations for Workspace
    score_band: thin
    score_composite: 32.0
    slug: google-chat-integrations-for-workspace
  - name: Google Vids
    score_band: minimal
    score_composite: 9.5
    slug: vids
  name: Google Workspace
  on_network: true
  permalink: /estates/google-workspace/
  slug: google-workspace
subfamily_page_count: 0
tags:
- Advertising
- Cloud
- Developers
- Google
- Platform
- Search
- T1
- Agentic Commerce
- Universal Commerce Protocol
- AP2
- A2A
title: Google
---
