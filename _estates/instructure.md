---
api_total: 145
category: Estates
description: Instructure is an EdTech company best known for Canvas LMS, a widely adopted learning management
  system used by thousands of educational institutions and organizations worldwide. The platform provides
  a comprehensive REST API and GraphQL API enabling developers to programmatically access and manage courses,
  enrollments, assignments, grades, discussions, and institutional data. Instructure also offers the Data
  Access Platform (DAP) for bulk data queries, New Quizzes API, Canvas Studio API, and support for LTI
  1.3 integrations. Authentication is handled via OAuth2 with per-token dynamic rate limiting, and all
  API responses are returned in JSON over HTTPS.
estate_rating:
  agent_avg: 11.8
  agent_band: emerging
  agent_native: 0
  agent_raw: 13.2
  agent_ready: 1
  band: emerging
  best: 73.7
  composite_avg: 28.2
  composite_band: thin
  composite_raw: 38.3
  developing: 0
  exemplar: 1
  rating: 21.6
  scored: 3
  spread: 67.0
  strength: 3
  strong: 0
  worst: 6.7
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/instructure.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 39.7
    api_count: 145
    immediate_parent: instructure
    name: Canvas
    relationship: product
    score_band: exemplar
    score_composite: 73.7
    slug: canvas
    source: declared
  label: Exemplar
  open: true
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: instructure
    name: LearnPlatform
    relationship: product
    score_band: thin
    score_composite: 34.6
    slug: learnplatform
    source: prose
  label: Thin
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
    immediate_parent: instructure
    name: MasteryConnect
    relationship: product
    score_band: minimal
    score_composite: 6.7
    slug: masteryconnect
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
name: Instructure
overview: 'Instructure publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 67.0 points, from 73.7 down to 6.7.


  Its highest-rated surfaces are Canvas, LearnPlatform, MasteryConnect.'
parent_provider: instructure
permalink: /estates/instructure/
slug: instructure
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/instructure/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- EdTech
- Education
- LMS
- Canvas
- Courses
- Enrollments
- Assignments
- Grades
- Discussions
- GraphQL
- LTI
- Learning Management
title: Instructure
---
