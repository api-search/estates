---
api_total: 2
category: Estates
description: 'Centene Corporation is a Fortune 500 managed care organization delivering government-sponsored
  healthcare to roughly one in fifteen Americans through Medicaid, Medicare Advantage, TRICARE and Health
  Insurance Marketplace plans, operating under brands including Ambetter Health, Wellcare, Superior HealthPlan
  and Fidelis Care. Its public API surface exists to satisfy the 21st Century Cures Act and the CMS Interoperability
  and Patient Access Rule: HL7 FHIR R4 APIs for member record access (US Core 6.1.0, CARIN Blue Button
  2.0.0, Da Vinci US Drug Formulary 2.0.1) and for provider directory (Da Vinci PDEX Plan Net 1.2.0),
  plus payer-to-payer PDEX exchange. Centene publishes twenty APIs through a partner portal at partners.centene.com,
  whose catalogue and OpenAPI documents are served anonymously; the FHIR Provider Directory is callable
  in production with no credential at all. Member data uses SMART on FHIR 2.0.0 standalone launch against
  a Ping Identity authorization server branded EntryKey ID; partner surfaces use OAuth client credentials
  with a per-API audience. Beyond the mandated interoperability estate Centene also publishes X12 / CAQH
  CORE EDI transaction, provider-search, product-mapping and care-management APIs.'
estate_rating:
  agent_avg: 8.3
  agent_band: minimal
  agent_native: 0
  agent_raw: 6.0
  agent_ready: 1
  band: emerging
  best: 36.2
  composite_avg: 15.4
  composite_band: emerging
  composite_raw: 10.5
  developing: 0
  exemplar: 0
  rating: 12.6
  scored: 5
  spread: 33.1
  strength: 0
  strong: 0
  worst: 3.1
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/centene.png
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 30.2
    api_count: 2
    api_count_basis: published
    immediate_parent: centene
    name: WellCare Health Plans
    relationship: product
    score_band: thin
    score_composite: 36.2
    slug: wellcare-health-plans
    source: parent-company-property
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 4
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: wellcare-health-plans
    name: Universal American
    relationship: product
    score_band: minimal
    score_composite: 5.7
    slug: universal-american
    source: parent-company-property
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: centene
    name: Magellan Health
    relationship: acquisition
    score_band: minimal
    score_composite: 4.0
    slug: magellan-health
    source: prose
  - &id004
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: centene
    name: Apixio (Centene)
    relationship: product
    score_band: minimal
    score_composite: 3.6
    slug: apixio-centene
    source: parent-company-property
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: centene
    name: Health Net
    relationship: subsidiary
    score_band: minimal
    score_composite: 3.1
    slug: health-net
    source: prose
  label: Minimal
  open: false
member_on_network: 5
member_total: 5
members:
- *id001
- *id002
- *id003
- *id004
- *id005
members_unrated: []
name: Centene
overview: 'Centene publishes its API surface across 5 provider profiles indexed on the APIs.io network,
  of which 5 carry a rating. The rated members span 33.1 points, from 36.2 down to 3.1.


  Its highest-rated surfaces are WellCare Health Plans, Universal American, Magellan Health, Apixio (Centene),
  Health Net.'
parent_provider: centene
permalink: /estates/centene/
slug: centene
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/centene/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: Universal American
    score_band: minimal
    score_composite: 5.7
    slug: universal-american
  name: WellCare Health Plans
  on_network: true
  permalink: /estates/wellcare-health-plans/
  slug: wellcare-health-plans
subfamily_page_count: 0
tags:
- Healthcare
- Insurance
- Managed Care
- FHIR
- HL7
- CMS Interoperability
- Patient Access
- Provider Directory
- Payers
- Medicaid
- Medicare
- Interoperability
title: Centene
---
