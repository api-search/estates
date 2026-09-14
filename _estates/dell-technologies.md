---
api_total: 20
category: Estates
description: Dell Technologies is a global Fortune 500 technology company that designs, develops, manufactures,
  and supports a wide range of computing products, including PCs, servers, storage, networking equipment,
  and software services. Dell publishes a developer platform exposing APIs and SDKs for managing PowerEdge
  servers, PowerStore storage, PowerScale, OpenManage, APEX, and related infrastructure products, enabling
  automation of IT operations and integration into enterprise tooling.
estate_rating:
  agent_avg: 11.1
  agent_band: emerging
  agent_native: 0
  agent_raw: 11.2
  agent_ready: 1
  band: emerging
  best: 61.2
  composite_avg: 24.3
  composite_band: emerging
  composite_raw: 26.2
  developing: 1
  exemplar: 0
  rating: 19.0
  scored: 6
  spread: 56.2
  strength: 3
  strong: 1
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/dell-technologies.png
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
    agent_score: 33.2
    api_count: 17
    immediate_parent: dell-technologies
    name: Moogsoft
    relationship: product
    score_band: strong
    score_composite: 61.2
    slug: moogsoft
    source: prose
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 26.1
    api_count: 1
    immediate_parent: dell-technologies
    name: DataLoop
    relationship: product
    score_band: developing
    score_composite: 49.7
    slug: dataloop
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 7.9
    api_count: 2
    immediate_parent: dell-technologies
    name: EMC
    relationship: product
    score_band: thin
    score_composite: 30.6
    slug: emc
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: emc
    name: XtremIO
    relationship: product
    score_band: minimal
    score_composite: 5.7
    slug: xtremio
    source: prose
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: emc
    name: Scaleio
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: scaleio
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: emc
    name: Voyence
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: voyence
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
name: Dell Technologies
overview: 'Dell Technologies publishes its API surface across 6 provider profiles indexed on the APIs.io
  network, of which 6 carry a rating. The rated members span 56.2 points, from 61.2 down to 5.0.


  Its highest-rated surfaces are Moogsoft, DataLoop, EMC, XtremIO, Scaleio.'
parent_provider: dell-technologies
permalink: /estates/dell-technologies/
slug: dell-technologies
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dell-technologies/refs/heads/main/apis.yml
subfamilies:
- has_page: true
  member_count: 3
  members:
  - name: XtremIO
    score_band: minimal
    score_composite: 5.7
    slug: xtremio
  - name: Scaleio
    score_band: minimal
    score_composite: 5.0
    slug: scaleio
  - name: Voyence
    score_band: minimal
    score_composite: 5.0
    slug: voyence
  name: EMC
  on_network: true
  permalink: /estates/emc/
  slug: emc
subfamily_page_count: 1
tags:
- Enterprise IT
- Infrastructure
- Servers
- Storage
- Cloud
- Automation
title: Dell Technologies
---
