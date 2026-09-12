---
api_total: 4
category: Estates
description: Smarty (formerly SmartyStreets) is an address intelligence company that provides REST APIs
  for US and international address verification, validation, geocoding, and autocomplete at high volume.
  The platform supports over 210 million US addresses including 20 million non-USPS addresses, delivering
  up to 55 metadata points and ZIP9-level geocodes per lookup. Smarty offers both cloud-hosted and on-premises
  deployment options, supporting embedded-key and secret-key authentication patterns. APIs are designed
  for high-throughput workloads, with US address lookups reaching up to 25,000 per second, making Smarty
  suitable for enterprise address validation pipelines and real-time checkout address autocomplete.
estate_rating:
  agent_avg: 6.0
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.0
  agent_ready: 0
  band: emerging
  best: 8.1
  composite_avg: 15.7
  composite_band: emerging
  composite_raw: 7.7
  developing: 0
  exemplar: 0
  rating: 11.8
  scored: 4
  spread: 0.5
  strength: 0
  strong: 0
  worst: 7.6
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/smarty.png
is_subfamily: false
layout: estate
member_bands:
- band: minimal
  blurb: Almost no public developer surface
  count: 4
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: smarty
    name: US Autocomplete
    relationship: product
    score_band: minimal
    score_composite: 8.1
    slug: us-autocomplete
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: smarty
    name: US Extract
    relationship: product
    score_band: minimal
    score_composite: 7.6
    slug: us-extract
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: smarty
    name: US Street Address
    relationship: product
    score_band: minimal
    score_composite: 7.6
    slug: us-street-address
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    immediate_parent: smarty
    name: US ZipCode
    relationship: product
    score_band: minimal
    score_composite: 7.6
    slug: us-zipcode
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
name: Smarty
overview: 'Smarty publishes its API surface across 4 provider profiles indexed on the APIs.io network,
  of which 4 carry a rating. The rated members span 0.5 points, from 8.1 down to 7.6.


  Its highest-rated surfaces are US Autocomplete, US Extract, US Street Address, US ZipCode.'
parent_provider: smarty
permalink: /estates/smarty/
slug: smarty
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/smarty/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Address Verification
- Geocoding
- Address Autocomplete
- ZIP Code
- Address Intelligence
- Location Data
- International Address
- US Address
title: Smarty
---
