---
api_total: 9
category: Estates
description: Collection of APIs offered by Intuit for financial and business management services.
estate_rating:
  agent_avg: 11.7
  agent_band: emerging
  agent_native: 0
  agent_raw: 12.9
  agent_ready: 1
  band: emerging
  best: 79.7
  composite_avg: 25.6
  composite_band: thin
  composite_raw: 30.9
  developing: 0
  exemplar: 1
  rating: 20.0
  scored: 5
  spread: 77.0
  strength: 3
  strong: 0
  worst: 2.7
estate_root: null
estate_root_name: null
image: https://developer.intuit.com/app/developer/common/imgs/IntuitDev_Logo.svg
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 42.6
    api_count: 4
    api_count_basis: published
    immediate_parent: intuit
    name: Mailchimp
    relationship: product
    score_band: exemplar
    score_composite: 79.7
    slug: mailchimp
    source: declared
  label: Exemplar
  open: true
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 19.7
    api_count: 4
    api_count_basis: split
    immediate_parent: intuit
    name: QuickBooks
    relationship: product
    score_band: thin
    score_composite: 34.2
    slug: quickbooks
    source: declared
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    api_count_basis: split
    immediate_parent: mailchimp
    name: Reaction Commerce
    relationship: product
    score_band: thin
    score_composite: 28.4
    slug: reaction-commerce
    source: declared
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 2.2
    api_count: 0
    api_count_basis: split
    immediate_parent: intuit
    name: Credit Karma
    relationship: product
    score_band: minimal
    score_composite: 9.6
    slug: credit-karma
    source: declared
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: intuit
    name: Deserve
    relationship: acquisition
    score_band: minimal
    score_composite: 2.7
    slug: deserve
    source: prose
  label: Minimal
  open: false
member_on_network: 5
member_total: 5
members:
- *id001
- *id002
- *id003
- *id004
- *id005
members_unrated: []
name: Intuit
overview: 'Intuit publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 77.0 points, from 79.7 down to 2.7.


  Its highest-rated surfaces are Mailchimp, QuickBooks, Reaction Commerce, Credit Karma, Deserve.'
parent_provider: intuit
permalink: /estates/intuit/
slug: intuit
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Reaction Commerce
    score_band: thin
    score_composite: 28.4
    slug: reaction-commerce
  name: Mailchimp
  on_network: true
  permalink: /estates/mailchimp/
  slug: mailchimp
subfamily_page_count: 0
tags:
- Accounting
- Custom Fields
- Finance
- Financial Services
- Invoicing
- Payments
- Payroll
- Project Management
- Sales Tax
- Small Business
- Tax
- Tax Preparation
title: Intuit
---
