---
api_total: 17
category: Estates
description: The GitHub REST API allows developers to programmatically interact with GitHub resources
  including repositories, users, organizations, pull requests, issues, and more.
estate_rating:
  agent_avg: 19.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 23.6
  agent_ready: 2
  band: thin
  best: 80.2
  composite_avg: 34.2
  composite_band: thin
  composite_raw: 40.6
  developing: 2
  exemplar: 1
  rating: 28.2
  scored: 9
  spread: 73.3
  strength: 7
  strong: 1
  worst: 6.9
estate_root: microsoft
estate_root_name: Microsoft
image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
is_subfamily: true
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 50.0
    api_count: 1
    immediate_parent: github
    name: GitHub Actions
    relationship: product
    score_band: exemplar
    score_composite: 80.2
    slug: github-actions
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 48.2
    api_count: 1
    immediate_parent: github
    name: GitHub Copilot
    relationship: product
    score_band: strong
    score_composite: 64.1
    slug: github-copilot
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 23.2
    api_count: 2
    immediate_parent: github
    name: NuGet
    relationship: product
    score_band: developing
    score_composite: 49.8
    slug: nuget
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 26.6
    api_count: 1
    immediate_parent: github
    name: npm
    relationship: product
    score_band: developing
    score_composite: 49.3
    slug: npm
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id005
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
    source: declared
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 22.9
    api_count: 8
    immediate_parent: github
    name: Microsoft Package
    relationship: product
    score_band: thin
    score_composite: 33.4
    slug: microsoft-package
    source: declared
  - &id007
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
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id008
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
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id009
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
    source: declared
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 2
  items:
  - &id010
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: github
    name: Artillery Games
    relationship: product
    score_band: null
    score_composite: null
    slug: artillery-games
    source: parent-company-property
  - &id011
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: github
    name: Lytmus
    relationship: product
    score_band: null
    score_composite: null
    slug: lytmus
    source: parent-company-property
  label: Unrated
  open: false
member_on_network: 11
member_total: 11
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
- *id010
- *id011
members_unrated: []
name: GitHub
overview: 'GitHub publishes its API surface across 11 provider profiles indexed on the APIs.io network,
  of which 11 carry a rating. The rated members span 73.3 points, from 80.2 down to 6.9.


  Its highest-rated surfaces are GitHub Actions, GitHub Copilot, NuGet, npm, GitHub Container Registry.'
parent_provider: github
permalink: /estates/github/
slug: github
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/github/refs/heads/main/apis.yml
subfamilies: []
tags:
- Code
- Developer Tools
- Pipelines
- Platform
- Software Development
- Source Control
- T1
- GitHub
title: GitHub
---
