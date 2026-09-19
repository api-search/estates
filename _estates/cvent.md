---
api_total: 22
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
  agent_avg: 20.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 28.3
  agent_ready: 3
  band: thin
  best: 79.5
  composite_avg: 37.8
  composite_band: thin
  composite_raw: 50.5
  developing: 1
  exemplar: 2
  rating: 30.9
  scored: 6
  spread: 63.9
  strength: 9
  strong: 1
  worst: 15.6
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cvent.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 42.6
    api_count: 2
    immediate_parent: cvent
    name: Cvent Registration
    relationship: product
    score_band: exemplar
    score_composite: 79.5
    slug: cvent-registration
    source: declared
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
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 55.8
    api_count: 17
    immediate_parent: cvent
    name: Cvent Hospitality Cloud
    relationship: product
    score_band: strong
    score_composite: 64.4
    slug: cvent-hospitality-cloud
    source: declared
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
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 7.9
    api_count: 1
    immediate_parent: cvent
    name: Jifflenow
    relationship: product
    score_band: thin
    score_composite: 32.9
    slug: jifflenow
    source: prose
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cvent
    name: DoubleDutch
    relationship: product
    score_band: emerging
    score_composite: 15.6
    slug: doubledutch
    source: prose
  label: Emerging
  open: false
member_on_network: 6
member_total: 6
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
members_unrated: []
name: Cvent
overview: 'Cvent publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 63.9 points, from 79.5 down to 15.6.


  Its highest-rated surfaces are Cvent Registration, Cvent Event Cloud, Cvent Hospitality Cloud, Cvent
  Community, Jifflenow.'
parent_provider: cvent
permalink: /estates/cvent/
slug: cvent
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cvent/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
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
