---
api_total: 13
category: Estates
description: Microsoft Entra (formerly Azure Active Directory) provides identity and access management
  services including authentication, authorization, and directory services.
estate_rating:
  agent_avg: 20.8
  agent_band: emerging
  agent_native: 0
  agent_raw: 36.1
  agent_ready: 1
  band: thin
  best: 79.7
  composite_avg: 35.6
  composite_band: thin
  composite_raw: 57.1
  developing: 0
  exemplar: 1
  rating: 29.7
  scored: 3
  spread: 47.8
  strength: 5
  strong: 1
  worst: 31.9
estate_root: microsoft
estate_root_name: Microsoft
image: https://www.microsoft.com/en-us/security/content/dam/microsoft/final/security/includes/microsoft-entra-logo.svg
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
    agent_score: 56.3
    api_count: 9
    immediate_parent: microsoft-entra
    name: Microsoft Entra ID (formerly Azure AD)
    relationship: product
    score_band: exemplar
    score_composite: 79.7
    slug: azure-ad
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 27.3
    api_count: 3
    immediate_parent: microsoft-entra
    name: Microsoft Active Directory
    relationship: product
    score_band: strong
    score_composite: 59.8
    slug: active-directory
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
    immediate_parent: microsoft-entra
    name: Microsoft Intune
    relationship: product
    score_band: thin
    score_composite: 31.9
    slug: microsoft-intune
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
name: Microsoft Entra
overview: 'Microsoft Entra publishes its API surface across 3 provider profiles indexed on the APIs.io
  network, of which 3 carry a rating. The rated members span 47.8 points, from 79.7 down to 31.9.


  Its highest-rated surfaces are Microsoft Entra ID (formerly Azure AD), Microsoft Active Directory, Microsoft
  Intune.'
parent_provider: microsoft-entra
permalink: /estates/microsoft-entra/
slug: microsoft-entra
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-entra/refs/heads/main/apis.yml
subfamilies: []
tags:
- Access Management
- Authentication
- Azure AD
- Entra
- Identity
- Identity Governance
- Microsoft
- Network Security
- Security
- Zero Trust
- Identity Federation
title: Microsoft Entra
---
