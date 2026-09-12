---
api_total: 3
category: Estates
description: Nvidia is a Fortune 500 company that provides developer APIs and integration capabilities
  through its developer platform. NVIDIA provides developer APIs for GPU computing, AI/ML model training
  and inference, and graphics. The platform includes APIs for CUDA, TensorRT, Omniverse, and cloud GPU
  services.
estate_rating:
  agent_avg: 6.1
  agent_band: minimal
  agent_native: 0
  agent_raw: 3.5
  agent_ready: 0
  band: emerging
  best: 41.7
  composite_avg: 14.8
  composite_band: emerging
  composite_raw: 10.8
  developing: 1
  exemplar: 0
  rating: 11.3
  scored: 9
  spread: 36.7
  strength: 1
  strong: 0
  worst: 5.0
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/nvidia.png
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: 2024
    agent_band: agent-aware
    agent_score: 27.5
    api_count: 1
    immediate_parent: nvidia
    name: NVIDIA Run:ai
    relationship: acquisition
    score_band: developing
    score_composite: 41.7
    slug: runai
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: 2025
    agent_band: human-only
    agent_score: 3.8
    api_count: 1
    immediate_parent: nvidia
    name: Lepton AI
    relationship: acquisition
    score_band: emerging
    score_composite: 14.1
    slug: lepton-ai
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 7
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nvidia
    name: Cumulus Networks
    relationship: acquisition
    score_band: minimal
    score_composite: 7.2
    slug: cumulus-networks
  - &id004
    acquired: 2022
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nvidia
    name: Excelero Storage
    relationship: acquisition
    score_band: minimal
    score_composite: 6.9
    slug: excelero-storage
  - &id005
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nvidia
    name: Deci AI
    relationship: acquisition
    score_band: minimal
    score_composite: 6.8
    slug: deci-ai
  - &id006
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nvidia
    name: Augtera Networks
    relationship: acquisition
    score_band: minimal
    score_composite: 5.3
    slug: augtera-networks
  - &id007
    acquired: 2021
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nvidia
    name: DeepMap
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: deepmap
  - &id008
    acquired: 2011
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nvidia
    name: icerasemi
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: icerasemi
  - &id009
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: nvidia
    name: SwiftStack
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: swiftstack
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id010
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 1
    immediate_parent: nvidia
    name: Shoreline
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: shoreline
  label: Unrated
  open: false
member_on_network: 10
member_total: 10
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
members_unrated: []
name: Nvidia
overview: 'Nvidia publishes its API surface across 10 provider profiles indexed on the APIs.io network,
  of which 10 carry a rating. The rated members span 36.7 points, from 41.7 down to 5.0.


  Its highest-rated surfaces are NVIDIA Run:ai, Lepton AI, Cumulus Networks, Excelero Storage, Deci AI.'
parent_provider: nvidia
permalink: /estates/nvidia/
slug: nvidia
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nvidia/refs/heads/main/apis.yml
subfamilies: []
tags:
- GPU
- Artificial Intelligence
- Machine-Learning
- Computing
- Graphics
- Fortune 1000
title: Nvidia
---
