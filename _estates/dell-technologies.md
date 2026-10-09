---
api_total: 20
category: Estates
description: Dell Technologies is a global Fortune 500 technology company that designs, develops, manufactures,
  and supports a wide range of computing products, including PCs, servers, storage, networking equipment,
  and software services. Dell publishes a developer platform exposing APIs and SDKs for managing PowerEdge
  servers, PowerStore storage, PowerScale, OpenManage, APEX, and related infrastructure products, enabling
  automation of IT operations and integration into enterprise tooling.
estate_rating:
  agent_avg: 11.8
  agent_band: emerging
  agent_native: 0
  agent_raw: 13.0
  agent_ready: 1
  band: emerging
  best: 63.0
  composite_avg: 22.8
  composite_band: emerging
  composite_raw: 24.9
  developing: 1
  exemplar: 0
  rating: 18.4
  scored: 6
  spread: 63.0
  strength: 3
  strong: 1
  worst: 0.0
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
    agent_score: 45.8
    api_count: 17
    api_count_basis: published
    immediate_parent: dell-technologies
    name: Moogsoft
    relationship: acquisition
    score_band: strong
    score_composite: 63.0
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
    agent_score: 24.0
    api_count: 1
    api_count_basis: split
    immediate_parent: dell-technologies
    name: DataLoop
    relationship: acquisition
    score_band: developing
    score_composite: 51.2
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
    api_count_basis: split
    immediate_parent: dell-technologies
    name: EMC
    relationship: product
    score_band: thin
    score_composite: 31.9
    slug: emc
    source: parent-company-property
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
    api_count_basis: split
    immediate_parent: emc
    name: Scaleio
    relationship: product
    score_band: minimal
    score_composite: 3.4
    slug: scaleio
    source: parent-company-property
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: emc
    name: Kashya
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: kashya
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: emc
    name: Voyence
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: voyence
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id007
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: emc
    name: XtremIO
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: xtremio
    source: prose
  label: Unrated
  open: false
member_on_network: 7
member_total: 7
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
members_unrated: []
name: Dell Technologies
overview: 'Dell Technologies publishes its API surface across 7 provider profiles indexed on the APIs.io
  network, of which 7 carry a rating. The rated members span 63.0 points, from 63.0 down to 0.0.


  Its highest-rated surfaces are Moogsoft, DataLoop, EMC, Scaleio, Kashya.'
parent_provider: dell-technologies
permalink: /estates/dell-technologies/
slug: dell-technologies
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dell-technologies/refs/heads/main/apis.yml
subfamilies:
- has_page: true
  member_count: 4
  members:
  - name: Scaleio
    score_band: minimal
    score_composite: 3.4
    slug: scaleio
  - name: Kashya
    score_band: minimal
    score_composite: 0.0
    slug: kashya
  - name: Voyence
    score_band: minimal
    score_composite: 0.0
    slug: voyence
  - name: XtremIO
    score_band: null
    score_composite: null
    slug: xtremio
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
