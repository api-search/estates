---
api_total: 6
category: Estates
description: Cisco Webex is a comprehensive collaboration platform offering APIs for messaging, meetings,
  calling, devices, and contact center workflows. The Webex Developer Platform enables developers to build
  integrations, bots, embedded apps, and automations using REST APIs, SDKs, and webhooks. Webex supports
  OAuth 2.0 authentication and provides separate API surfaces for messaging, video conferencing, cloud
  calling, admin management, and more.
estate_rating:
  agent_avg: 15.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 20.6
  agent_ready: 0
  band: emerging
  best: 53.0
  composite_avg: 30.5
  composite_band: thin
  composite_raw: 40.6
  developing: 3
  exemplar: 0
  rating: 24.5
  scored: 5
  spread: 22.1
  strength: 3
  strong: 0
  worst: 30.9
estate_root: cisco
estate_root_name: Cisco
image: https://developer.webex.com/images/webex-logo.png
is_subfamily: true
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 3
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 2
    api_count_basis: published
    immediate_parent: webex
    name: Cisco Expressway
    relationship: product
    score_band: developing
    score_composite: 53.0
    slug: cisco-expressway
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 23.7
    api_count: 1
    api_count_basis: published
    immediate_parent: webex
    name: Cisco Webex Meetings
    relationship: product
    score_band: developing
    score_composite: 45.1
    slug: cisco-webex-meetings
    source: declared
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    api_count_basis: published
    immediate_parent: webex
    name: Cisco Directory Connector
    relationship: product
    score_band: developing
    score_composite: 40.2
    slug: cisco-directory-connector
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    api_count_basis: published
    immediate_parent: webex
    name: Cisco Control Hub
    relationship: product
    score_band: thin
    score_composite: 33.9
    slug: cisco-control-hub
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    api_count_basis: published
    immediate_parent: webex
    name: Cisco Collaboration Hybrid Solutions
    relationship: product
    score_band: thin
    score_composite: 30.9
    slug: cisco-collaboration-hybrid-solutions
    source: declared
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
name: Webex
overview: 'Webex publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 22.1 points, from 53.0 down to 30.9.


  Its highest-rated surfaces are Cisco Expressway, Cisco Webex Meetings, Cisco Directory Connector, Cisco
  Control Hub, Cisco Collaboration Hybrid Solutions.'
parent_provider: webex
permalink: /estates/webex/
slug: webex
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/apis.yml
subfamilies: []
tags:
- Calling
- Collaboration
- Communications
- Enterprise
- Messaging
- Video Conferencing
title: Webex
---
