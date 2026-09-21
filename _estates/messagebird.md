---
api_total: 3
category: Estates
description: 'MessageBird, which trades as Bird, is a Dutch cloud communications company whose platform
  carries email, SMS, WhatsApp, RCS, push, voice and eSIM traffic for businesses in over 200 countries.
  Bird publishes a first-party OpenAPI 3.1 description of 277 operations at bird.com/openapi.json and
  generates its TypeScript, Python, Go and PHP SDKs from it. The platform is unusually agent-native: a
  hosted MCP server at mcp.bird.com behind credential-less OAuth, a bird CLI with JSON output and semantic
  exit codes, published agent skills shipped as an Agent Plugins marketplace plugin, an RFC 9727 api-catalog,
  an Agentic Resource Discovery document, an llms.txt, and a Markdown twin of every documentation page.
  One auth model, one opt-in Idempotency-Key contract, IETF RateLimit headers and one stable error envelope
  span every channel. The legacy MessageBird REST API at rest.messagebird.com is still served alongside
  it.'
estate_rating:
  agent_avg: 13.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 15.4
  agent_ready: 0
  band: emerging
  best: 50.1
  composite_avg: 26.7
  composite_band: thin
  composite_raw: 33.3
  developing: 2
  exemplar: 0
  rating: 21.2
  scored: 3
  spread: 40.4
  strength: 2
  strong: 0
  worst: 9.7
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/messagebird.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 25.2
    api_count: 1
    immediate_parent: messagebird
    name: Hull
    relationship: product
    score_band: developing
    score_composite: 50.1
    slug: hull
    source: prose
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 20.9
    api_count: 1
    immediate_parent: messagebird
    name: Pusher
    relationship: product
    score_band: developing
    score_composite: 40.1
    slug: pusher
    source: prose
  label: Developing
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
    score_composite: 9.7
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
name: Messagebird
overview: 'Messagebird publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 40.4 points, from 50.1 down to 9.7.


  Its highest-rated surfaces are Hull, Pusher, Pusher Beams.'
parent_provider: messagebird
permalink: /estates/messagebird/
slug: messagebird
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Pusher Beams
    score_band: minimal
    score_composite: 9.7
    slug: pusher-beams
  name: Pusher
  on_network: true
  permalink: /estates/pusher/
  slug: pusher
subfamily_page_count: 0
tags:
- Communications
- Messaging
- SMS
- Email
- WhatsApp
- Voice
- Verification
- CPaaS
- Webhook
- Agents
title: Messagebird
---
