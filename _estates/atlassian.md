---
api_total: 49
category: Estates
description: Atlassian is a software company that develops collaboration, productivity, and project management
  tools to help teams work more efficiently. Its products are designed to enhance teamwork, streamline
  workflows, and support project tracking across a wide range of industries.
estate_rating:
  agent_avg: 22.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 27.6
  agent_ready: 4
  band: thin
  best: 75.3
  composite_avg: 35.9
  composite_band: thin
  composite_raw: 44.0
  developing: 2
  exemplar: 4
  rating: 30.3
  scored: 10
  spread: 75.3
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
    agent_score: 65.7
    api_count: 4
    api_count_basis: published
    immediate_parent: atlassian
    name: Jira
    relationship: product
    score_band: exemplar
    score_composite: 75.3
    slug: jira
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 20.2
    api_count: 23
    api_count_basis: split
    immediate_parent: atlassian
    name: Bitbucket
    relationship: acquisition
    score_band: exemplar
    score_composite: 71.4
    slug: bitbucket
    source: declared
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 49.1
    api_count: 2
    api_count_basis: published
    immediate_parent: atlassian
    name: Atlassian Compass
    relationship: product
    score_band: exemplar
    score_composite: 71.3
    slug: atlassian-compass
    source: declared
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 56.9
    api_count: 3
    api_count_basis: published
    immediate_parent: atlassian
    name: Confluence
    relationship: product
    score_band: exemplar
    score_composite: 70.4
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
    agent_score: 27.1
    api_count: 12
    api_count_basis: published
    immediate_parent: atlassian
    name: OpsGenie
    relationship: acquisition
    score_band: developing
    score_composite: 48.0
    slug: opsgenie
    source: declared
  - &id006
    acquired: null
    agent_band: agent-ready
    agent_score: 34.9
    api_count: 1
    api_count_basis: published
    immediate_parent: bitbucket
    name: Bitbucket Pipelines
    relationship: product
    score_band: developing
    score_composite: 45.5
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
    agent_score: 20.1
    api_count: 1
    api_count_basis: published
    immediate_parent: atlassian
    name: Statuspage
    relationship: product
    score_band: thin
    score_composite: 35.1
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
    score_composite: 19.7
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
  of which 10 carry a rating. The rated members span 75.3 points, from 75.3 down to 0.0.


  Its highest-rated surfaces are Jira, Bitbucket, Atlassian Compass, Confluence, OpsGenie.'
parent_provider: atlassian
permalink: /estates/atlassian/
slug: atlassian
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/atlassian/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Bitbucket Pipelines
    score_band: developing
    score_composite: 45.5
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
