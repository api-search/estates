---
api_total: 21
category: Estates
description: Atlassian is a software company that develops collaboration, productivity, and project management
  tools to help teams work more efficiently. Its products are designed to enhance teamwork, streamline
  workflows, and support project tracking across a wide range of industries.
estate_rating:
  agent_avg: 25.8
  agent_band: thin
  agent_native: 0
  agent_raw: 35.2
  agent_ready: 5
  band: thin
  best: 70.2
  composite_avg: 41.4
  composite_band: developing
  composite_raw: 53.5
  developing: 3
  exemplar: 1
  rating: 35.2
  scored: 8
  spread: 35.7
  strength: 12
  strong: 3
  worst: 34.5
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/atlassian.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 50.2
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
  count: 3
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 47.8
    api_count: 1
    immediate_parent: atlassian
    name: Confluence
    relationship: product
    score_band: strong
    score_composite: 62.1
    slug: confluence
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 34.2
    api_count: 1
    immediate_parent: atlassian
    name: Bitbucket
    relationship: acquisition
    score_band: strong
    score_composite: 60.4
    slug: bitbucket
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 50.7
    api_count: 1
    immediate_parent: atlassian
    name: Jira
    relationship: product
    score_band: strong
    score_composite: 56.3
    slug: jira
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 3
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 19.1
    api_count: 2
    immediate_parent: atlassian
    name: HipChat
    relationship: product
    score_band: developing
    score_composite: 51.3
    slug: hipchat
  - &id006
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
  - &id007
    acquired: null
    agent_band: agent-ready
    agent_score: 33.1
    api_count: 1
    immediate_parent: bitbucket
    name: Bitbucket Pipelines
    relationship: product
    score_band: developing
    score_composite: 45.0
    slug: bitbucket-pipelines
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id008
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
member_on_network: 8
member_total: 8
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
members_unrated: []
name: Atlassian
overview: 'Atlassian publishes its API surface across 8 provider profiles indexed on the APIs.io network,
  of which 8 carry a rating. The rated members span 35.7 points, from 70.2 down to 34.5.


  Its highest-rated surfaces are Atlassian Compass, Confluence, Bitbucket, Jira, HipChat.'
parent_provider: atlassian
permalink: /estates/atlassian/
slug: atlassian
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/atlassian/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Bitbucket Pipelines
    score_band: developing
    score_composite: 45.0
    slug: bitbucket-pipelines
  name: Bitbucket
  on_network: true
  permalink: /estates/bitbucket/
  slug: bitbucket
subfamily_page_count: 0
tags:
- Code
- Collaboration
- Platform
- Productivity
- Software Development
title: Atlassian
---
