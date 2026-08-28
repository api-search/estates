---
api_total: 438
category: Estates
description: Collection of Oracle's APIs and developer resources across cloud infrastructure, databases,
  AI services, SaaS applications, and platform services.
estate_rating:
  agent_avg: 15.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 16.3
  agent_ready: 4
  band: thin
  best: 67.1
  composite_avg: 31.6
  composite_band: thin
  composite_raw: 33.6
  developing: 10
  exemplar: 1
  rating: 25.1
  scored: 27
  spread: 62.1
  strength: 21
  strong: 4
  worst: 5.0
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/oracle.png
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 31.3
    api_count: 16
    immediate_parent: oracle
    name: Oracle Siebel
    relationship: product
    score_band: exemplar
    score_composite: 67.1
    slug: oracle-siebel
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 4
  items:
  - &id002
    acquired: 2022
    agent_band: agent-ready
    agent_score: 28.6
    api_count: 13
    immediate_parent: oracle
    name: Oracle Health (Cerner)
    relationship: acquisition
    score_band: strong
    score_composite: 60.7
    slug: cerner
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 29.6
    api_count: 135
    immediate_parent: oracle
    name: Oracle Hospitality
    relationship: product
    score_band: strong
    score_composite: 60.5
    slug: oracle-hospitality
  - &id004
    acquired: 2014
    agent_band: agent-aware
    agent_score: 26.1
    api_count: 3
    immediate_parent: oracle
    name: Responsys
    relationship: acquisition
    score_band: strong
    score_composite: 55.3
    slug: responsys
  - &id005
    acquired: null
    agent_band: agent-ready
    agent_score: 28.6
    api_count: 23
    immediate_parent: oracle
    name: Oracle Eloqua
    relationship: acquisition
    score_band: strong
    score_composite: 55.1
    slug: eloqua
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 10
  items:
  - &id006
    acquired: null
    agent_band: agent-aware
    agent_score: 27.3
    api_count: 48
    immediate_parent: oracle
    name: PeopleSoft
    relationship: acquisition
    score_band: developing
    score_composite: 50.9
    slug: peoplesoft
  - &id007
    acquired: null
    agent_band: agent-aware
    agent_score: 20.9
    api_count: 29
    immediate_parent: oracle
    name: Oracle Database
    relationship: product
    score_band: developing
    score_composite: 50.6
    slug: oracle-database
  - &id008
    acquired: null
    agent_band: agent-aware
    agent_score: 25.5
    api_count: 23
    immediate_parent: oracle
    name: Oracle Essbase
    relationship: product
    score_band: developing
    score_composite: 50.3
    slug: oracle-essbase
  - &id009
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 52
    immediate_parent: oracle
    name: Oracle Fusion Cloud Applications
    relationship: product
    score_band: developing
    score_composite: 47.2
    slug: oracle-fusion
  - &id010
    acquired: null
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 9
    immediate_parent: oracle
    name: Oracle Primavera
    relationship: product
    score_band: developing
    score_composite: 45.7
    slug: oracle-primavera
  - &id011
    acquired: null
    agent_band: agent-aware
    agent_score: 24.4
    api_count: 10
    immediate_parent: oracle
    name: Oracle Retail
    relationship: product
    score_band: developing
    score_composite: 42.9
    slug: oracle-retail
  - &id012
    acquired: null
    agent_band: agent-aware
    agent_score: 22.7
    api_count: 5
    immediate_parent: oracle
    name: Oracle Transportation Management
    relationship: product
    score_band: developing
    score_composite: 42.9
    slug: oracle-transportation-management
  - &id013
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 18
    immediate_parent: oracle
    name: Oracle General Ledger
    relationship: product
    score_band: developing
    score_composite: 42.1
    slug: oracle-general-ledger
  - &id014
    acquired: null
    agent_band: agent-aware
    agent_score: 24.0
    api_count: 26
    immediate_parent: oracle
    name: Oracle WebLogic Server
    relationship: product
    score_band: developing
    score_composite: 41.9
    slug: oracle-weblogic
  - &id015
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 6
    immediate_parent: oracle
    name: Oracle Container Engine for Kubernetes
    relationship: product
    score_band: developing
    score_composite: 40.8
    slug: oracle-container-engine
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 3
  items:
  - &id016
    acquired: null
    agent_band: agent-aware
    agent_score: 18.0
    api_count: 17
    immediate_parent: oracle
    name: Oracle Planning
    relationship: product
    score_band: thin
    score_composite: 36.9
    slug: oracle-planning
  - &id017
    acquired: null
    agent_band: agent-aware
    agent_score: 21.4
    api_count: 3
    immediate_parent: oracle
    name: Oracle Partitioning
    relationship: product
    score_band: thin
    score_composite: 33.2
    slug: oracle-partitioning
  - &id018
    acquired: null
    agent_band: agent-aware
    agent_score: 26.9
    api_count: 2
    immediate_parent: oracle
    name: Oracle Health Data Intelligence
    relationship: product
    score_band: thin
    score_composite: 31.3
    slug: oracle-health-data-intelligence
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 9
  items:
  - &id019
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: oracle
    name: TimesTen
    relationship: acquisition
    score_band: minimal
    score_composite: 10.4
    slug: timesten
  - &id020
    acquired: 2016
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: oracle
    name: Palerra
    relationship: acquisition
    score_band: minimal
    score_composite: 5.3
    slug: palerra
  - &id021
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: oracle
    name: Agile Software
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: agile-software
  - &id022
    acquired: 2010
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: oracle
    name: Amberpoint
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: amberpoint
  - &id023
    acquired: 2017
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: oracle
    name: Conjectag
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: conjectag
  - &id024
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: oracle
    name: DataFox
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: datafox
  - &id025
    acquired: 2014
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: oracle
    name: Datalogix
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: datalogix
  - &id026
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: agile-software
    name: Digital Market
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: digital-market
  - &id027
    acquired: 2014
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: oracle
    name: GreenBytes
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: greenbytes
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
name: Oracle
overview: 'Oracle publishes its API surface across 27 provider profiles indexed on the APIs.io network,
  of which 27 carry a rating. The rated members span 62.1 points, from 67.1 down to 5.0.


  Its highest-rated surfaces are Oracle Siebel, Oracle Health (Cerner), Oracle Hospitality, Responsys,
  Oracle Eloqua.'
parent_provider: oracle
permalink: /estates/oracle/
slug: oracle
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle/refs/heads/main/apis.yml
subfamilies:
- member_count: 1
  members:
  - name: Digital Market
    score_band: minimal
    score_composite: 5.0
    slug: digital-market
  name: Agile Software
  on_network: true
  slug: agile-software
tags:
- Cloud
- Database
- Enterprise
- Infrastructure
- Software-as-a-Service
- Fortune 100
title: Oracle
---
