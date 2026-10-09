---
api_total: 3
category: Estates
description: Visa is a global payment technology company that facilitates electronic funds transfers by
  providing consumers, businesses, and governments with secure, convenient, and reliable payment solutions.
  Through its network of financial institutions and partners, Visa enables individuals to make purchases,
  transfer money, and access other financial services in over 200 countries and territories worldwide.
  The Visa Developer platform provides APIs for money movement (Visa Direct), merchant intelligence, account
  validation, transaction controls, foreign exchange, digital wallets, tokenization, and more.
estate_rating:
  agent_avg: 12.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 14.5
  agent_ready: 1
  band: emerging
  best: 57.2
  composite_avg: 22.2
  composite_band: emerging
  composite_raw: 24.5
  developing: 0
  exemplar: 0
  rating: 18.2
  scored: 4
  spread: 55.3
  strength: 2
  strong: 1
  worst: 1.9
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/visa.png
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
    agent_score: 38.2
    api_count: 2
    api_count_basis: published
    immediate_parent: visa
    name: Currencycloud
    relationship: product
    score_band: strong
    score_composite: 57.2
    slug: currencycloud
    source: prose
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
    api_count: 1
    api_count_basis: published
    immediate_parent: visa
    name: Pismo
    relationship: acquisition
    score_band: thin
    score_composite: 32.1
    slug: pismo
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: visa
    name: Featurespace
    relationship: acquisition
    score_band: minimal
    score_composite: 6.8
    slug: featurespace
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: visa
    name: Payworks
    relationship: product
    score_band: minimal
    score_composite: 1.9
    slug: payworks
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Visa
overview: 'Visa publishes its API surface across 4 provider profiles indexed on the APIs.io network, of
  which 4 carry a rating. The rated members span 55.3 points, from 57.2 down to 1.9.


  Its highest-rated surfaces are Currencycloud, Pismo, Featurespace, Payworks.'
parent_provider: visa
permalink: /estates/visa/
slug: visa
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/visa/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Visa
- Account
- Banking
- Credit Cards
- Digital Commerce
- Digital Wallet
- Fintech
- Foreign Exchange
- Fraud Prevention
- Merchants
- Money Movement
- Payments
title: Visa
---
