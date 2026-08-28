---
api_total: 55
category: Estates
description: Cisco Webex is a comprehensive collaboration platform offering APIs for messaging, meetings,
  calling, devices, and contact center workflows. The Webex Developer Platform enables developers to build
  integrations, bots, embedded apps, and automations using REST APIs, SDKs, and webhooks. Webex supports
  OAuth 2.0 authentication and provides separate API surfaces for messaging, video conferencing, cloud
  calling, admin management, and more.
estate_rating:
  agent_avg: 15.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 20.7
  agent_ready: 0
  band: emerging
  best: 42.8
  composite_avg: 27.0
  composite_band: thin
  composite_raw: 32.6
  developing: 1
  exemplar: 0
  rating: 22.3
  scored: 5
  spread: 18.7
  strength: 1
  strong: 0
  worst: 24.1
image: https://developer.webex.com/images/webex-logo.png
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 18
    immediate_parent: webex
    name: Cisco Expressway
    relationship: product
    score_band: developing
    score_composite: 42.8
    slug: cisco-expressway
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 24.1
    api_count: 14
    immediate_parent: webex
    name: Cisco Webex Meetings
    relationship: product
    score_band: thin
    score_composite: 37.4
    slug: cisco-webex-meetings
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 4
    immediate_parent: webex
    name: Cisco Directory Connector
    relationship: product
    score_band: thin
    score_composite: 31.1
    slug: cisco-directory-connector
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 7
    immediate_parent: webex
    name: Cisco Control Hub
    relationship: product
    score_band: thin
    score_composite: 27.7
    slug: cisco-control-hub
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 12
    immediate_parent: webex
    name: Cisco Collaboration Hybrid Solutions
    relationship: product
    score_band: emerging
    score_composite: 24.1
    slug: cisco-collaboration-hybrid-solutions
  label: Emerging
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
  of which 5 carry a rating. The rated members span 18.7 points, from 42.8 down to 24.1.


  Its highest-rated surfaces are Cisco Expressway, Cisco Webex Meetings, Cisco Directory Connector, Cisco
  Control Hub, Cisco Collaboration Hybrid Solutions.'
parent_provider: webex
permalink: /estates/webex/
slug: webex
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/apis.yml
tags:
- Calling
- Collaboration
- Communications
- Enterprise
- Messaging
- Video Conferencing
title: Webex
---
