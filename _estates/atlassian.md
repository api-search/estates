---
api_total: 27
category: Estates
description: Atlassian is a software company that develops collaboration, productivity, and project management
  tools to help teams work more efficiently. Its products are designed to enhance teamwork, streamline
  workflows, and support project tracking across a wide range of industries.
estate_rating:
  agent_avg: 22.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 28.2
  agent_ready: 5
  band: thin
  best: 76.3
  composite_avg: 36.2
  composite_band: thin
  composite_raw: 44.2
  developing: 2
  exemplar: 4
  rating: 30.6
  scored: 10
  spread: 76.3
  strength: 14
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/atlassian.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 4
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 65.6
    api_count: 4
    api_count_basis: published
    immediate_parent: atlassian
    name: Jira
    relationship: product
    score_band: exemplar
    score_composite: 76.3
    slug: jira
    source: declared
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 48.0
    api_count: 2
    api_count_basis: published
    immediate_parent: atlassian
    name: Atlassian Compass
    relationship: product
    score_band: exemplar
    score_composite: 72.6
    slug: atlassian-compass
    source: declared
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 34.2
    api_count: 1
    api_count_basis: published
    immediate_parent: atlassian
    name: Bitbucket
    relationship: acquisition
    score_band: exemplar
    score_composite: 70.6
    slug: bitbucket
    source: declared
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 54.4
    api_count: 3
    api_count_basis: published
    immediate_parent: atlassian
    name: Confluence
    relationship: product
    score_band: exemplar
    score_composite: 70.6
    slug: confluence
    source: declared
  label: Exemplar
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 28.3
    api_count: 12
    api_count_basis: published
    immediate_parent: atlassian
    name: OpsGenie
    relationship: acquisition
    score_band: developing
    score_composite: 48.1
    slug: opsgenie
    source: declared
  - &id006
    acquired: null
    agent_band: agent-ready
    agent_score: 31.2
    api_count: 1
    api_count_basis: published
    immediate_parent: bitbucket
    name: Bitbucket Pipelines
    relationship: product
    score_band: developing
    score_composite: 45.7
    slug: bitbucket-pipelines
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id007
    acquired: null
    agent_band: agent-aware
    agent_score: 18.3
    api_count: 1
    api_count_basis: published
    immediate_parent: atlassian
    name: Statuspage
    relationship: product
    score_band: thin
    score_composite: 33.6
    slug: statuspage
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
    api_count_basis: split
    immediate_parent: atlassian
    name: Optic
    relationship: acquisition
    score_band: emerging
    score_composite: 21.0
    slug: optic
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id009
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: atlassian
    name: Wikidocs
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: wikidocs
    source: prose
  - &id010
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 2
    api_count_basis: split
    immediate_parent: atlassian
    name: HipChat
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: hipchat
    source: declared
  label: Minimal
  open: false
member_on_network: 10
member_total: 10
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
members_unrated: []
name: Atlassian
overview: 'Atlassian publishes its API surface across 10 provider profiles indexed on the APIs.io network,
  of which 10 carry a rating. The rated members span 76.3 points, from 76.3 down to 0.0.


  Its highest-rated surfaces are Jira, Atlassian Compass, Bitbucket, Confluence, OpsGenie.'
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
    score_composite: 45.7
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
- Atlassian
- Australia
- A2A
title: Atlassian
---
