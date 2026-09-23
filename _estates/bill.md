---
api_total: 0
category: Estates
description: BILL (formerly Bill.com) is a cloud-based financial operations platform for small and midsize
  businesses that automates accounts payable, accounts receivable, and spend & expense management. The
  BILL API Platform exposes these workflows through the BILL v3 REST API and embeddable BILL Elements
  UI components, enabling partners and ERPs to integrate bill capture, approvals, payments, and real-time
  event notifications via webhooks. The API uses session-based authentication with API keys and developer
  keys against production and sandbox gateways.
estate_rating:
  agent_avg: 10.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 8.4
  agent_ready: 0
  band: emerging
  best: 41.1
  composite_avg: 22.2
  composite_band: emerging
  composite_raw: 21.2
  developing: 1
  exemplar: 0
  rating: 17.5
  scored: 3
  spread: 36.1
  strength: 1
  strong: 0
  worst: 5.0
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/bill.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 25.2
    api_count: 0
    immediate_parent: bill
    name: Divvy
    relationship: product
    score_band: developing
    score_composite: 41.1
    slug: divvy
    source: declared
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: bill
    name: Invoice2go
    relationship: product
    score_band: emerging
    score_composite: 17.6
    slug: invoice2go
    source: parent-company-property
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
    immediate_parent: bill
    name: Finmark
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: finmark
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
name: BILL
overview: 'BILL publishes its API surface across 3 provider profiles indexed on the APIs.io network, of
  which 3 carry a rating. The rated members span 36.1 points, from 41.1 down to 5.0.


  Its highest-rated surfaces are Divvy, Invoice2go, Finmark.'
parent_provider: bill
permalink: /estates/bill/
slug: bill
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bill/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Accounts Payable
- Accounts Receivable
- Spend Management
- Expense Management
- Payments
- Bill Pay
- Financial Operations
- Fintech
title: BILL
---
