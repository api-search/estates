---
api_total: 910
category: Estates
description: Cisco provides a comprehensive suite of APIs across its networking, security, collaboration,
  and cloud infrastructure platforms. Through Cisco DevNet, developers can access REST APIs, SDKs, and
  developer tools for Meraki, Webex, Catalyst Center, ACI, ISE, Intersight, ThousandEyes, SD-WAN, and
  other Cisco products to automate network operations, build integrations, and extend platform capabilities.
estate_rating:
  agent_avg: 22.9
  agent_band: emerging
  agent_native: 0
  agent_raw: 25.3
  agent_ready: 13
  band: thin
  best: 69.9
  composite_avg: 38.0
  composite_band: thin
  composite_raw: 41.0
  developing: 7
  exemplar: 2
  rating: 32.0
  scored: 28
  spread: 68.1
  strength: 25
  strong: 6
  worst: 1.8
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cisco.png
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 2
  items:
  - &id001
    acquired: 2020
    agent_band: agent-ready
    agent_score: 51.1
    api_count: 26
    immediate_parent: cisco
    name: ThousandEyes
    relationship: acquisition
    score_band: exemplar
    score_composite: 69.9
    slug: thousandeyes
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 34.0
    api_count: 197
    immediate_parent: cisco
    name: Cisco Identity Services Engine
    relationship: product
    score_band: exemplar
    score_composite: 67.8
    slug: cisco-ise
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 6
  items:
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 37.4
    api_count: 30
    immediate_parent: cisco
    name: Cisco Catalyst Center
    relationship: product
    score_band: strong
    score_composite: 65.9
    slug: cisco-catalyst-center
  - &id004
    acquired: 2017
    agent_band: agent-aware
    agent_score: 26.3
    api_count: 13
    immediate_parent: cisco
    name: Cisco Catalyst SD-WAN
    relationship: acquisition
    score_band: strong
    score_composite: 61.8
    slug: cisco-catalyst-sdwan
  - &id005
    acquired: 2015
    agent_band: agent-ready
    agent_score: 29.7
    api_count: 26
    immediate_parent: cisco
    name: Cisco Umbrella
    relationship: acquisition
    score_band: strong
    score_composite: 61.0
    slug: cisco-umbrella
  - &id006
    acquired: null
    agent_band: agent-ready
    agent_score: 36.7
    api_count: 50
    immediate_parent: cisco
    name: Cisco XDR
    relationship: product
    score_band: strong
    score_composite: 60.7
    slug: cisco-xdr
  - &id007
    acquired: 2013
    agent_band: agent-ready
    agent_score: 37.4
    api_count: 108
    immediate_parent: cisco
    name: Cisco Secure Firewall
    relationship: acquisition
    score_band: strong
    score_composite: 57.8
    slug: cisco-secure-firewall
  - &id008
    acquired: null
    agent_band: agent-ready
    agent_score: 29.3
    api_count: 3
    immediate_parent: cisco
    name: Cisco PSIRT openVuln API
    relationship: product
    score_band: strong
    score_composite: 56.4
    slug: cisco-psirt
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 7
  items:
  - &id009
    acquired: null
    agent_band: agent-ready
    agent_score: 35.5
    api_count: 1
    immediate_parent: cisco
    name: Cisco ACI
    relationship: product
    score_band: developing
    score_composite: 53.5
    slug: cisco-aci
  - &id010
    acquired: null
    agent_band: agent-ready
    agent_score: 31.7
    api_count: 99
    immediate_parent: cisco
    name: Cisco Crosswork
    relationship: product
    score_band: developing
    score_composite: 52.9
    slug: cisco-crosswork
  - &id011
    acquired: null
    agent_band: agent-aware
    agent_score: 25.0
    api_count: 11
    immediate_parent: cisco
    name: Cisco Intersight
    relationship: product
    score_band: developing
    score_composite: 52.8
    slug: intersight
  - &id012
    acquired: 2007
    agent_band: agent-ready
    agent_score: 43.5
    api_count: 193
    immediate_parent: cisco
    name: Webex
    relationship: acquisition
    score_band: developing
    score_composite: 50.1
    slug: webex
  - &id013
    acquired: 2024
    agent_band: agent-ready
    agent_score: 34.0
    api_count: 14
    immediate_parent: cisco
    name: Splunk
    relationship: acquisition
    score_band: developing
    score_composite: 48.0
    slug: splunk
  - &id014
    acquired: null
    agent_band: agent-ready
    agent_score: 31.3
    api_count: 5
    immediate_parent: cisco
    name: AGNTCY
    relationship: initiative
    score_band: developing
    score_composite: 46.7
    slug: agntcy
  - &id015
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 11
    immediate_parent: cisco
    name: Cisco Hardware
    relationship: product
    score_band: developing
    score_composite: 39.7
    slug: cisco-hardware
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 8
  items:
  - &id016
    acquired: 2024
    agent_band: agent-aware
    agent_score: 23.9
    api_count: 10
    immediate_parent: cisco
    name: Isovalent
    relationship: acquisition
    score_band: thin
    score_composite: 35.7
    slug: isovalent
  - &id017
    acquired: null
    agent_band: agent-aware
    agent_score: 20.5
    api_count: 8
    immediate_parent: cisco
    name: Cisco Support APIs
    relationship: product
    score_band: thin
    score_composite: 33.1
    slug: cisco-support-apis
  - &id018
    acquired: null
    agent_band: agent-aware
    agent_score: 20.9
    api_count: 24
    immediate_parent: cisco
    name: Cisco Voice Portal
    relationship: product
    score_band: thin
    score_composite: 32.2
    slug: cisco-voice-portal
  - &id019
    acquired: null
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 16
    immediate_parent: cisco
    name: Cisco Nexus Dashboard
    relationship: product
    score_band: thin
    score_composite: 32.0
    slug: cisco-nexus
  - &id020
    acquired: 2012
    agent_band: agent-ready
    agent_score: 31.2
    api_count: 21
    immediate_parent: cisco
    name: Cisco Meraki
    relationship: acquisition
    score_band: thin
    score_composite: 30.7
    slug: cisco-meraki
  - &id021
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 11
    immediate_parent: cisco
    name: Cisco Secure Client
    relationship: product
    score_band: thin
    score_composite: 28.3
    slug: cisco-secure-client
  - &id022
    acquired: 2017
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 25
    immediate_parent: cisco
    name: AppDynamics
    relationship: acquisition
    score_band: thin
    score_composite: 28.0
    slug: appdynamics
  - &id023
    acquired: 2023
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 0
    immediate_parent: cisco
    name: Valtix
    relationship: acquisition
    score_band: thin
    score_composite: 27.8
    slug: valtix
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 2
  items:
  - &id024
    acquired: 2018
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 7
    immediate_parent: cisco
    name: Duo Security
    relationship: acquisition
    score_band: emerging
    score_composite: 20.0
    slug: duo-security
  - &id025
    acquired: 2021
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: cisco
    name: Kenna Security
    relationship: acquisition
    score_band: emerging
    score_composite: 19.9
    slug: kenna-security
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 3
  items:
  - &id026
    acquired: 2021
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: Epsagon
    relationship: acquisition
    score_band: minimal
    score_composite: 7.5
    slug: epsagon
  - &id027
    acquired: 2021
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: Acacia
    relationship: acquisition
    score_band: minimal
    score_composite: 6.4
    slug: acacia
  - &id028
    acquired: 2018
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: Broadsoft
    relationship: acquisition
    score_band: minimal
    score_composite: 1.8
    slug: broadsoft
  label: Minimal
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
name: Cisco
overview: 'Cisco publishes its API surface across 28 provider profiles indexed on the APIs.io network,
  of which 28 carry a rating. The rated members span 68.1 points, from 69.9 down to 1.8.


  Its highest-rated surfaces are ThousandEyes, Cisco Identity Services Engine, Cisco Catalyst Center,
  Cisco Catalyst SD-WAN, Cisco Umbrella.'
parent_provider: cisco
permalink: /estates/cisco/
slug: cisco
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco/refs/heads/main/apis.yml
tags:
- Fortune 100
- Collaboration
- Enterprise
- Networking
- Security
- SD-WAN
title: Cisco
---
