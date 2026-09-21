---
api_total: 7
category: Estates
description: Westpac Banking Corporation is Australia's oldest bank and company, founded in 1817 as the
  Bank of New South Wales, and is one of the country's "Big Four" banks. Headquartered in Sydney, it is
  a publicly listed company on the Australian Securities Exchange (ASX:WBC), not a customer-owned mutual,
  and operates a multi-brand group that includes St.George, BankSA, Bank of Melbourne, and RAMS. As an
  authorised deposit-taking institution (ADI) regulated by APRA, Westpac is a designated data holder under
  Australia's Consumer Data Right (CDR / Open Banking) regime and exposes a public, unauthenticated Product
  Reference Data (PRD) API conforming to the DSB Consumer Data Standards. Consumer and account data sharing
  beyond product reference data is available only to accredited data recipients through the CDR's authenticated,
  consent-driven channels.
estate_rating:
  agent_avg: 15.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 22.9
  agent_ready: 0
  band: emerging
  best: 55.1
  composite_avg: 30.6
  composite_band: thin
  composite_raw: 43.7
  developing: 1
  exemplar: 0
  rating: 24.7
  scored: 3
  spread: 25.2
  strength: 3
  strong: 1
  worst: 29.9
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/westpac.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 23.9
    api_count: 1
    immediate_parent: westpac
    name: St.George Bank
    relationship: product
    score_band: strong
    score_composite: 55.1
    slug: st-george-bank
    source: prose
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 23.9
    api_count: 1
    immediate_parent: westpac
    name: BankSA
    relationship: product
    score_band: developing
    score_composite: 46.1
    slug: banksa
    source: prose
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 21.0
    api_count: 5
    immediate_parent: westpac
    name: Bank of Melbourne
    relationship: product
    score_band: thin
    score_composite: 29.9
    slug: bank-of-melbourne
    source: prose
  label: Thin
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Westpac Banking Corporation
overview: 'Westpac Banking Corporation publishes its API surface across 3 provider profiles indexed on
  the APIs.io network, of which 3 carry a rating. The rated members span 25.2 points, from 55.1 down to
  29.9.


  Its highest-rated surfaces are St.George Bank, BankSA, Bank of Melbourne.'
parent_provider: westpac
permalink: /estates/westpac/
slug: westpac
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/westpac/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Financial
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Product Reference Data
- ADI
title: Westpac Banking Corporation
---
