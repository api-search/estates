---
api_total: 10
category: Estates
description: Paylocity is a cloud-based human capital management (HCM) and payroll software provider serving
  small and mid-sized US employers with payroll, benefits administration, talent management, time and
  labor tracking, and workforce analytics. The platform powers HR back-office operations along with employee
  self-service tools. The Paylocity API uses OAuth 2.0 client credentials over api.paylocity.com to expose
  employee, payroll, deduction, earning, and onboarding data for partner integrations and customer automations.
estate_rating:
  agent_avg: 10.6
  agent_band: emerging
  agent_native: 0
  agent_raw: 10.1
  agent_ready: 0
  band: emerging
  best: 40.0
  composite_avg: 21.2
  composite_band: emerging
  composite_raw: 19.7
  developing: 1
  exemplar: 0
  rating: 17.0
  scored: 3
  spread: 34.3
  strength: 1
  strong: 0
  worst: 5.7
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/paylocity.png
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
    agent_score: 27.9
    api_count: 1
    immediate_parent: paylocity
    name: VidGrid
    relationship: product
    score_band: developing
    score_composite: 40.0
    slug: vidgrid
    source: prose
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 9
    immediate_parent: paylocity
    name: Airbase
    relationship: product
    score_band: emerging
    score_composite: 13.4
    slug: airbase
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: paylocity
    name: Trace
    relationship: product
    score_band: minimal
    score_composite: 5.7
    slug: trace
    source: prose
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Paylocity
overview: 'Paylocity publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 34.3 points, from 40.0 down to 5.7.


  Its highest-rated surfaces are VidGrid, Airbase, Trace.'
parent_provider: paylocity
permalink: /estates/paylocity/
slug: paylocity
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/paylocity/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- HR
- Payroll
- HCM
- Benefits
- Workforce Management
- Time Tracking
title: Paylocity
---
