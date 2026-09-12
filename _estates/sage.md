---
api_total: 8
category: Estates
description: Sage provides cloud-based ERP, accounting, payroll, and HR software for businesses worldwide.
  The Sage Developer program provides APIs for integrating with Sage products including Sage Accounting
  (Business Cloud), Sage Intacct, Sage 200, Sage X3, and Sage 50. APIs support OAuth 2.0 authentication
  and cover contacts, invoices, payments, ledger accounts, bank accounts, products, and financial reporting.
  Sage Accounting API v3.1 is the current supported REST version with daily limits of 1,296,000 requests
  per app.
estate_rating:
  agent_avg: 12.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 15.5
  agent_ready: 0
  band: emerging
  best: 35.7
  composite_avg: 25.9
  composite_band: thin
  composite_raw: 30.7
  developing: 0
  exemplar: 0
  rating: 20.7
  scored: 4
  spread: 7.6
  strength: 0
  strong: 0
  worst: 28.1
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/sage.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 4
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 3
    immediate_parent: sage
    name: Sage X3
    relationship: product
    score_band: thin
    score_composite: 35.7
    slug: sage-x3
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 1
    immediate_parent: sage
    name: Sage Accounting
    relationship: product
    score_band: thin
    score_composite: 30.9
    slug: sage-accounting
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 2
    immediate_parent: sage-intacct
    name: Sage Intacct Accounting
    relationship: product
    score_band: thin
    score_composite: 28.2
    slug: sage-intacct-accounting
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 2
    immediate_parent: sage
    name: Sage Intacct
    relationship: product
    score_band: thin
    score_composite: 28.1
    slug: sage-intacct
  label: Thin
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Sage
overview: 'Sage publishes its API surface across 4 provider profiles indexed on the APIs.io network, of
  which 4 carry a rating. The rated members span 7.6 points, from 35.7 down to 28.1.


  Its highest-rated surfaces are Sage X3, Sage Accounting, Sage Intacct Accounting, Sage Intacct.'
parent_provider: sage
permalink: /estates/sage/
slug: sage
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Sage Intacct Accounting
    score_band: thin
    score_composite: 28.2
    slug: sage-intacct-accounting
  name: Sage Intacct
  on_network: true
  permalink: /estates/sage-intacct/
  slug: sage-intacct
subfamily_page_count: 0
tags:
- Accounting
- Business Management
- Cloud Software
- ERP
- Payroll
- HR
title: Sage
---
