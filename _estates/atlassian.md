---
api_total: 21
category: Estates
description: Atlassian is a software company that develops collaboration, productivity, and project management
  tools to help teams work more efficiently. Its products are designed to enhance teamwork, streamline
  workflows, and support project tracking across a wide range of industries.
estate_rating:
  agent_avg: 24.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 37.9
  agent_ready: 3
  band: thin
  best: 74.3
  composite_avg: 40.4
  composite_band: developing
  composite_raw: 58.7
  developing: 1
  exemplar: 2
  rating: 33.9
  scored: 5
  spread: 39.8
  strength: 9
  strong: 1
  worst: 34.5
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/atlassian.png
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 50.8
    api_count: 2
    immediate_parent: atlassian
    name: Atlassian Confluence
    relationship: product
    score_band: exemplar
    score_composite: 74.3
    slug: atlassian-confluence
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 45.0
    api_count: 2
    immediate_parent: atlassian
    name: Atlassian Compass
    relationship: product
    score_band: exemplar
    score_composite: 70.2
    slug: atlassian-compass
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 47.1
    api_count: 4
    immediate_parent: atlassian
    name: Atlassian Jira
    relationship: product
    score_band: strong
    score_composite: 66.4
    slug: atlassian-jira
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 28.3
    api_count: 12
    immediate_parent: atlassian
    name: OpsGenie
    relationship: acquisition
    score_band: developing
    score_composite: 48.3
    slug: opsgenie
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 18.3
    api_count: 1
    immediate_parent: atlassian
    name: Statuspage
    relationship: product
    score_band: thin
    score_composite: 34.5
    slug: statuspage
  label: Thin
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
name: Atlassian
overview: 'Atlassian publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 39.8 points, from 74.3 down to 34.5.


  Its highest-rated surfaces are Atlassian Confluence, Atlassian Compass, Atlassian Jira, OpsGenie, Statuspage.'
parent_provider: atlassian
permalink: /estates/atlassian/
slug: atlassian
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/atlassian/refs/heads/main/apis.yml
subfamilies: []
tags:
- Code
- Collaboration
- Platform
- Productivity
- Software Development
title: Atlassian
---
