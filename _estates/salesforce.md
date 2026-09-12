---
api_total: 71
category: Estates
description: Salesforce is a cloud-based customer relationship management (CRM) platform that provides
  a comprehensive suite of enterprise applications for sales, service, marketing, commerce, analytics
  and AI. Its Lightning Platform exposes REST, SOAP, Bulk 2.0, Streaming, GraphQL, Metadata, Tooling and
  gRPC Pub/Sub APIs, alongside the Agentforce agent and models APIs, letting developers query, write and
  subscribe to org data programmatically.
estate_rating:
  agent_avg: 13.0
  agent_band: emerging
  agent_native: 1
  agent_raw: 13.4
  agent_ready: 4
  band: emerging
  best: 68.6
  composite_avg: 28.3
  composite_band: thin
  composite_raw: 29.4
  developing: 7
  exemplar: 1
  rating: 22.2
  scored: 27
  spread: 63.6
  strength: 18
  strong: 4
  worst: 5.0
image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-native
    agent_score: 47.2
    api_count: 1
    immediate_parent: salesforce
    name: Salesforce Service Cloud APIs
    relationship: product
    score_band: exemplar
    score_composite: 68.6
    slug: service-cloud
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 4
  items:
  - &id002
    acquired: 2021
    agent_band: agent-ready
    agent_score: 34.4
    api_count: 32
    immediate_parent: salesforce
    name: Slack
    relationship: acquisition
    score_band: strong
    score_composite: 65.6
    slug: slack
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 27.3
    api_count: 8
    immediate_parent: salesforce
    name: Salesforce Sales Cloud
    relationship: product
    score_band: strong
    score_composite: 55.3
    slug: salesforce-sales-cloud
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 28.6
    api_count: 1
    immediate_parent: salesforce
    name: Salesforce Marketing Cloud Account Engagement (Pardot)
    relationship: acquisition
    score_band: strong
    score_composite: 54.8
    slug: pardot
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 26.1
    api_count: 11
    immediate_parent: salesforce
    name: Salesforce Automation
    relationship: product
    score_band: strong
    score_composite: 54.7
    slug: salesforce-automation
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 7
  items:
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 27.3
    api_count: 9
    immediate_parent: salesforce
    name: Salesforce Experience Cloud
    relationship: product
    score_band: developing
    score_composite: 51.4
    slug: salesforce-experience-cloud
  - &id007
    acquired: 2018
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 1
    immediate_parent: salesforce
    name: MuleSoft
    relationship: acquisition
    score_band: developing
    score_composite: 51.3
    slug: mulesoft
  - &id008
    acquired: 2019
    agent_band: agent-ready
    agent_score: 35.2
    api_count: 1
    immediate_parent: salesforce
    name: Tableau
    relationship: acquisition
    score_band: developing
    score_composite: 50.4
    slug: tableau
  - &id009
    acquired: 2010
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    immediate_parent: salesforce
    name: Heroku
    relationship: acquisition
    score_band: developing
    score_composite: 45.6
    slug: heroku
  - &id010
    acquired: 2025
    agent_band: agent-ready
    agent_score: 30.6
    api_count: 1
    immediate_parent: salesforce
    name: Informatica
    relationship: acquisition
    score_band: developing
    score_composite: 43.7
    slug: informatica
  - &id011
    acquired: 2016
    agent_band: agent-aware
    agent_score: 9.6
    api_count: 2
    immediate_parent: salesforce
    name: Demandware
    relationship: acquisition
    score_band: developing
    score_composite: 41.8
    slug: demandware
  - &id012
    acquired: null
    agent_band: agent-aware
    agent_score: 10.1
    api_count: 1
    immediate_parent: salesforce
    name: Lightning Web Components
    relationship: product
    score_band: developing
    score_composite: 41.8
    slug: lightning-web-components
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id013
    acquired: null
    agent_band: agent-aware
    agent_score: 20.9
    api_count: 1
    immediate_parent: salesforce
    name: Salesforce Commerce Cloud
    relationship: product
    score_band: thin
    score_composite: 34.1
    slug: salesforce-commerce-cloud
  - &id014
    acquired: null
    agent_band: agent-aware
    agent_score: 15.5
    api_count: 1
    immediate_parent: salesforce
    name: Clockwise
    relationship: acquisition
    score_band: thin
    score_composite: 29.5
    slug: clockwise
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 4
  items:
  - &id015
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Own (OwnBackup)
    relationship: acquisition
    score_band: emerging
    score_composite: 16.2
    slug: own-ownbackup
  - &id016
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Regrello
    relationship: acquisition
    score_band: emerging
    score_composite: 14.7
    slug: regrello
  - &id017
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Zoomin
    relationship: acquisition
    score_band: emerging
    score_composite: 12.1
    slug: zoomin
  - &id018
    acquired: 2026
    agent_band: human-only
    agent_score: 3.5
    api_count: 0
    immediate_parent: salesforce
    name: Cimulate
    relationship: acquisition
    score_band: emerging
    score_composite: 11.2
    slug: cimulate
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 9
  items:
  - &id019
    acquired: 2025
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: convergence
    relationship: acquisition
    score_band: minimal
    score_composite: 8.7
    slug: convergence
  - &id020
    acquired: 2013
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: demandware
    name: CQuotient
    relationship: acquisition
    score_band: minimal
    score_composite: 8.3
    slug: cquotient
  - &id021
    acquired: 2023
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: AirKit
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: airkit
  - &id022
    acquired: 2012
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Buddy Media
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: buddy-media
  - &id023
    acquired: 2013
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Exact Target
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: exact-target
  - &id024
    acquired: 2024
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Spiff
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: spiff
  - &id025
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Spindle Technologies
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: spindle-technologies
  - &id026
    acquired: 2015
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Steelbrick
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: steelbrick
  - &id027
    acquired: 2020
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: salesforce
    name: Vlocity
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: vlocity
  label: Minimal
  open: false
member_on_network: 27
member_total: 27
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
members_unrated: []
name: Salesforce
overview: 'Salesforce publishes its API surface across 27 provider profiles indexed on the APIs.io network,
  of which 27 carry a rating. The rated members span 63.6 points, from 68.6 down to 5.0.


  Its highest-rated surfaces are Salesforce Service Cloud APIs, Slack, Salesforce Sales Cloud, Salesforce
  Marketing Cloud Account Engagement (Pardot), Salesforce Automation.'
parent_provider: salesforce
permalink: /estates/salesforce/
slug: salesforce
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml
subfamilies:
- member_count: 1
  members:
  - name: CQuotient
    score_band: minimal
    score_composite: 8.3
    slug: cquotient
  name: Demandware
  on_network: true
  slug: demandware
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
title: Salesforce
---
