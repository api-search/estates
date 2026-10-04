---
api_total: 13
category: Estates
description: Hewlett Packard Enterprise (HPE) is a global edge-to-cloud technology company providing servers,
  storage, networking, and hybrid cloud services, with HPE GreenLake serving as the unified edge-to-cloud
  platform delivering infrastructure as a service. The HPE GreenLake developer platform exposes OpenAPI
  3.0 REST APIs covering compute, storage, networking, data services, identity, and workspace management,
  all authenticated via OAuth 2.0 client credentials and bearer tokens through a unified global API gateway.
estate_rating:
  agent_avg: 10.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.0
  agent_ready: 2
  band: emerging
  best: 60.2
  composite_avg: 19.8
  composite_band: emerging
  composite_raw: 19.6
  developing: 1
  exemplar: 0
  rating: 15.9
  scored: 16
  spread: 60.2
  strength: 5
  strong: 2
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/hpe.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 35.3
    api_count: 6
    immediate_parent: hpe
    name: Juniper Networks
    relationship: product
    score_band: strong
    score_composite: 60.2
    slug: juniper
    source: declared
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 29.3
    api_count: 1
    immediate_parent: juniper
    name: Mist
    relationship: product
    score_band: strong
    score_composite: 60.2
    slug: mist
    source: parent-company-property
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 28.4
    api_count: 1
    immediate_parent: juniper
    name: Juniper Mist AI
    relationship: acquisition
    score_band: developing
    score_composite: 45.7
    slug: mist-ai
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id004
    acquired: 2020
    agent_band: agent-aware
    agent_score: 25.2
    api_count: 1
    immediate_parent: juniper
    name: 128 Technology
    relationship: acquisition
    score_band: thin
    score_composite: 37.1
    slug: 128-technology
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 23.1
    api_count: 1
    immediate_parent: hpe
    name: SimpliVity
    relationship: product
    score_band: thin
    score_composite: 31.1
    slug: simplivity
    source: declared
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 1
    immediate_parent: hpe
    name: Pachyderm
    relationship: acquisition
    score_band: thin
    score_composite: 26.5
    slug: pachyderm
    source: prose
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: hpe
    name: Nimble Storage
    relationship: product
    score_band: emerging
    score_composite: 17.9
    slug: nimble-storage
    source: parent-company-property
  - &id008
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: hpe
    name: 3PAR (HPE 3PAR StoreServ)
    relationship: product
    score_band: emerging
    score_composite: 12.2
    slug: 3par
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 8
  items:
  - &id009
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: juniper
    name: BTI Systems (Juniper)
    relationship: product
    score_band: minimal
    score_composite: 8.6
    slug: bti-systems-juniper
    source: declared
  - &id010
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: hpe
    name: Axis Security
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: axis-security
    source: prose
  - &id011
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: hpe
    name: CloudPhysics
    relationship: product
    score_band: minimal
    score_composite: 3.4
    slug: cloudphysics
    source: parent-company-property
  - &id012
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: hpe
    name: Cray
    relationship: product
    score_band: minimal
    score_composite: 3.4
    slug: cray
    source: prose
  - &id013
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: hpe
    name: TidalScale
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: tidalscale
    source: prose
  - &id014
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: juniper
    name: Argon Networks
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: argon
    source: parent-company-property
  - &id015
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: juniper
    name: Peribit
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: peribit
    source: parent-company-property
  - &id016
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: hpe
    name: SGI (Silicon Graphics)
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: sgi
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id017
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: hpe
    name: Bluedata Software Inc
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: bluedata-software-inc
    source: prose
  label: Unrated
  open: false
member_on_network: 17
member_total: 17
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
- *id009
- *id010
- *id011
- *id012
- *id013
- *id014
- *id015
- *id016
- *id017
members_unrated: []
name: Hewlett Packard Enterprise
overview: 'Hewlett Packard Enterprise publishes its API surface across 17 provider profiles indexed on
  the APIs.io network, of which 17 carry a rating. The rated members span 60.2 points, from 60.2 down
  to 0.0.


  Its highest-rated surfaces are Juniper Networks, Mist, Juniper Mist AI, 128 Technology, SimpliVity.'
parent_provider: hpe
permalink: /estates/hpe/
slug: hpe
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hpe/refs/heads/main/apis.yml
subfamilies:
- has_page: true
  member_count: 6
  members:
  - name: Mist
    score_band: strong
    score_composite: 60.2
    slug: mist
  - name: Juniper Mist AI
    score_band: developing
    score_composite: 45.7
    slug: mist-ai
  - name: 128 Technology
    score_band: thin
    score_composite: 37.1
    slug: 128-technology
  - name: BTI Systems (Juniper)
    score_band: minimal
    score_composite: 8.6
    slug: bti-systems-juniper
  - name: Argon Networks
    score_band: minimal
    score_composite: 0.0
    slug: argon
  - name: Peribit
    score_band: minimal
    score_composite: 0.0
    slug: peribit
  name: Juniper Networks
  on_network: true
  permalink: /estates/juniper/
  slug: juniper
subfamily_page_count: 1
tags:
- Cloud
- Edge to Cloud
- Infrastructure-as-a-Service
- Compute
- Storage
- Networking
- Hybrid Cloud
- Enterprise IT
- Data Center
title: Hewlett Packard Enterprise
---
