---
api_total: 3
category: Estates
description: 'Employ, Inc. is the Denver-based parent company of the JazzHR, Lever and Jobvite applicant
  tracking systems, and of the AI Interview, Screening and Sourcing Companions layered across them. Employ
  itself runs no developer program: the recruiting APIs its customers integrate against are published
  under each brand''s own domain and are profiled separately in this network. What Employ publishes on
  employinc.com is a corporate surface that is nonetheless machine-readable — the WordPress REST API behind
  its site, two self-describing Events Calendar REST contracts, and an anonymous Atlassian Statuspage
  API on status.employinc.com — plus the legal, security and responsible-AI documents (Security Exhibit,
  DPAs, SLAs, NYC Local Law 144 bias audit) that govern every brand underneath it.'
estate_rating:
  agent_avg: 12.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 16.4
  agent_ready: 1
  band: emerging
  best: 65.6
  composite_avg: 27.4
  composite_band: thin
  composite_raw: 40.4
  developing: 0
  exemplar: 0
  rating: 21.4
  scored: 2
  spread: 50.3
  strength: 2
  strong: 1
  worst: 15.3
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/employ-inc.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 32.9
    api_count: 2
    immediate_parent: employ-inc
    name: Lever
    relationship: product
    score_band: strong
    score_composite: 65.6
    slug: lever-co
    source: prose
  label: Strong
  open: true
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: employ-inc
    name: Jobvite
    relationship: product
    score_band: emerging
    score_composite: 15.3
    slug: jobvite
    source: prose
  label: Emerging
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: jobvite
    name: RolePoint
    relationship: product
    score_band: null
    score_composite: null
    slug: rolepoint
    source: prose
  label: Unrated
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Employ Inc
overview: 'Employ Inc publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 50.3 points, from 65.6 down to 15.3.


  Its highest-rated surfaces are Lever, Jobvite, RolePoint.'
parent_provider: employ-inc
permalink: /estates/employ-inc/
slug: employ-inc
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/employ-inc/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: RolePoint
    score_band: null
    score_composite: null
    slug: rolepoint
  name: Jobvite
  on_network: true
  permalink: /estates/jobvite/
  slug: jobvite
subfamily_page_count: 0
tags:
- Human Resources
- Recruiting
- Talent Acquisition
- Applicant Tracking
- ATS
- Hiring
- HR Tech
- Content
- Events
- Status
title: Employ Inc
---
