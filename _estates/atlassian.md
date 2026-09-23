---
api_total: 27
category: Estates
description: Atlassian is a software company that develops collaboration, productivity, and project management
  tools to help teams work more efficiently. Its products are designed to enhance teamwork, streamline
  workflows, and support project tracking across a wide range of industries.
estate_rating:
  agent_avg: 24.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 30.4
  agent_ready: 5
  band: thin
  best: 73.5
  composite_avg: 39.9
  composite_band: thin
  composite_raw: 48.5
  developing: 3
  exemplar: 4
  rating: 33.6
  scored: 10
  spread: 68.5
  strength: 15
  strong: 0
  worst: 5.0
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
    immediate_parent: atlassian
    name: Jira
    relationship: product
    score_band: exemplar
    score_composite: 73.5
    slug: jira
    source: declared
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 48.0
    api_count: 2
    immediate_parent: atlassian
    name: Atlassian Compass
    relationship: product
    score_band: exemplar
    score_composite: 69.7
    slug: atlassian-compass
    source: declared
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 34.2
    api_count: 1
    immediate_parent: atlassian
    name: Bitbucket
    relationship: acquisition
    score_band: exemplar
    score_composite: 67.8
    slug: bitbucket
    source: declared
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 54.4
    api_count: 3
    immediate_parent: atlassian
    name: Confluence
    relationship: product
    score_band: exemplar
    score_composite: 67.4
    slug: confluence
    source: declared
  label: Exemplar
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
    source: declared
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
    source: declared
  - &id007
    acquired: null
    agent_band: agent-ready
    agent_score: 33.1
    api_count: 1
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
  - &id008
    acquired: null
    agent_band: agent-aware
    agent_score: 18.3
    api_count: 1
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
  - &id009
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: atlassian
    name: Optic
    relationship: product
    score_band: emerging
    score_composite: 21.1
    slug: optic
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id010
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: atlassian
    name: Wikidocs
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: wikidocs
    source: prose
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
  of which 10 carry a rating. The rated members span 68.5 points, from 73.5 down to 5.0.


  Its highest-rated surfaces are Jira, Atlassian Compass, Bitbucket, Confluence, HipChat.'
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
title: Atlassian
---
