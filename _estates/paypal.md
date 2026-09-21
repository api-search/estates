---
api_total: 1
category: Estates
description: PayPal is a global online payment system that lets individuals and businesses send and receive
  money electronically. PayPal exposes a broad surface of REST APIs covering payments, orders, subscriptions,
  invoicing, payouts, disputes, payment tokens, shipping tracking, transaction reporting, partner referrals,
  payment experience, and webhook notifications.
estate_rating:
  agent_avg: 11.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 12.7
  agent_ready: 0
  band: emerging
  best: 32.5
  composite_avg: 25.3
  composite_band: thin
  composite_raw: 31.8
  developing: 0
  exemplar: 0
  rating: 19.9
  scored: 2
  spread: 1.4
  strength: 0
  strong: 0
  worst: 31.1
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/paypal.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 21.0
    api_count: 1
    immediate_parent: paypal
    name: MirrorTab
    relationship: product
    score_band: thin
    score_composite: 32.5
    slug: mirrortab
    source: parent-company-property
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 4.3
    api_count: 0
    immediate_parent: paypal
    name: Venmo
    relationship: product
    score_band: thin
    score_composite: 31.1
    slug: venmo
    source: parent-company-property
  label: Thin
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
    immediate_parent: paypal
    name: card.io
    relationship: product
    score_band: null
    score_composite: null
    slug: cardio
    source: parent-company-property
  label: Unrated
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: PayPal
overview: 'PayPal publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 1.4 points, from 32.5 down to 31.1.


  Its highest-rated surfaces are MirrorTab, Venmo, card.io.'
parent_provider: paypal
permalink: /estates/paypal/
slug: paypal
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/paypal/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- PayPal
- Billing
- Commerce
- Disputes
- Invoices
- Order
- Payments
- Payouts
- Subscription
- Tokens
- Webhook
title: PayPal
---
