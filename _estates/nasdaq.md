---
api_total: 2
category: Estates
description: 'Nasdaq, Inc. operates the Nasdaq stock exchanges and sells market data, index, and financial
  technology products. Its developer surface is Nasdaq Data Link (data.nasdaq.com): a Tables API (REST,
  api_key, JSON/XML/CSV, 10,000-row pages with cursor and bulk export), a Bulk Download API, a request-based
  REST API for real-time and delayed equities, indexes, ETPs and options (Nasdaq Cloud Data Service, OAuth
  client-credentials, customer-specific base URL), and a Kafka-based Streaming API delivered through first-party
  Java and Python SDKs.'
estate_rating:
  agent_avg: 9.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 8.9
  agent_ready: 0
  band: emerging
  best: 13.9
  composite_avg: 16.0
  composite_band: emerging
  composite_raw: 9.7
  developing: 0
  exemplar: 0
  rating: 13.6
  scored: 3
  spread: 10.5
  strength: 0
  strong: 0
  worst: 3.4
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/nasdaq.png
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id001
    acquired: 2021
    agent_band: agent-aware
    agent_score: 13.3
    api_count: 1
    api_count_basis: split
    immediate_parent: nasdaq
    name: Calypso Workstation
    relationship: acquisition
    score_band: emerging
    score_composite: 13.9
    slug: calypso-workstation
    source: declared
  - &id002
    acquired: 2021
    agent_band: agent-aware
    agent_score: 13.3
    api_count: 1
    api_count_basis: split
    immediate_parent: nasdaq
    name: Calypso Migration
    relationship: acquisition
    score_band: emerging
    score_composite: 11.9
    slug: calypso-migration
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: nasdaq
    name: eVestment Alliance
    relationship: product
    score_band: minimal
    score_composite: 3.4
    slug: evestment-alliance
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Nasdaq
overview: 'Nasdaq publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 10.5 points, from 13.9 down to 3.4.


  Its highest-rated surfaces are Calypso Workstation, Calypso Migration, eVestment Alliance.'
parent_provider: nasdaq
permalink: /estates/nasdaq/
slug: nasdaq
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/nasdaq/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Data Marketplace
- Financial Data
- Fortune 1000
- Kafka
- Market Data
- Stock Exchange
- Streaming
- Financial Services
- Capital Markets
- Economics
title: Nasdaq
---
