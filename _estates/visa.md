---
api_total: 2
category: Estates
description: Visa is a global payment technology company that facilitates electronic funds transfers by
  providing consumers, businesses, and governments with secure, convenient, and reliable payment solutions.
  Through its network of financial institutions and partners, Visa enables individuals to make purchases,
  transfer money, and access other financial services in over 200 countries and territories worldwide.
  The Visa Developer platform provides APIs for money movement (Visa Direct), merchant intelligence, account
  validation, transaction controls, foreign exchange, digital wallets, tokenization, and more.
estate_rating:
  agent_avg: 11.7
  agent_band: emerging
  agent_native: 0
  agent_raw: 12.7
  agent_ready: 1
  band: emerging
  best: 59.4
  composite_avg: 22.2
  composite_band: emerging
  composite_raw: 21.7
  developing: 0
  exemplar: 0
  rating: 18.0
  scored: 3
  spread: 59.3
  strength: 2
  strong: 1
  worst: 0.1
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
    immediate_parent: visa
    name: Currencycloud
    relationship: product
    score_band: strong
    score_composite: 59.4
    slug: currencycloud
    source: prose
  label: Strong
  open: true
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: visa
    name: Featurespace
    relationship: product
    score_band: minimal
    score_composite: 5.7
    slug: featurespace
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: visa
    name: Payworks
    relationship: product
    score_band: minimal
    score_composite: 0.1
    slug: payworks
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
name: Visa
overview: 'Visa publishes its API surface across 3 provider profiles indexed on the APIs.io network, of
  which 3 carry a rating. The rated members span 59.3 points, from 59.4 down to 0.1.


  Its highest-rated surfaces are Currencycloud, Featurespace, Payworks.'
parent_provider: visa
permalink: /estates/visa/
slug: visa
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/visa/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
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
- Tokenization
title: Visa
---
