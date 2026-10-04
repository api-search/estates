---
api_total: 6
category: Estates
description: Etherscan is the leading blockchain explorer, search, API, and analytics platform for Ethereum
  and other EVM-compatible chains. It allows users to easily access and explore blockchain data, including
  transaction histories, smart contracts, token balances, and network activity. Etherscan's unified V2
  API covers 60+ chains under a single account and API key, with a free tier offering 100,000 daily calls
  and paid tiers up to enterprise.
estate_rating:
  agent_avg: 19.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 26.4
  agent_ready: 3
  band: thin
  best: 49.1
  composite_avg: 31.7
  composite_band: thin
  composite_raw: 41.2
  developing: 4
  exemplar: 0
  rating: 26.7
  scored: 6
  spread: 21.3
  strength: 4
  strong: 0
  worst: 27.8
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/etherscan.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 4
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 28.7
    api_count: 1
    immediate_parent: etherscan
    name: Optimism Etherscan
    relationship: product
    score_band: developing
    score_composite: 49.1
    slug: optimistic-etherscan
    source: declared
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 28.7
    api_count: 1
    immediate_parent: etherscan
    name: Arbiscan
    relationship: product
    score_band: developing
    score_composite: 47.1
    slug: arbiscan
    source: declared
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 1
    immediate_parent: etherscan
    name: Basescan
    relationship: product
    score_band: developing
    score_composite: 42.7
    slug: basescan
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 1
    immediate_parent: etherscan
    name: BscScan
    relationship: product
    score_band: developing
    score_composite: 41.3
    slug: bscscan
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
    agent_score: 22.9
    api_count: 1
    immediate_parent: etherscan
    name: PolygonScan
    relationship: product
    score_band: thin
    score_composite: 39.1
    slug: polygonscan
    source: declared
  - &id006
    acquired: 2024
    agent_band: agent-ready
    agent_score: 28.6
    api_count: 1
    immediate_parent: etherscan
    name: Solscan
    relationship: acquisition
    score_band: thin
    score_composite: 27.8
    slug: solscan
    source: declared
  label: Thin
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
name: Etherscan
overview: 'Etherscan publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 21.3 points, from 49.1 down to 27.8.


  Its highest-rated surfaces are Optimism Etherscan, Arbiscan, Basescan, BscScan, PolygonScan.'
parent_provider: etherscan
permalink: /estates/etherscan/
slug: etherscan
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/etherscan/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Blockchain
- Cryptocurrency
- Ethereum
- EVM
- Web3
title: Etherscan
---
