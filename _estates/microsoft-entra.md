---
api_total: 13
category: Estates
description: Microsoft Entra (formerly Azure Active Directory) provides identity and access management
  services including authentication, authorization, and directory services.
estate_rating:
  agent_avg: 20.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 36.1
  agent_ready: 1
  band: thin
  best: 79.7
  composite_avg: 34.6
  composite_band: thin
  composite_raw: 55.0
  developing: 1
  exemplar: 1
  rating: 29.0
  scored: 3
  spread: 47.8
  strength: 4
  strong: 0
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
- band: developing
  blurb: Usable, with meaningful gaps to close
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
    score_band: developing
    score_composite: 53.4
    slug: active-directory
    source: declared
  label: Developing
  open: false
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
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: microsoft-entra
    name: Microsoft Azure Active Directory
    relationship: product
    score_band: null
    score_composite: null
    slug: microsoft-azure-active-directory
    source: declared
  label: Unrated
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Microsoft Entra
overview: 'Microsoft Entra publishes its API surface across 4 provider profiles indexed on the APIs.io
  network, of which 4 carry a rating. The rated members span 47.8 points, from 79.7 down to 31.9.


  Its highest-rated surfaces are Microsoft Entra ID (formerly Azure AD), Microsoft Active Directory, Microsoft
  Intune, Microsoft Azure Active Directory.'
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
