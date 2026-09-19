---
api_total: 6
category: Estates
description: Cisco Webex is a comprehensive collaboration platform offering APIs for messaging, meetings,
  calling, devices, and contact center workflows. The Webex Developer Platform enables developers to build
  integrations, bots, embedded apps, and automations using REST APIs, SDKs, and webhooks. Webex supports
  OAuth 2.0 authentication and provides separate API surfaces for messaging, video conferencing, cloud
  calling, admin management, and more.
estate_rating:
  agent_avg: 15.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 20.7
  agent_ready: 0
  band: thin
  best: 52.0
  composite_avg: 31.9
  composite_band: thin
  composite_raw: 41.4
  developing: 3
  exemplar: 0
  rating: 25.5
  scored: 5
  spread: 19.8
  strength: 3
  strong: 0
  worst: 32.2
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
    immediate_parent: webex
    name: Cisco Expressway
    relationship: product
    score_band: developing
    score_composite: 52.0
    slug: cisco-expressway
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 24.1
    api_count: 1
    immediate_parent: webex
    name: Cisco Webex Meetings
    relationship: product
    score_band: developing
    score_composite: 46.4
    slug: cisco-webex-meetings
    source: declared
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: webex
    name: Cisco Directory Connector
    relationship: product
    score_band: developing
    score_composite: 40.3
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
    immediate_parent: webex
    name: Cisco Control Hub
    relationship: product
    score_band: thin
    score_composite: 35.9
    slug: cisco-control-hub
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: webex
    name: Cisco Collaboration Hybrid Solutions
    relationship: product
    score_band: thin
    score_composite: 32.2
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
  of which 5 carry a rating. The rated members span 19.8 points, from 52.0 down to 32.2.


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
