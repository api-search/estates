---
api_total: 2
category: Estates
description: Dropbox is a file hosting service operated by the American company Dropbox, Inc., headquartered
  in San Francisco, California, U.S. that offers cloud storage, file synchronization, personal cloud,
  and client software.
estate_rating:
  agent_avg: 13.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 15.3
  agent_ready: 2
  band: emerging
  best: 59.6
  composite_avg: 19.3
  composite_band: emerging
  composite_raw: 18.4
  developing: 1
  exemplar: 0
  rating: 16.9
  scored: 6
  spread: 59.6
  strength: 3
  strong: 1
  worst: 0.0
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
    score_composite: 59.6
    slug: hellosign
    source: parent-company-property
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
    score_composite: 48.5
    slug: docsend
    source: prose
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 4
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
    score_composite: 2.5
    slug: command-e
    source: parent-company-property
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: dropbox
    name: Clementine
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: clementine
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: dropbox
    name: Hackpad
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: hackpad
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: dropbox
    name: PiCloud
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: picloud
    source: prose
  label: Minimal
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
  of which 6 carry a rating. The rated members span 59.6 points, from 59.6 down to 0.0.


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
- Collaboration
- Storage
- Cloud Storage
- File Sharing
title: Dropbox
---
