---
api_total: 3
category: Estates
description: Vonage (part of Ericsson) provides cloud communications APIs for voice, SMS, messaging, video,
  and verification. The Vonage API platform enables businesses to embed communication capabilities into
  applications including voice calls, SMS, multi-channel messaging (WhatsApp, Messenger, Viber, RCS),
  video conferencing, and two-factor authentication. SDKs are available for Node.js, Python, Java, PHP,
  Ruby, .NET, Go, and Kotlin.
estate_rating:
  agent_avg: 14.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 21.1
  agent_ready: 0
  band: emerging
  best: 44.2
  composite_avg: 24.6
  composite_band: emerging
  composite_raw: 32.7
  developing: 1
  exemplar: 0
  rating: 20.6
  scored: 3
  spread: 18.9
  strength: 1
  strong: 0
  worst: 25.3
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/vonage.png
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
    agent_score: 22.8
    api_count: 1
    api_count_basis: split
    immediate_parent: vonage
    name: TokBox
    relationship: product
    score_band: developing
    score_composite: 44.2
    slug: tokbox
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
    agent_score: 19.8
    api_count: 1
    api_count_basis: split
    immediate_parent: vonage
    name: NewVoiceMedia
    relationship: product
    score_band: thin
    score_composite: 28.6
    slug: newvoicemedia
    source: parent-company-property
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 20.7
    api_count: 1
    api_count_basis: published
    immediate_parent: vonage
    name: Vonage Video API
    relationship: product
    score_band: emerging
    score_composite: 25.3
    slug: vonage-video
    source: declared
  label: Emerging
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Vonage
overview: 'Vonage publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 18.9 points, from 44.2 down to 25.3.


  Its highest-rated surfaces are TokBox, NewVoiceMedia, Vonage Video API.'
parent_provider: vonage
permalink: /estates/vonage/
slug: vonage
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/vonage/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Communications
- Messaging
- Telecommunications
- Video Conferencing
- Voice
- SMS
- Verification
- Real-Time
title: Vonage
---
