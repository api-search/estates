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
  agent_avg: 10.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.4
  agent_ready: 0
  band: emerging
  best: 40.1
  composite_avg: 21.9
  composite_band: emerging
  composite_raw: 23.2
  developing: 1
  exemplar: 0
  rating: 17.3
  scored: 6
  spread: 37.2
  strength: 1
  strong: 0
  worst: 2.9
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/sage.png
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
    agent_score: 26.5
    api_count: 1
    immediate_parent: sage
    name: Sage HR
    relationship: acquisition
    score_band: developing
    score_composite: 40.1
    slug: sage-hr
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 3
    immediate_parent: sage
    name: Sage X3
    relationship: product
    score_band: thin
    score_composite: 34.3
    slug: sage-x3
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 3
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 2
    immediate_parent: sage
    name: Sage Intacct
    relationship: product
    score_band: emerging
    score_composite: 24.9
    slug: sage-intacct
    source: declared
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: sage
    name: Sage Accounting
    relationship: product
    score_band: emerging
    score_composite: 20.6
    slug: sage-accounting
    source: declared
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: sage
    name: Anvyl
    relationship: product
    score_band: emerging
    score_composite: 16.3
    slug: anvyl
    source: parent-company-property
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id006
    acquired: 2012-06
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: sage
    name: Folhamatic
    relationship: product
    score_band: minimal
    score_composite: 2.9
    slug: folhamatic
    source: prose
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
name: Sage
overview: 'Sage publishes its API surface across 6 provider profiles indexed on the APIs.io network, of
  which 6 carry a rating. The rated members span 37.2 points, from 40.1 down to 2.9.


  Its highest-rated surfaces are Sage HR, Sage X3, Sage Intacct, Sage Accounting, Anvyl.'
parent_provider: sage
permalink: /estates/sage/
slug: sage
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Accounting
- Business Management
- Cloud Software
- ERP
- Payroll
- Human Resources
title: Sage
---
