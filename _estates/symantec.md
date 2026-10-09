---
api_total: 0
category: Estates
description: Symantec (now part of Broadcom) is a leading enterprise cybersecurity company providing endpoint
  security, threat detection, data loss prevention, identity security, and network protection products.
  Symantec offers REST APIs for Endpoint Protection Manager (SEPM), Endpoint Security Cloud (SES), Endpoint
  Detection and Response (EDR), Data Loss Prevention (DLP), and the Integrated Cyber Defense Manager (ICDm)
  platform.
estate_rating:
  agent_avg: 6.6
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 14.0
  composite_avg: 14.5
  composite_band: emerging
  composite_raw: 4.7
  developing: 0
  exemplar: 0
  rating: 11.3
  scored: 3
  spread: 14.0
  strength: 0
  strong: 0
  worst: 0.0
estate_root: broadcom
estate_root_name: Broadcom
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/symantec.png
is_subfamily: true
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: 2016
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: symantec
    name: Bluecoat (Symantec)
    relationship: acquisition
    score_band: emerging
    score_composite: 14.0
    slug: bluecoat-symantec
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: 2004
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: symantec
    name: Brightmail
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: brightmail
    source: declared
  - &id003
    acquired: 2017
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: symantec
    name: Fireglass
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: fireglass
    source: declared
  label: Minimal
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
    api_count_basis: split
    immediate_parent: symantec
    name: Elastica
    relationship: product
    score_band: null
    score_composite: null
    slug: elastica
    source: parent-company-property
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
name: Symantec
overview: 'Symantec publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 14.0 points, from 14.0 down to 0.0.


  Its highest-rated surfaces are Bluecoat (Symantec), Brightmail, Fireglass, Elastica.'
parent_provider: symantec
permalink: /estates/symantec/
slug: symantec
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/apis.yml
subfamilies: []
tags:
- Broadcom
- Cybersecurity
- DLP
- EDR
- Endpoint Protection
- Endpoint Security
- Security
- Symantec
- Fortune 500
title: Symantec
---
