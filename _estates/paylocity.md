---
api_total: 10
category: Estates
description: Paylocity is a cloud-based human capital management (HCM) and payroll software provider serving
  small and mid-sized US employers with payroll, benefits administration, talent management, time and
  labor tracking, and workforce analytics. The platform powers HR back-office operations along with employee
  self-service tools. The Paylocity API uses OAuth 2.0 client credentials over api.paylocity.com to expose
  employee, payroll, deduction, earning, and onboarding data for partner integrations and customer automations.
estate_rating:
  agent_avg: 10.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 9.0
  agent_ready: 0
  band: emerging
  best: 40.1
  composite_avg: 18.8
  composite_band: emerging
  composite_raw: 17.2
  developing: 1
  exemplar: 0
  rating: 15.3
  scored: 3
  spread: 36.5
  strength: 1
  strong: 0
  worst: 3.6
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
    agent_score: 26.4
    api_count: 1
    api_count_basis: published
    immediate_parent: paylocity
    name: VidGrid
    relationship: product
    score_band: developing
    score_composite: 40.1
    slug: vidgrid
    source: parent-company-property
  label: Developing
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.6
    api_count: 9
    api_count_basis: split
    immediate_parent: paylocity
    name: Airbase
    relationship: acquisition
    score_band: minimal
    score_composite: 7.8
    slug: airbase
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: paylocity
    name: Trace
    relationship: acquisition
    score_band: minimal
    score_composite: 3.6
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
  of which 3 carry a rating. The rated members span 36.5 points, from 40.1 down to 3.6.


  Its highest-rated surfaces are VidGrid, Airbase, Trace.'
parent_provider: paylocity
permalink: /estates/paylocity/
slug: paylocity
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://artifacts.apis.io/paylocity/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Human Resources
- Payroll
- HCM
- Benefits
- Workforce Management
- Time Tracking
- Employee Benefits
title: Paylocity
---
