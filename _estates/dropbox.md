---
api_total: 2
category: Estates
description: Dropbox is a file hosting service operated by the American company Dropbox, Inc., headquartered
  in San Francisco, California, U.S. that offers cloud storage, file synchronization, personal cloud,
  and client software.
estate_rating:
  agent_avg: 18.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 30.6
  agent_ready: 2
  band: emerging
  best: 56.7
  composite_avg: 27.3
  composite_band: thin
  composite_raw: 35.5
  developing: 1
  exemplar: 0
  rating: 23.7
  scored: 3
  spread: 51.7
  strength: 3
  strong: 1
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/dropbox.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 44.8
    api_count: 1
    immediate_parent: dropbox
    name: Dropbox Sign (HelloSign)
    relationship: product
    score_band: strong
    score_composite: 56.7
    slug: hellosign
    source: prose
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 47.1
    api_count: 1
    immediate_parent: dropbox
    name: DocSend
    relationship: product
    score_band: developing
    score_composite: 44.8
    slug: docsend
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
    api_count: 0
    immediate_parent: dropbox
    name: Command E
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: command-e
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 3
  items:
  - &id004
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: dropbox
    name: Clementine
    relationship: product
    score_band: null
    score_composite: null
    slug: clementine
    source: prose
  - &id005
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: dropbox
    name: Hackpad
    relationship: product
    score_band: null
    score_composite: null
    slug: hackpad
    source: prose
  - &id006
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: dropbox
    name: PiCloud
    relationship: product
    score_band: null
    score_composite: null
    slug: picloud
    source: prose
  label: Unrated
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
name: Dropbox
overview: 'Dropbox publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 51.7 points, from 56.7 down to 5.0.


  Its highest-rated surfaces are Dropbox Sign (HelloSign), DocSend, Command E, Clementine, Hackpad.'
parent_provider: dropbox
permalink: /estates/dropbox/
slug: dropbox
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dropbox/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Documents
title: Dropbox
---
