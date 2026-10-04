---
api_total: 5
category: Estates
description: Microsoft Dynamics 365 is a cloud-based suite of business applications that unify CRM and
  ERP capabilities to help organizations manage sales, marketing, customer service, finance, operations,
  and commerce.
estate_rating:
  agent_avg: 19.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 33.8
  agent_ready: 2
  band: thin
  best: 70.7
  composite_avg: 34.4
  composite_band: thin
  composite_raw: 57.7
  developing: 0
  exemplar: 1
  rating: 28.4
  scored: 3
  spread: 32.5
  strength: 5
  strong: 1
  worst: 38.2
estate_root: microsoft
estate_root_name: Microsoft
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/microsoft-dynamics-365.png
is_subfamily: true
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 39.2
    api_count: 1
    immediate_parent: microsoft-dynamics-365
    name: Microsoft Dynamics 365 Sales
    relationship: product
    score_band: exemplar
    score_composite: 70.7
    slug: microsoft-dynamics-365-sales
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 37.3
    api_count: 3
    immediate_parent: microsoft-dynamics-365
    name: Microsoft Dynamics NAV
    relationship: product
    score_band: strong
    score_composite: 64.3
    slug: navision
    source: declared
  label: Strong
  open: true
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 1
    immediate_parent: microsoft-dynamics-365
    name: Microsoft Dynamics 365 Business Central
    relationship: product
    score_band: thin
    score_composite: 38.2
    slug: microsoft-dynamics-365-business-central
    source: declared
  label: Thin
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Microsoft Dynamics 365
overview: 'Microsoft Dynamics 365 publishes its API surface across 3 provider profiles indexed on the
  APIs.io network, of which 3 carry a rating. The rated members span 32.5 points, from 70.7 down to 38.2.


  Its highest-rated surfaces are Microsoft Dynamics 365 Sales, Microsoft Dynamics NAV, Microsoft Dynamics
  365 Business Central.'
parent_provider: microsoft-dynamics-365
permalink: /estates/microsoft-dynamics-365/
slug: microsoft-dynamics-365
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics-365/refs/heads/main/apis.yml
subfamilies: []
tags:
- Business Applications
- Cloud
- CRM
- Enterprise
- ERP
- Microsoft
- Microsoft Dynamics 365
title: Microsoft Dynamics 365
---
