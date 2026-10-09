---
api_total: 147
category: Estates
description: Instructure is an EdTech company best known for Canvas LMS, a widely adopted learning management
  system used by thousands of educational institutions and organizations worldwide. The platform provides
  a comprehensive REST API and GraphQL API enabling developers to programmatically access and manage courses,
  enrollments, assignments, grades, discussions, and institutional data. Instructure also offers the Data
  Access Platform (DAP) for bulk data queries, New Quizzes API, Canvas Studio API, and support for LTI
  1.3 integrations. Authentication is handled via OAuth2 with per-token dynamic rate limiting, and all
  API responses are returned in JSON over HTTPS.
estate_rating:
  agent_avg: 13.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 18.1
  agent_ready: 2
  band: emerging
  best: 68.7
  composite_avg: 30.8
  composite_band: thin
  composite_raw: 43.8
  developing: 0
  exemplar: 2
  rating: 24.0
  scored: 4
  spread: 61.6
  strength: 6
  strong: 0
  worst: 7.1
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/instructure.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 39.7
    api_count: 146
    api_count_basis: published
    immediate_parent: instructure
    name: Canvas
    relationship: product
    score_band: exemplar
    score_composite: 68.7
    slug: canvas
    source: declared
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 32.8
    api_count: 1
    api_count_basis: published
    immediate_parent: instructure
    name: Canvas LMS
    relationship: product
    score_band: exemplar
    score_composite: 67.5
    slug: canvas-lms
    source: declared
  label: Exemplar
  open: true
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: instructure
    name: LearnPlatform
    relationship: acquisition
    score_band: thin
    score_composite: 31.8
    slug: learnplatform
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: instructure
    name: MasteryConnect
    relationship: product
    score_band: minimal
    score_composite: 7.1
    slug: masteryconnect
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 4
member_total: 4
members:
- *id001
- *id002
- *id003
- *id004
members_unrated: []
name: Instructure
overview: 'Instructure publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 61.6 points, from 68.7 down to 7.1.


  Its highest-rated surfaces are Canvas, Canvas LMS, LearnPlatform, MasteryConnect.'
parent_provider: instructure
permalink: /estates/instructure/
slug: instructure
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/instructure/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Enrollment
- Instructure
- EdTech
- Education
- LMS
- Canvas
- Courses
- Assignments
- Grades
- Discussions
- GraphQL
- LTI
title: Instructure
---
