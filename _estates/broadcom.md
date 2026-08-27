---
api_total: 87
category: Estates
description: Broadcom is a global technology company that specializes in the design and manufacturing
  of semiconductors and other hardware components for a wide range of industries. They provide a diverse
  portfolio of products for the enterprise, data center, networking, telecommunications, and consumer
  electronics markets. Broadcom's technology is used in a variety of devices such as smartphones, tablets,
  routers, and smart TVs.
estate_rating:
  agent_avg: 11.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 12.0
  agent_ready: 0
  band: emerging
  best: 53.4
  composite_avg: 25.7
  composite_band: thin
  composite_raw: 29.4
  developing: 3
  exemplar: 0
  rating: 19.8
  scored: 6
  spread: 52.8
  strength: 3
  strong: 0
  worst: 0.6
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/broadcom.png
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 3
  items:
  - &id001
    acquired: 2023
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 59
    immediate_parent: broadcom
    name: VMware
    relationship: acquisition
    score_band: developing
    score_composite: 53.4
    slug: vmware
  - &id002
    acquired: 2017
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 12
    immediate_parent: broadcom
    name: Brocade
    relationship: acquisition
    score_band: developing
    score_composite: 46.4
    slug: brocade
  - &id003
    acquired: 2019
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 8
    immediate_parent: broadcom
    name: Symantec
    relationship: acquisition
    score_band: developing
    score_composite: 42.0
    slug: symantec
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id004
    acquired: 2018
    agent_band: human-only
    agent_score: 2.5
    api_count: 6
    immediate_parent: broadcom
    name: CA Technologies (Broadcom)
    relationship: acquisition
    score_band: emerging
    score_composite: 21.3
    slug: ca
  - &id005
    acquired: 2021
    agent_band: human-only
    agent_score: 2.5
    api_count: 2
    immediate_parent: broadcom
    name: AppNeta
    relationship: acquisition
    score_band: emerging
    score_composite: 12.5
    slug: appneta
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id006
    acquired: 2000
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: broadcom
    name: Newport Communications
    relationship: acquisition
    score_band: minimal
    score_composite: 0.6
    slug: newport-communications
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
name: Broadcom
overview: 'Broadcom publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 52.8 points, from 53.4 down to 0.6.


  Its highest-rated surfaces are VMware, Brocade, Symantec, CA Technologies (Broadcom), AppNeta.'
parent_provider: broadcom
permalink: /estates/broadcom/
slug: broadcom
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/apis.yml
tags:
- Cloud Infrastructure
- Gateways
- Management
- Networks
- Observability
- Virtualization
- Fortune 500
title: Broadcom
---
