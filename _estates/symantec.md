---
api_total: 0
category: Estates
description: Symantec (now part of Broadcom) is a leading enterprise cybersecurity company providing endpoint
  security, threat detection, data loss prevention, identity security, and network protection products.
  Symantec offers REST APIs for Endpoint Protection Manager (SEPM), Endpoint Security Cloud (SES), Endpoint
  Detection and Response (EDR), Data Loss Prevention (DLP), and the Integrated Cyber Defense Manager (ICDm)
  platform.
estate_rating:
  agent_avg: 6.1
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 14.5
  composite_avg: 16.4
  composite_band: emerging
  composite_raw: 8.2
  developing: 0
  exemplar: 0
  rating: 12.3
  scored: 3
  spread: 9.5
  strength: 0
  strong: 0
  worst: 5.0
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/symantec.png
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
    immediate_parent: symantec
    name: Bluecoat (Symantec)
    relationship: acquisition
    score_band: emerging
    score_composite: 14.5
    slug: bluecoat-symantec
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
    immediate_parent: symantec
    name: Brightmail
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: brightmail
  - &id003
    acquired: 2017
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: symantec
    name: Fireglass
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: fireglass
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Symantec
overview: 'Symantec publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 9.5 points, from 14.5 down to 5.0.


  Its highest-rated surfaces are Bluecoat (Symantec), Brightmail, Fireglass.'
parent_provider: symantec
permalink: /estates/symantec/
slug: symantec
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/apis.yml
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
