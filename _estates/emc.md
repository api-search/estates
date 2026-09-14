---
api_total: 0
category: Estates
description: 'EMC Corporation, acquired by Dell Technologies in 2016 and now operating as Dell EMC, builds
  enterprise storage, data management and data protection platforms — ECS/ObjectScale object storage,
  Unity, VNX, PowerMax (VMAX lineage), PowerScale (Isilon) and PowerFlex (ScaleIO). Two management APIs
  are profiled: the ECS Management REST API and the Unisphere REST API. Both are appliance APIs served
  on port 4443 and 8443 by hardware the customer owns, so there is no EMC-operated endpoint, no API key,
  no plan and no rate limit — a fact that shapes every artifact in this repo. ECS is multi-protocol, implementing
  the Amazon S3, OpenStack Swift, EMC Atmos, EMC CAS, HDFS and NFSv3 interfaces, which means an S3-speaking
  application integrates by changing an endpoint rather than writing a connector. No OpenAPI is publicly
  downloadable: Dell publishes references on developer.dell.com, but the portal is a client-rendered SPA
  whose specification API returns HTTP 401 to anonymous callers, so this profile is built from EMC''s
  own published client libraries on github.com/EMCECS and github.com/dell.'
estate_rating:
  agent_avg: 6.8
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 5.7
  composite_avg: 15.8
  composite_band: emerging
  composite_raw: 5.2
  developing: 0
  exemplar: 0
  rating: 12.2
  scored: 3
  spread: 0.7
  strength: 0
  strong: 0
  worst: 5.0
estate_root: dell-technologies
estate_root_name: Dell Technologies
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/emc.png
is_subfamily: true
layout: estate
member_bands:
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id001
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
  - &id002
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
  - &id003
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
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: EMC
overview: 'EMC publishes its API surface across 3 provider profiles indexed on the APIs.io network, of
  which 3 carry a rating. The rated members span 0.7 points, from 5.7 down to 5.0.


  Its highest-rated surfaces are XtremIO, Scaleio, Voyence.'
parent_provider: emc
permalink: /estates/emc/
slug: emc
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/emc/refs/heads/main/apis.yml
subfamilies: []
tags:
- Cloud Infrastructure
- Data Management
- Data Protection
- Enterprise Storage
- Object Storage
- Storage
- S3 Compatible
- Fortune 500
title: EMC
---
