---
api_total: 16
category: Estates
description: Autodesk is a global leader in design, engineering, and entertainment software, providing
  cloud-connected platform APIs through Autodesk Platform Services (APS). APS APIs enable developers to
  build applications that access design data, automate workflows, visualize 3D models, manage construction
  projects, create digital twins, and integrate sustainability data across Autodesk's product ecosystem
  including AutoCAD, Revit, Inventor, Maya, BIM 360, and Autodesk Construction Cloud.
estate_rating:
  agent_avg: 14.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 17.1
  agent_ready: 1
  band: emerging
  best: 50.2
  composite_avg: 30.3
  composite_band: thin
  composite_raw: 36.1
  developing: 4
  exemplar: 0
  rating: 24.0
  scored: 7
  spread: 45.2
  strength: 4
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/autodesk.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 4
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 27.2
    api_count: 2
    immediate_parent: autodesk
    name: Autodesk Construction Cloud
    relationship: product
    score_band: developing
    score_composite: 50.2
    slug: autodesk-construction-cloud
    source: declared
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 3.8
    api_count: 2
    immediate_parent: autodesk
    name: Autodesk PowerMill
    relationship: product
    score_band: developing
    score_composite: 45.3
    slug: autodesk-powermill
    source: declared
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 33.1
    api_count: 8
    immediate_parent: autodesk
    name: Autodesk Fusion
    relationship: product
    score_band: developing
    score_composite: 43.4
    slug: autodesk-fusion
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 2
    immediate_parent: autodesk
    name: Autodesk BIM 360
    relationship: product
    score_band: developing
    score_composite: 41.6
    slug: autodesk-bim360
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: autodesk
    name: Prodsmart
    relationship: product
    score_band: thin
    score_composite: 36.4
    slug: prodsmart
    source: prose
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 10.8
    api_count: 1
    immediate_parent: autodesk-construction-cloud
    name: Buildingconnected
    relationship: product
    score_band: thin
    score_composite: 30.7
    slug: buildingconnected
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: autodesk
    name: Spacemaker
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: spacemaker
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id008
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: autodesk
    name: Socialcam
    relationship: product
    score_band: null
    score_composite: null
    slug: socialcam
    source: prose
  label: Unrated
  open: false
member_on_network: 8
member_total: 8
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
members_unrated: []
name: Autodesk
overview: 'Autodesk publishes its API surface across 8 provider profiles indexed on the APIs.io network,
  of which 8 carry a rating. The rated members span 45.2 points, from 50.2 down to 5.0.


  Its highest-rated surfaces are Autodesk Construction Cloud, Autodesk PowerMill, Autodesk Fusion, Autodesk
  BIM 360, Prodsmart.'
parent_provider: autodesk
permalink: /estates/autodesk/
slug: autodesk
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/autodesk/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Buildingconnected
    score_band: thin
    score_composite: 30.7
    slug: buildingconnected
  name: Autodesk Construction Cloud
  on_network: true
  permalink: /estates/autodesk-construction-cloud/
  slug: autodesk-construction-cloud
subfamily_page_count: 0
tags:
- Fortune 1000
- 3D Modeling
- Architecture
- BIM
- CAD
- Construction
- Design
- Digital Twins
- Engineering
- Manufacturing
- Media and Entertainment
- Sustainability
title: Autodesk
---
