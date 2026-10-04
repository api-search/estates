---
api_total: 2
category: Estates
description: 'Pearson plc is the world''s largest learning company, operating courseware and assessment
  platforms (MyLab, Mastering, Revel, Pearson+, Learning Catalytics), UK and international qualifications
  (Edexcel, BTEC), clinical and school assessment businesses, Pearson Virtual Schools, English language
  learning, and Pearson VUE, the computer-based certification and licensure testing network. Pearson once
  ran a substantial public API program — the Pearson Developers Network, with RESTful LearningStudio Course
  APIs, SOAP SIS APIs, an eventing surface and first-party client libraries in five languages. That program
  is retired and closed: LearningStudio ended in 2018, eCollege shut down in 2023, api.pearson.com answers
  "service that has been moved", and developer.pearson.com returns 401 behind a Salesforce community.
  What remains public is an OIDC discovery document, a live status page, a security disclosure policy,
  LTI 1.3 guidance, and three retired SIS WSDLs.'
estate_rating:
  agent_avg: 9.9
  agent_band: minimal
  agent_native: 0
  agent_raw: 8.8
  agent_ready: 0
  band: emerging
  best: 34.5
  composite_avg: 19.7
  composite_band: emerging
  composite_raw: 18.4
  developing: 0
  exemplar: 0
  rating: 15.8
  scored: 3
  spread: 31.6
  strength: 0
  strong: 0
  worst: 2.9
estate_root: null
estate_root_name: null
image: https://www.pearson.com/media_11f626a45563a855db4c129c4851356069ff52ec8.png?width=1200&format=pjpg&optimize=medium
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 22.7
    api_count: 1
    immediate_parent: pearson
    name: Credly
    relationship: acquisition
    score_band: thin
    score_composite: 34.5
    slug: credly
    source: prose
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 3.8
    api_count: 1
    immediate_parent: pearson
    name: Scott Foresman
    relationship: product
    score_band: emerging
    score_composite: 17.9
    slug: scott-foresman
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
    immediate_parent: pearson
    name: Clutch Learning
    relationship: acquisition
    score_band: minimal
    score_composite: 2.9
    slug: clutch-learning
    source: declared
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Pearson
overview: 'Pearson publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 31.6 points, from 34.5 down to 2.9.


  Its highest-rated surfaces are Credly, Scott Foresman, Clutch Learning.'
parent_provider: pearson
permalink: /estates/pearson/
slug: pearson
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/pearson/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Education
- Learning
- Assessment
- Certification
- Publishing
- EdTech
- Qualifications
- Testing
- Learning Management
- Workforce Skills
title: Pearson
---
