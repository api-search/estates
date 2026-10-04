---
api_total: 3
category: Estates
description: Bird (formerly MessageBird) is an omnichannel customer communications platform offering REST
  APIs for email, SMS, WhatsApp, RCS, push notifications, voice, and data management. Trusted by more
  than 450,000 developers, Bird provides enterprise-grade connectivity through a global carrier network
  alongside a full customer engagement and marketing automation suite.
estate_rating:
  agent_avg: 12.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 14.7
  agent_ready: 0
  band: emerging
  best: 50.9
  composite_avg: 25.1
  composite_band: thin
  composite_raw: 32.8
  developing: 1
  exemplar: 0
  rating: 19.9
  scored: 3
  spread: 42.1
  strength: 1
  strong: 0
  worst: 8.8
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/bird.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 25.2
    api_count: 1
    immediate_parent: bird
    name: Hull
    relationship: acquisition
    score_band: developing
    score_composite: 50.9
    slug: hull
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 19.0
    api_count: 1
    immediate_parent: bird
    name: Pusher
    relationship: acquisition
    score_band: thin
    score_composite: 38.7
    slug: pusher
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: pusher
    name: Pusher Beams
    relationship: product
    score_band: minimal
    score_composite: 8.8
    slug: pusher-beams
    source: declared
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Bird
overview: 'Bird publishes its API surface across 3 provider profiles indexed on the APIs.io network, of
  which 3 carry a rating. The rated members span 42.1 points, from 50.9 down to 8.8.


  Its highest-rated surfaces are Hull, Pusher, Pusher Beams.'
parent_provider: bird
permalink: /estates/bird/
slug: bird
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bird/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Pusher Beams
    score_band: minimal
    score_composite: 8.8
    slug: pusher-beams
  name: Pusher
  on_network: true
  permalink: /estates/pusher/
  slug: pusher
subfamily_page_count: 0
tags:
- Communications
- SMS
- Email
- WhatsApp
- Voice
- Messaging
- Omnichannel
- Customer Engagement
- Verification
- CPaaS
- Webhook
- Agents
title: Bird
---
