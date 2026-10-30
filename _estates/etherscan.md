---
api_total: 6
category: Estates
description: Etherscan is the leading blockchain explorer, search, API, and analytics platform for Ethereum
  and other EVM-compatible chains. It allows users to easily access and explore blockchain data, including
  transaction histories, smart contracts, token balances, and network activity. Etherscan's unified V2
  API covers 60+ chains under a single account and API key, with a free tier offering 100,000 daily calls
  and paid tiers up to enterprise.
estate_rating:
  agent_avg: 19.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 26.9
  agent_ready: 2
  band: emerging
  best: 42.2
  composite_avg: 28.3
  composite_band: thin
  composite_raw: 35.4
  developing: 2
  exemplar: 0
  rating: 24.8
  scored: 6
  spread: 15.9
  strength: 2
  strong: 0
  worst: 26.3
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/etherscan.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 28.7
    api_count: 1
    api_count_basis: published
    immediate_parent: etherscan
    name: Optimism Etherscan
    relationship: product
    score_band: developing
    score_composite: 42.2
    slug: optimistic-etherscan
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 26.6
    api_count: 1
    api_count_basis: published
    immediate_parent: etherscan
    name: Arbiscan
    relationship: product
    score_band: developing
    score_composite: 40.2
    slug: arbiscan
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 4
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 26.4
    api_count: 1
    api_count_basis: published
    immediate_parent: etherscan
    name: BscScan
    relationship: product
    score_band: thin
    score_composite: 37.0
    slug: bscscan
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 26.4
    api_count: 1
    api_count_basis: published
    immediate_parent: etherscan
    name: Basescan
    relationship: product
    score_band: thin
    score_composite: 34.4
    slug: basescan
    source: declared
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 22.9
    api_count: 1
    api_count_basis: published
    immediate_parent: etherscan
    name: PolygonScan
    relationship: product
    score_band: thin
    score_composite: 32.2
    slug: polygonscan
    source: declared
  - &id006
    acquired: 2024
    agent_band: agent-ready
    agent_score: 30.4
    api_count: 1
    api_count_basis: published
    immediate_parent: etherscan
    name: Solscan
    relationship: acquisition
    score_band: thin
    score_composite: 26.3
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
  of which 6 carry a rating. The rated members span 15.9 points, from 42.2 down to 26.3.


  Its highest-rated surfaces are Optimism Etherscan, Arbiscan, BscScan, Basescan, PolygonScan.'
parent_provider: etherscan
permalink: /estates/etherscan/
slug: etherscan
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/etherscan/apis.yml
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
