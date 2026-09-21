---
api_total: 4
category: Estates
description: APILayer is an API marketplace and hub, an Idera, Inc. brand headquartered in Vienna, Austria,
  that publishes and operates a portfolio of self-service REST data APIs alongside a gateway marketplace
  of third-party APIs. The house products cover IP geolocation (IPstack, ipapi), foreign exchange (Fixer,
  Currencylayer, ExchangeRate.host, Exchange Rates API), weather (Weatherstack), market data (Marketstack),
  news (Mediastack), aviation (Aviationstack), scraping and SERP (Scrapestack, Serpstack), and validation
  utilities (Numverify, Mailboxlayer, Vatlayer, Userstack, Countrylayer, Positionstack, Pdflayer, Screenshotlayer).
  One account and one dashboard cover every product, each product is keyed and billed separately, and
  every API has a free plan. APILayer publishes 22 OpenAPI documents from its own SwaggerHub organization,
  an llms.txt, and an OAuth-protected hosted MCP server.
estate_rating:
  agent_avg: 17.4
  agent_band: emerging
  agent_native: 0
  agent_raw: 27.2
  agent_ready: 1
  band: thin
  best: 57.6
  composite_avg: 33.6
  composite_band: thin
  composite_raw: 51.7
  developing: 1
  exemplar: 0
  rating: 27.1
  scored: 3
  spread: 14.8
  strength: 5
  strong: 2
  worst: 42.8
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/apilayer.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 24.4
    api_count: 1
    immediate_parent: apilayer
    name: Currencylayer
    relationship: product
    score_band: strong
    score_composite: 57.6
    slug: currencylayer
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 24.4
    api_count: 1
    immediate_parent: apilayer
    name: Fixer
    relationship: product
    score_band: strong
    score_composite: 54.8
    slug: fixer
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 32.7
    api_count: 2
    immediate_parent: apilayer
    name: IPstack
    relationship: product
    score_band: developing
    score_composite: 42.8
    slug: ipstack
    source: x-parent-company
  label: Developing
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: APILayer
overview: 'APILayer publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 14.8 points, from 57.6 down to 42.8.


  Its highest-rated surfaces are Currencylayer, Fixer, IPstack.'
parent_provider: apilayer
permalink: /estates/apilayer/
slug: apilayer
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apilayer/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- API Marketplace
- API Catalog
- API Discovery
- Developer Tools
- SaaS APIs
- Geolocation
- Currency
- Data API
title: APILayer
---
