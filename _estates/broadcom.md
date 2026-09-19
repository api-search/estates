---
api_total: 25
category: Estates
description: Broadcom is a global technology company that specializes in the design and manufacturing
  of semiconductors and other hardware components for a wide range of industries. They provide a diverse
  portfolio of products for the enterprise, data center, networking, telecommunications, and consumer
  electronics markets. Broadcom's technology is used in a variety of devices such as smartphones, tablets,
  routers, and smart TVs.
estate_rating:
  agent_avg: 9.8
  agent_band: minimal
  agent_native: 0
  agent_raw: 9.4
  agent_ready: 1
  band: emerging
  best: 57.6
  composite_avg: 21.9
  composite_band: emerging
  composite_raw: 21.8
  developing: 3
  exemplar: 0
  rating: 17.1
  scored: 20
  spread: 57.0
  strength: 7
  strong: 2
  worst: 0.6
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/broadcom.png
is_subfamily: false
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 2
  items:
  - &id001
    acquired: 2018
    agent_band: agent-ready
    agent_score: 38.9
    api_count: 8
    immediate_parent: vmware
    name: CloudHealth
    relationship: acquisition
    score_band: strong
    score_composite: 57.6
    slug: cloudhealth
    source: declared
  - &id002
    acquired: 2023
    agent_band: agent-aware
    agent_score: 24.8
    api_count: 1
    immediate_parent: broadcom
    name: VMware
    relationship: acquisition
    score_band: strong
    score_composite: 54.3
    slug: vmware
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 3
  items:
  - &id003
    acquired: 2017
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: broadcom
    name: Brocade
    relationship: acquisition
    score_band: developing
    score_composite: 45.2
    slug: brocade
    source: declared
  - &id004
    acquired: 2019
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 1
    immediate_parent: broadcom
    name: Symantec
    relationship: acquisition
    score_band: developing
    score_composite: 40.7
    slug: symantec
    source: declared
  - &id005
    acquired: 2021
    agent_band: agent-aware
    agent_score: 28.1
    api_count: 2
    immediate_parent: broadcom
    name: AppNeta
    relationship: acquisition
    score_band: developing
    score_composite: 39.6
    slug: appneta
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id006
    acquired: 2013
    agent_band: agent-aware
    agent_score: 24.6
    api_count: 2
    immediate_parent: ca
    name: Flowdock (Discontinued)
    relationship: acquisition
    score_band: thin
    score_composite: 37.9
    slug: flowdock
    source: declared
  - &id007
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 2
    immediate_parent: vmware
    name: VMware Tanzu
    relationship: product
    score_band: thin
    score_composite: 36.4
    slug: vmware-tanzu
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 4
  items:
  - &id008
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
    source: declared
  - &id009
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
    source: declared
  - &id010
    acquired: 2019
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: vmware
    name: Carbon Black
    relationship: acquisition
    score_band: emerging
    score_composite: 19.8
    slug: carbon-black
    source: declared
  - &id011
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
    source: declared
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 9
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
    source: declared
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
    source: declared
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
    source: declared
  - &id015
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: broadcom
    name: Avago Technologies
    relationship: rename
    score_band: minimal
    score_composite: 5.4
    slug: avago-technologies
    source: declared
  - &id016
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: avago-technologies
    name: LSI
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: lsi
    source: prose
  - &id017
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
    source: declared
  - &id018
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
    source: declared
  - &id019
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
    source: declared
  - &id020
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
    source: declared
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 8
  items:
  - &id021
    acquired: 2017
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: vmware
    name: Apteligent
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: apteligent
    source: declared
  - &id022
    acquired: 2004
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: symantec
    name: Brightmail
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: brightmail
    source: declared
  - &id023
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: ca
    name: Concord Data Systems
    relationship: product
    score_band: null
    score_composite: null
    slug: concord-data-systems
    source: prose
  - &id024
    acquired: 2016
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: carbon-black
    name: Confer Technologies
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: confer
    source: declared
  - &id025
    acquired: 2020
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: vmware
    name: Datrium
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: datrium
    source: declared
  - &id026
    acquired: 2017
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: symantec
    name: Fireglass
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: fireglass
    source: declared
  - &id027
    acquired: 2018
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: vmware
    name: Heptio
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: heptio
    source: declared
  - &id028
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: avago-technologies
    name: LSI Logic
    relationship: product
    score_band: null
    score_composite: null
    slug: lsi-logic
    source: prose
  label: Unrated
  open: false
member_on_network: 28
member_total: 28
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
members_unrated: []
name: Broadcom
overview: 'Broadcom publishes its API surface across 28 provider profiles indexed on the APIs.io network,
  of which 28 carry a rating. The rated members span 57.0 points, from 57.6 down to 0.6.


  Its highest-rated surfaces are CloudHealth, VMware, Brocade, Symantec, AppNeta.'
parent_provider: broadcom
permalink: /estates/broadcom/
slug: broadcom
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/apis.yml
subfamilies:
- has_page: true
  member_count: 12
  members:
  - name: CloudHealth
    score_band: strong
    score_composite: 57.6
    slug: cloudhealth
  - name: VMware Tanzu
    score_band: thin
    score_composite: 36.4
    slug: vmware-tanzu
  - name: Lastline
    score_band: emerging
    score_composite: 23.5
    slug: lastline
  - name: Carbon Black
    score_band: emerging
    score_composite: 19.8
    slug: carbon-black
  - name: AVI Networks
    score_band: minimal
    score_composite: 8.7
    slug: avi-networks
  - name: SpringSource
    score_band: minimal
    score_composite: 6.9
    slug: springsource
  - name: Nicira Networks
    score_band: minimal
    score_composite: 5.0
    slug: nicira-networks
  - name: Octarine
    score_band: minimal
    score_composite: 5.0
    slug: octarine
  - name: Apteligent
    score_band: null
    score_composite: null
    slug: apteligent
  - name: Confer Technologies
    score_band: null
    score_composite: null
    slug: confer
  - name: Datrium
    score_band: null
    score_composite: null
    slug: datrium
  - name: Heptio
    score_band: null
    score_composite: null
    slug: heptio
  name: VMware
  on_network: true
  permalink: /estates/vmware/
  slug: vmware
- has_page: true
  member_count: 3
  members:
  - name: Flowdock (Discontinued)
    score_band: thin
    score_composite: 37.9
    slug: flowdock
  - name: Arcot Systems
    score_band: minimal
    score_composite: 1.5
    slug: arcot-systems
  - name: Concord Data Systems
    score_band: null
    score_composite: null
    slug: concord-data-systems
  name: CA Technologies (Broadcom)
  on_network: true
  permalink: /estates/ca/
  slug: ca
- has_page: true
  member_count: 3
  members:
  - name: Bluecoat (Symantec)
    score_band: emerging
    score_composite: 14.5
    slug: bluecoat-symantec
  - name: Brightmail
    score_band: null
    score_composite: null
    slug: brightmail
  - name: Fireglass
    score_band: null
    score_composite: null
    slug: fireglass
  name: Symantec
  on_network: true
  permalink: /estates/symantec/
  slug: symantec
- has_page: false
  member_count: 2
  members:
  - name: LSI
    score_band: minimal
    score_composite: 5.0
    slug: lsi
  - name: LSI Logic
    score_band: null
    score_composite: null
    slug: lsi-logic
  name: Avago Technologies
  on_network: true
  permalink: /estates/avago-technologies/
  slug: avago-technologies
- has_page: false
  member_count: 1
  members:
  - name: Tracelytics
    score_band: minimal
    score_composite: 7.5
    slug: tracelytics
  name: AppNeta
  on_network: true
  permalink: /estates/appneta/
  slug: appneta
subfamily_page_count: 3
tags:
- Cloud Infrastructure
- Gateways
- Management
- Networks
- Observability
- Virtualization
- Fortune 500
- Broadcom
title: Broadcom
---
