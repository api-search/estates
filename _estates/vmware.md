---
api_total: 12
category: Estates
description: Collection of VMware APIs for cloud infrastructure, virtualization, and management solutions
  including vSphere, NSX, vCloud Director, Tanzu, and Aria operations.
estate_rating:
  agent_avg: 9.4
  agent_band: minimal
  agent_native: 0
  agent_raw: 8.3
  agent_ready: 1
  band: emerging
  best: 57.6
  composite_avg: 21.2
  composite_band: emerging
  composite_raw: 20.4
  developing: 0
  exemplar: 0
  rating: 16.5
  scored: 8
  spread: 52.6
  strength: 2
  strong: 1
  worst: 5.0
estate_root: broadcom
estate_root_name: Broadcom
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/vmware.png
is_subfamily: true
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: 2018
    agent_band: agent-ready
    agent_score: 38.9
    api_count: 8
    immediate_parent: vmware
    name: CloudHealth
    relationship: acquisition
    score_band: strong
    score_composite: 57.6
    slug: cloudhealth
    source: declared
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 2
    immediate_parent: vmware
    name: VMware Tanzu
    relationship: product
    score_band: thin
    score_composite: 36.4
    slug: vmware-tanzu
    source: declared
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
    score_composite: 23.5
    slug: lastline
    source: declared
  - &id004
    acquired: 2019
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: vmware
    name: Carbon Black
    relationship: acquisition
    score_band: emerging
    score_composite: 19.8
    slug: carbon-black
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 4
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
    source: declared
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
    source: declared
  - &id007
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
    source: declared
  - &id008
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
    source: declared
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 4
  items:
  - &id009
    acquired: 2017
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: vmware
    name: Apteligent
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: apteligent
    source: declared
  - &id010
    acquired: 2016
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: carbon-black
    name: Confer Technologies
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: confer
    source: declared
  - &id011
    acquired: 2020
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: vmware
    name: Datrium
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: datrium
    source: declared
  - &id012
    acquired: 2018
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: vmware
    name: Heptio
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: heptio
    source: declared
  label: Unrated
  open: false
member_on_network: 12
member_total: 12
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
members_unrated: []
name: VMware
overview: 'VMware publishes its API surface across 12 provider profiles indexed on the APIs.io network,
  of which 12 carry a rating. The rated members span 52.6 points, from 57.6 down to 5.0.


  Its highest-rated surfaces are CloudHealth, VMware Tanzu, Lastline, Carbon Black, AVI Networks.'
parent_provider: vmware
permalink: /estates/vmware/
slug: vmware
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vmware/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Confer Technologies
    score_band: null
    score_composite: null
    slug: confer
  name: Carbon Black
  on_network: true
  permalink: /estates/carbon-black/
  slug: carbon-black
tags:
- Cloud Computing
- Container Management
- Hybrid Cloud
- Infrastructure
- Virtualization
- VMware
title: VMware
---
