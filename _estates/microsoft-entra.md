---
api_total: 14
category: Estates
description: Microsoft Entra (formerly Azure Active Directory) provides identity and access management
  services including authentication, authorization, and directory services.
estate_rating:
  agent_avg: 21.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 34.1
  agent_ready: 2
  band: thin
  best: 77.9
  composite_avg: 36.7
  composite_band: thin
  composite_raw: 55.0
  developing: 1
  exemplar: 1
  rating: 30.5
  scored: 4
  spread: 46.0
  strength: 6
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
    agent_score: 52.0
    api_count: 9
    immediate_parent: microsoft-entra
    name: Microsoft Entra ID (formerly Azure AD)
    relationship: product
    score_band: exemplar
    score_composite: 77.9
    slug: azure-ad
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 32.4
    api_count: 1
    immediate_parent: microsoft-entra
    name: Microsoft Azure Active Directory
    relationship: product
    score_band: strong
    score_composite: 56.6
    slug: microsoft-azure-active-directory
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 27.3
    api_count: 3
    immediate_parent: microsoft-entra
    name: Microsoft Active Directory
    relationship: product
    score_band: developing
    score_composite: 53.6
    slug: active-directory
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id004
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
name: Microsoft Entra
overview: 'Microsoft Entra publishes its API surface across 4 provider profiles indexed on the APIs.io
  network, of which 4 carry a rating. The rated members span 46.0 points, from 77.9 down to 31.9.


  Its highest-rated surfaces are Microsoft Entra ID (formerly Azure AD), Microsoft Azure Active Directory,
  Microsoft Active Directory, Microsoft Intune.'
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
title: Microsoft Entra
---
