---
api_total: 4
category: Estates
description: The GitHub REST API allows developers to programmatically interact with GitHub resources
  including repositories, users, organizations, pull requests, issues, and more.
estate_rating:
  agent_avg: 10.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.3
  agent_ready: 0
  band: emerging
  best: 39.0
  composite_avg: 22.1
  composite_band: emerging
  composite_raw: 22.2
  developing: 0
  exemplar: 0
  rating: 17.4
  scored: 4
  spread: 32.1
  strength: 0
  strong: 0
  worst: 6.9
image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    immediate_parent: github
    name: GitHub Container Registry
    relationship: product
    score_band: thin
    score_composite: 39.0
    slug: github-container-registry
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 17.3
    api_count: 1
    immediate_parent: github
    name: GitHub Enterprise
    relationship: product
    score_band: thin
    score_composite: 28.9
    slug: github-enterprise
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: github
    name: GitHub CLI
    relationship: product
    score_band: emerging
    score_composite: 13.9
    slug: github-cli
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: github
    name: GitHub ReadMe Stats
    relationship: product
    score_band: minimal
    score_composite: 6.9
    slug: github-readme-stats
  label: Minimal
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: GitHub
overview: 'GitHub publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 32.1 points, from 39.0 down to 6.9.


  Its highest-rated surfaces are GitHub Container Registry, GitHub Enterprise, GitHub CLI, GitHub ReadMe
  Stats.'
parent_provider: github
permalink: /estates/github/
slug: github
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/github/refs/heads/main/apis.yml
subfamilies: []
tags:
- Code
- Pipelines
- Platform
- Software Development
- Source Control
- T1
title: GitHub
---
