---
api_total: 15
category: Estates
description: Collection of VMware APIs for cloud infrastructure, virtualization, and management solutions
  including vSphere, NSX, vCloud Director, Tanzu, and Aria operations.
estate_rating:
  agent_avg: 6.2
  agent_band: minimal
  agent_native: 0
  agent_raw: 4.6
  agent_ready: 0
  band: emerging
  best: 40.1
  composite_avg: 16.7
  composite_band: emerging
  composite_raw: 14.6
  developing: 1
  exemplar: 0
  rating: 12.5
  scored: 11
  spread: 35.1
  strength: 1
  strong: 0
  worst: 5.0
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/vmware.png
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: 2018
    agent_band: agent-aware
    agent_score: 22.7
    api_count: 8
    immediate_parent: vmware
    name: CloudHealth
    relationship: acquisition
    score_band: developing
    score_composite: 40.1
    slug: cloudhealth
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
    api_count: 5
    immediate_parent: vmware
    name: VMware Tanzu
    relationship: product
    score_band: thin
    score_composite: 37.6
    slug: vmware-tanzu
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id003
    acquired: 2020
    agent_band: agent-aware
    agent_score: 5.4
    api_count: 1
    immediate_parent: vmware
    name: Lastline
    relationship: acquisition
    score_band: emerging
    score_composite: 22.8
    slug: lastline
  - &id004
    acquired: 2019
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: vmware
    name: Carbon Black
    relationship: acquisition
    score_band: emerging
    score_composite: 19.3
    slug: carbon-black
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 7
  items:
  - &id005
    acquired: 2019
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: AVI Networks
    relationship: acquisition
    score_band: minimal
    score_composite: 8.7
    slug: avi-networks
  - &id006
    acquired: 2009
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: SpringSource
    relationship: acquisition
    score_band: minimal
    score_composite: 6.9
    slug: springsource
  - &id007
    acquired: 2018
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Heptio
    relationship: acquisition
    score_band: minimal
    score_composite: 5.3
    slug: heptio
  - &id008
    acquired: 2017
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Apteligent
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: apteligent
  - &id009
    acquired: 2020
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Datrium
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: datrium
  - &id010
    acquired: 2012
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Nicira Networks
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: nicira-networks
  - &id011
    acquired: 2020
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Octarine
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: octarine
  label: Minimal
  open: false
member_on_network: 11
member_total: 11
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
members_unrated: []
name: VMware
overview: 'VMware publishes its API surface across 11 provider profiles indexed on the APIs.io network,
  of which 11 carry a rating. The rated members span 35.1 points, from 40.1 down to 5.0.


  Its highest-rated surfaces are CloudHealth, VMware Tanzu, Lastline, Carbon Black, AVI Networks.'
parent_provider: vmware
permalink: /estates/vmware/
slug: vmware
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vmware/refs/heads/main/apis.yml
tags:
- Cloud Computing
- Container Management
- Hybrid Cloud
- Infrastructure
- Virtualization
title: VMware
---
