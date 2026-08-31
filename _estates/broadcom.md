---
api_total: 117
category: Estates
description: Broadcom is a global technology company that specializes in the design and manufacturing
  of semiconductors and other hardware components for a wide range of industries. They provide a diverse
  portfolio of products for the enterprise, data center, networking, telecommunications, and consumer
  electronics markets. Broadcom's technology is used in a variety of devices such as smartphones, tablets,
  routers, and smart TVs.
estate_rating:
  agent_avg: 6.6
  agent_band: minimal
  agent_native: 0
  agent_raw: 5.9
  agent_ready: 0
  band: emerging
  best: 56.2
  composite_avg: 17.8
  composite_band: emerging
  composite_raw: 17.1
  developing: 3
  exemplar: 0
  rating: 13.3
  scored: 24
  spread: 55.6
  strength: 5
  strong: 1
  worst: 0.6
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/broadcom.png
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: 2023
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 59
    immediate_parent: broadcom
    name: VMware
    relationship: acquisition
    score_band: strong
    score_composite: 56.2
    slug: vmware
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 3
  items:
  - &id002
    acquired: 2017
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 12
    immediate_parent: broadcom
    name: Brocade
    relationship: acquisition
    score_band: developing
    score_composite: 46.4
    slug: brocade
  - &id003
    acquired: 2019
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 8
    immediate_parent: broadcom
    name: Symantec
    relationship: acquisition
    score_band: developing
    score_composite: 42.0
    slug: symantec
  - &id004
    acquired: 2018
    agent_band: agent-aware
    agent_score: 22.7
    api_count: 8
    immediate_parent: vmware
    name: CloudHealth
    relationship: acquisition
    score_band: developing
    score_composite: 40.1
    slug: cloudhealth
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 5
    immediate_parent: vmware
    name: VMware Tanzu
    relationship: product
    score_band: thin
    score_composite: 37.6
    slug: vmware-tanzu
  - &id006
    acquired: 2013
    agent_band: agent-aware
    agent_score: 19.6
    api_count: 15
    immediate_parent: ca
    name: Flowdock (Discontinued)
    relationship: acquisition
    score_band: thin
    score_composite: 30.5
    slug: flowdock
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 5
  items:
  - &id007
    acquired: 2020
    agent_band: agent-aware
    agent_score: 5.4
    api_count: 1
    immediate_parent: vmware
    name: Lastline
    relationship: acquisition
    score_band: emerging
    score_composite: 23.5
    slug: lastline
  - &id008
    acquired: 2018
    agent_band: human-only
    agent_score: 2.5
    api_count: 6
    immediate_parent: broadcom
    name: CA Technologies (Broadcom)
    relationship: acquisition
    score_band: emerging
    score_composite: 21.3
    slug: ca
  - &id009
    acquired: 2019
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: vmware
    name: Carbon Black
    relationship: acquisition
    score_band: emerging
    score_composite: 19.3
    slug: carbon-black
  - &id010
    acquired: 2016
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: symantec
    name: Bluecoat (Symantec)
    relationship: acquisition
    score_band: emerging
    score_composite: 14.5
    slug: bluecoat-symantec
  - &id011
    acquired: 2021
    agent_band: human-only
    agent_score: 2.5
    api_count: 2
    immediate_parent: broadcom
    name: AppNeta
    relationship: acquisition
    score_band: emerging
    score_composite: 12.5
    slug: appneta
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 13
  items:
  - &id012
    acquired: 2019
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: AVI Networks
    relationship: acquisition
    score_band: minimal
    score_composite: 8.7
    slug: avi-networks
  - &id013
    acquired: 2012
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: appneta
    name: Tracelytics
    relationship: acquisition
    score_band: minimal
    score_composite: 7.5
    slug: tracelytics
  - &id014
    acquired: 2009
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: SpringSource
    relationship: acquisition
    score_band: minimal
    score_composite: 6.9
    slug: springsource
  - &id015
    acquired: 2018
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Heptio
    relationship: acquisition
    score_band: minimal
    score_composite: 5.3
    slug: heptio
  - &id016
    acquired: 2017
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Apteligent
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: apteligent
  - &id017
    acquired: 2004
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: symantec
    name: Brightmail
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: brightmail
  - &id018
    acquired: 2016
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: carbon-black
    name: Confer Technologies
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: confer
  - &id019
    acquired: 2020
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Datrium
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: datrium
  - &id020
    acquired: 2017
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: symantec
    name: Fireglass
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: fireglass
  - &id021
    acquired: 2012
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Nicira Networks
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: nicira-networks
  - &id022
    acquired: 2020
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: vmware
    name: Octarine
    relationship: acquisition
    score_band: minimal
    score_composite: 5.0
    slug: octarine
  - &id023
    acquired: 2010
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: ca
    name: Arcot Systems
    relationship: acquisition
    score_band: minimal
    score_composite: 1.5
    slug: arcot-systems
  - &id024
    acquired: 2000
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: broadcom
    name: Newport Communications
    relationship: acquisition
    score_band: minimal
    score_composite: 0.6
    slug: newport-communications
  label: Minimal
  open: false
member_on_network: 24
member_total: 24
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
members_unrated: []
name: Broadcom
overview: 'Broadcom publishes its API surface across 24 provider profiles indexed on the APIs.io network,
  of which 24 carry a rating. The rated members span 55.6 points, from 56.2 down to 0.6.


  Its highest-rated surfaces are VMware, Brocade, Symantec, CloudHealth, VMware Tanzu.'
parent_provider: broadcom
permalink: /estates/broadcom/
slug: broadcom
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/apis.yml
subfamilies:
- member_count: 11
  members:
  - name: CloudHealth
    score_band: developing
    score_composite: 40.1
    slug: cloudhealth
  - name: VMware Tanzu
    score_band: thin
    score_composite: 37.6
    slug: vmware-tanzu
  - name: Lastline
    score_band: emerging
    score_composite: 23.5
    slug: lastline
  - name: Carbon Black
    score_band: emerging
    score_composite: 19.3
    slug: carbon-black
  - name: AVI Networks
    score_band: minimal
    score_composite: 8.7
    slug: avi-networks
  - name: SpringSource
    score_band: minimal
    score_composite: 6.9
    slug: springsource
  - name: Heptio
    score_band: minimal
    score_composite: 5.3
    slug: heptio
  - name: Apteligent
    score_band: minimal
    score_composite: 5.0
    slug: apteligent
  - name: Datrium
    score_band: minimal
    score_composite: 5.0
    slug: datrium
  - name: Nicira Networks
    score_band: minimal
    score_composite: 5.0
    slug: nicira-networks
  - name: Octarine
    score_band: minimal
    score_composite: 5.0
    slug: octarine
  name: VMware
  on_network: true
  slug: vmware
- member_count: 3
  members:
  - name: Bluecoat (Symantec)
    score_band: emerging
    score_composite: 14.5
    slug: bluecoat-symantec
  - name: Brightmail
    score_band: minimal
    score_composite: 5.0
    slug: brightmail
  - name: Fireglass
    score_band: minimal
    score_composite: 5.0
    slug: fireglass
  name: Symantec
  on_network: true
  slug: symantec
- member_count: 2
  members:
  - name: Flowdock (Discontinued)
    score_band: thin
    score_composite: 30.5
    slug: flowdock
  - name: Arcot Systems
    score_band: minimal
    score_composite: 1.5
    slug: arcot-systems
  name: CA Technologies (Broadcom)
  on_network: true
  slug: ca
- member_count: 1
  members:
  - name: Tracelytics
    score_band: minimal
    score_composite: 7.5
    slug: tracelytics
  name: AppNeta
  on_network: true
  slug: appneta
- member_count: 1
  members:
  - name: Confer Technologies
    score_band: minimal
    score_composite: 5.0
    slug: confer
  name: Carbon Black
  on_network: true
  slug: carbon-black
tags:
- Cloud Infrastructure
- Gateways
- Management
- Networks
- Observability
- Virtualization
- Fortune 500
title: Broadcom
---
