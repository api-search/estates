---
api_total: 6
category: Estates
description: CyberArk is the global leader in identity security, providing a unified Identity Security
  Platform that protects human, machine, and application identities across hybrid and multi-cloud environments.
  Core product lines include Privileged Access Manager (PAM Self-Hosted) and Privilege Cloud for credential
  vaulting and session management; Conjur Secrets Manager (Open Source, Enterprise, and Cloud) for machine-identity
  and DevOps secrets; CyberArk Identity for workforce SSO, MFA, and lifecycle; Endpoint Privilege Manager
  for least-privilege enforcement on Windows / macOS / Linux endpoints; Secure Cloud Access for just-in-time
  cloud entitlements; and Customer Identity for B2B / B2C identity. CyberArk publishes a canonical OpenAPI
  3.1 specification for Conjur Secrets Manager at github.com/cyberark/conjur-openapi-spec, and REST APIs
  for PAM Self-Hosted, Privilege Cloud, and CyberArk Identity are documented on docs.cyberark.com and
  developer.cyberark.com.
estate_rating:
  agent_avg: 16.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 25.2
  agent_ready: 1
  band: emerging
  best: 40.7
  composite_avg: 26.2
  composite_band: thin
  composite_raw: 32.4
  developing: 1
  exemplar: 0
  rating: 22.3
  scored: 3
  spread: 14.6
  strength: 1
  strong: 0
  worst: 26.1
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cyberark.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 33.2
    api_count: 4
    immediate_parent: cyberark
    name: Venafi
    relationship: product
    score_band: developing
    score_composite: 40.7
    slug: venafi
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
    agent_score: 22.7
    api_count: 1
    immediate_parent: cyberark
    name: Conjur
    relationship: product
    score_band: thin
    score_composite: 30.4
    slug: conjur
    source: prose
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: cyberark
    name: CyberArk Identity
    relationship: product
    score_band: emerging
    score_composite: 26.1
    slug: cyberark-identity
    source: declared
  label: Emerging
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: CyberArk
overview: 'CyberArk publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 14.6 points, from 40.7 down to 26.1.


  Its highest-rated surfaces are Venafi, Conjur, CyberArk Identity.'
parent_provider: cyberark
permalink: /estates/cyberark/
slug: cyberark
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Authentication
- Cloud Security
- Conjur
- Credential Vault
- DevOps Secrets
- Endpoint Privilege Management
- Identity Security
- Machine Identity
- MFA
- OpenAPI
- PAM
- Privileged Access
title: CyberArk
---
