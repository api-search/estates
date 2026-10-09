---
api_total: 62
category: Estates
description: Salesforce is a cloud-based customer relationship management (CRM) platform that provides
  a comprehensive suite of enterprise applications for sales, service, marketing, commerce, analytics
  and AI. Its Lightning Platform exposes REST, SOAP, Bulk 2.0, Streaming, GraphQL, Metadata, Tooling and
  gRPC Pub/Sub APIs, alongside the Agentforce agent and models APIs, letting developers query, write and
  subscribe to org data programmatically.
estate_rating:
  agent_avg: 12.6
  agent_band: emerging
  agent_native: 0
  agent_raw: 12.9
  agent_ready: 6
  band: emerging
  best: 71.9
  composite_avg: 23.7
  composite_band: emerging
  composite_raw: 24.3
  developing: 5
  exemplar: 2
  rating: 19.3
  scored: 30
  spread: 71.9
  strength: 17
  strong: 3
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg
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
    agent_score: 45.0
    api_count: 1
    api_count_basis: published
    immediate_parent: salesforce
    name: Salesforce Service Cloud APIs
    relationship: product
    score_band: exemplar
    score_composite: 71.9
    slug: service-cloud
    source: declared
  - &id002
    acquired: 2021
    agent_band: agent-ready
    agent_score: 34.0
    api_count: 32
    api_count_basis: published
    immediate_parent: salesforce
    name: Slack
    relationship: acquisition
    score_band: exemplar
    score_composite: 68.4
    slug: slack
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 3
  items:
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 34.0
    api_count: 1
    api_count_basis: published
    immediate_parent: salesforce
    name: Salesforce Marketing Cloud Account Engagement (Pardot)
    relationship: acquisition
    score_band: strong
    score_composite: 59.1
    slug: pardot
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 27.3
    api_count: 8
    api_count_basis: published
    immediate_parent: salesforce
    name: Salesforce Sales Cloud
    relationship: product
    score_band: strong
    score_composite: 58.1
    slug: salesforce-sales-cloud
    source: declared
  - &id005
    acquired: 2018
    agent_band: agent-ready
    agent_score: 44.2
    api_count: 1
    api_count_basis: published
    immediate_parent: salesforce
    name: MuleSoft
    relationship: acquisition
    score_band: strong
    score_composite: 54.8
    slug: mulesoft
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 5
  items:
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 27.3
    api_count: 9
    api_count_basis: published
    immediate_parent: salesforce
    name: Salesforce Experience Cloud
    relationship: product
    score_band: developing
    score_composite: 52.9
    slug: salesforce-experience-cloud
    source: declared
  - &id007
    acquired: 2019
    agent_band: agent-ready
    agent_score: 47.1
    api_count: 1
    api_count_basis: published
    immediate_parent: salesforce
    name: Tableau
    relationship: acquisition
    score_band: developing
    score_composite: 51.4
    slug: tableau
    source: declared
  - &id008
    acquired: 2025
    agent_band: agent-ready
    agent_score: 54.4
    api_count: 1
    api_count_basis: published
    immediate_parent: salesforce
    name: Informatica
    relationship: acquisition
    score_band: developing
    score_composite: 50.2
    slug: informatica
    source: declared
  - &id009
    acquired: 2016
    agent_band: agent-aware
    agent_score: 9.6
    api_count: 2
    api_count_basis: split
    immediate_parent: salesforce
    name: Demandware
    relationship: acquisition
    score_band: developing
    score_composite: 45.8
    slug: demandware
    source: declared
  - &id010
    acquired: 2010
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    api_count_basis: published
    immediate_parent: salesforce
    name: Heroku
    relationship: acquisition
    score_band: developing
    score_composite: 43.4
    slug: heroku
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id011
    acquired: null
    agent_band: agent-aware
    agent_score: 10.1
    api_count: 1
    api_count_basis: split
    immediate_parent: salesforce
    name: Lightning Web Components
    relationship: product
    score_band: thin
    score_composite: 38.8
    slug: lightning-web-components
    source: declared
  - &id012
    acquired: null
    agent_band: agent-aware
    agent_score: 20.5
    api_count: 1
    api_count_basis: published
    immediate_parent: salesforce
    name: Salesforce Commerce Cloud
    relationship: product
    score_band: thin
    score_composite: 32.0
    slug: salesforce-commerce-cloud
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 3
  items:
  - &id013
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Own (OwnBackup)
    relationship: acquisition
    score_band: emerging
    score_composite: 16.7
    slug: own-ownbackup
    source: declared
  - &id014
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Regrello
    relationship: acquisition
    score_band: emerging
    score_composite: 15.6
    slug: regrello
    source: declared
  - &id015
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Zoomin
    relationship: acquisition
    score_band: emerging
    score_composite: 11.6
    slug: zoomin
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 15
  items:
  - &id016
    acquired: 2026
    agent_band: human-only
    agent_score: 3.5
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Cimulate
    relationship: acquisition
    score_band: minimal
    score_composite: 10.0
    slug: cimulate
    source: declared
  - &id017
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Moonhub
    relationship: acquihire
    score_band: minimal
    score_composite: 9.4
    slug: moonhub
    source: prose
  - &id018
    acquired: 2025
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: convergence
    relationship: acquisition
    score_band: minimal
    score_composite: 7.0
    slug: convergence
    source: declared
  - &id019
    acquired: 2013
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: demandware
    name: CQuotient
    relationship: acquisition
    score_band: minimal
    score_composite: 5.8
    slug: cquotient
    source: declared
  - &id020
    acquired: 2023
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: AirKit
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: airkit
    source: declared
  - &id021
    acquired: 2012
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Buddy Media
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: buddy-media
    source: declared
  - &id022
    acquired: 2013
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Exact Target
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: exact-target
    source: declared
  - &id023
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: informatica
    name: Privitar
    relationship: product
    score_band: minimal
    score_composite: 3.4
    slug: privitar
    source: parent-company-property
  - &id024
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Spiff
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: spiff
    source: declared
  - &id025
    acquired: 2015
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Steelbrick
    relationship: acquisition
    score_band: minimal
    score_composite: 3.4
    slug: steelbrick
    source: declared
  - &id026
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Spindle Technologies
    relationship: acquisition
    score_band: minimal
    score_composite: 3.3
    slug: spindle-technologies
    source: declared
  - &id027
    acquired: null
    agent_band: agent-aware
    agent_score: 8.6
    api_count: 0
    api_count_basis: split
    immediate_parent: slack
    name: Screenhero
    relationship: acquisition
    score_band: minimal
    score_composite: 2.8
    slug: screenhero
    source: prose
  - &id028
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 1
    api_count_basis: split
    immediate_parent: salesforce
    name: Clockwise
    relationship: acquihire
    score_band: minimal
    score_composite: 0.0
    slug: clockwise
    source: declared
  - &id029
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: informatica
    name: Itemfield
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: itemfield
    source: parent-company-property
  - &id030
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 2
    api_count_basis: split
    immediate_parent: salesforce
    name: PredictionIO
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: predictionio
    source: parent-company-property
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id031
    acquired: 2020
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: salesforce
    name: Vlocity
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: vlocity
    source: declared
  label: Unrated
  open: false
member_on_network: 31
member_total: 31
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
- *id009
- *id010
- *id011
- *id012
- *id013
- *id014
- *id015
- *id016
- *id017
- *id018
- *id019
- *id020
- *id021
- *id022
- *id023
- *id024
- *id025
- *id026
- *id027
- *id028
- *id029
- *id030
- *id031
members_unrated: []
name: Salesforce
overview: 'Salesforce publishes its API surface across 31 provider profiles indexed on the APIs.io network,
  of which 31 carry a rating. The rated members span 71.9 points, from 71.9 down to 0.0.


  Its highest-rated surfaces are Salesforce Service Cloud APIs, Slack, Salesforce Marketing Cloud Account
  Engagement (Pardot), Salesforce Sales Cloud, MuleSoft.'
parent_provider: salesforce
permalink: /estates/salesforce/
slug: salesforce
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 2
  members:
  - name: Privitar
    score_band: minimal
    score_composite: 3.4
    slug: privitar
  - name: Itemfield
    score_band: minimal
    score_composite: 0.0
    slug: itemfield
  name: Informatica
  on_network: true
  permalink: /estates/informatica/
  slug: informatica
- has_page: false
  member_count: 1
  members:
  - name: CQuotient
    score_band: minimal
    score_composite: 5.8
    slug: cquotient
  name: Demandware
  on_network: true
  permalink: /estates/demandware/
  slug: demandware
- has_page: false
  member_count: 1
  members:
  - name: Screenhero
    score_band: minimal
    score_composite: 2.8
    slug: screenhero
  name: Slack
  on_network: true
  permalink: /estates/slack/
  slug: slack
subfamily_page_count: 0
tags:
- Fortune 500
- Artificial Intelligence
- Analytics
- Cloud
- Commerce
- CRM
- Customer Service
- Enterprise
- Marketing
- Platform
- Sales
- Salesforce
title: Salesforce
---
