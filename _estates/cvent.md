---
api_total: 5
category: Estates
description: Cvent is a leading meetings, events, and hospitality technology provider with over 4,800
  employees and 22,000+ customers worldwide. The Cvent platform spans Event Cloud (event management, registration,
  mobile event apps, virtual and hybrid events, Attendee Hub, surveys, Diagramming, and analytics) and
  Hospitality Cloud (Cvent Supplier Network, Passkey, Venue Sourcing, and Sales & Catering). Programmatic
  access is delivered through the unified Cvent Platform REST API (api-platform.cvent.com) using OAuth
  2.0 client credentials, with legacy SOAP, BadgeKit, Jifflenow, and CSN APIs documented for historical
  integrations. The developer portal at developers.cvent.com hosts API references, guides, OpenAPI downloads,
  webhooks, SSO, custom widgets, white-label, and integration documentation.
estate_rating:
  agent_avg: 23.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 38.8
  agent_ready: 3
  band: thin
  best: 82.0
  composite_avg: 40.8
  composite_band: developing
  composite_raw: 64.3
  developing: 1
  exemplar: 2
  rating: 33.8
  scored: 4
  spread: 41.1
  strength: 9
  strong: 1
  worst: 40.9
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cvent.png
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 38.3
    api_count: 2
    immediate_parent: cvent
    name: Cvent Registration
    relationship: product
    score_band: exemplar
    score_composite: 82.0
    slug: cvent-registration
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 46.1
    api_count: 2
    immediate_parent: cvent
    name: Cvent Event Cloud
    relationship: product
    score_band: exemplar
    score_composite: 69.9
    slug: cvent-event-cloud
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 53.2
    api_count: 1
    immediate_parent: cvent
    name: Cvent Hospitality Cloud
    relationship: product
    score_band: strong
    score_composite: 64.3
    slug: cvent-hospitality-cloud
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 17.6
    api_count: 0
    immediate_parent: cvent
    name: Cvent Community
    relationship: product
    score_band: developing
    score_composite: 40.9
    slug: cvent-community
  label: Developing
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Cvent
overview: 'Cvent publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 41.1 points, from 82.0 down to 40.9.


  Its highest-rated surfaces are Cvent Registration, Cvent Event Cloud, Cvent Hospitality Cloud, Cvent
  Community.'
parent_provider: cvent
permalink: /estates/cvent/
slug: cvent
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cvent/refs/heads/main/apis.yml
subfamilies: []
tags:
- Attendee Hub
- Attendee Management
- Conferences
- Diagramming
- Event Management
- Event Marketing
- Event
- Exhibitors
- Hospitality
- Hospitality Cloud
- Hybrid Events
- Meetings
title: Cvent
---
