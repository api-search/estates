---
api_total: 1673
category: Estates
description: Cisco provides a comprehensive suite of APIs across its networking, security, collaboration,
  and cloud infrastructure platforms. Through Cisco DevNet, developers can access REST APIs, SDKs, and
  developer tools for Meraki, Webex, Catalyst Center, ACI, ISE, Intersight, ThousandEyes, SD-WAN, and
  other Cisco products to automate network operations, build integrations, and extend platform capabilities.
estate_rating:
  agent_avg: 22.2
  agent_band: emerging
  agent_native: 0
  agent_raw: 23.9
  agent_ready: 16
  band: thin
  best: 67.7
  composite_avg: 37.3
  composite_band: thin
  composite_raw: 39.4
  developing: 9
  exemplar: 1
  rating: 31.3
  scored: 37
  spread: 65.9
  strength: 28
  strong: 8
  worst: 1.8
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cisco.png
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 1
  items:
  - &id001
    acquired: 2020
    agent_band: agent-ready
    agent_score: 51.1
    api_count: 98
    immediate_parent: cisco
    name: ThousandEyes
    relationship: acquisition
    score_band: exemplar
    score_composite: 67.7
    slug: thousandeyes
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 8
  items:
  - &id002
    acquired: null
    agent_band: agent-ready
    agent_score: 34.0
    api_count: 197
    immediate_parent: cisco
    name: Cisco Identity Services Engine
    relationship: product
    score_band: strong
    score_composite: 65.2
    slug: cisco-ise
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 37.4
    api_count: 30
    immediate_parent: cisco
    name: Cisco Catalyst Center
    relationship: product
    score_band: strong
    score_composite: 64.2
    slug: cisco-catalyst-center
  - &id004
    acquired: 2017
    agent_band: agent-ready
    agent_score: 31.3
    api_count: 382
    immediate_parent: cisco
    name: Cisco Catalyst SD-WAN
    relationship: acquisition
    score_band: strong
    score_composite: 63.0
    slug: cisco-catalyst-sdwan
  - &id005
    acquired: 2015
    agent_band: agent-ready
    agent_score: 29.7
    api_count: 85
    immediate_parent: cisco
    name: Cisco Umbrella
    relationship: acquisition
    score_band: strong
    score_composite: 59.2
    slug: cisco-umbrella
  - &id006
    acquired: null
    agent_band: agent-ready
    agent_score: 36.7
    api_count: 83
    immediate_parent: cisco
    name: Cisco XDR
    relationship: product
    score_band: strong
    score_composite: 59.0
    slug: cisco-xdr
  - &id007
    acquired: null
    agent_band: agent-ready
    agent_score: 34.6
    api_count: 49
    immediate_parent: splunk
    name: Splunk Observability Cloud
    relationship: product
    score_band: strong
    score_composite: 58.7
    slug: splunk-observability
  - &id008
    acquired: null
    agent_band: agent-ready
    agent_score: 31.8
    api_count: 117
    immediate_parent: cisco
    name: Cisco Intersight
    relationship: product
    score_band: strong
    score_composite: 57.4
    slug: intersight
  - &id009
    acquired: 2013
    agent_band: agent-ready
    agent_score: 37.4
    api_count: 108
    immediate_parent: cisco
    name: Cisco Secure Firewall
    relationship: acquisition
    score_band: strong
    score_composite: 56.3
    slug: cisco-secure-firewall
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 9
  items:
  - &id010
    acquired: null
    agent_band: agent-ready
    agent_score: 29.3
    api_count: 3
    immediate_parent: cisco
    name: Cisco PSIRT openVuln API
    relationship: product
    score_band: developing
    score_composite: 53.9
    slug: cisco-psirt
  - &id011
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
  - &id012
    acquired: 2007
    agent_band: agent-ready
    agent_score: 43.5
    api_count: 193
    immediate_parent: cisco
    name: Webex
    relationship: acquisition
    score_band: developing
    score_composite: 51.0
    slug: webex
  - &id013
    acquired: null
    agent_band: agent-ready
    agent_score: 31.7
    api_count: 99
    immediate_parent: cisco
    name: Cisco Crosswork
    relationship: product
    score_band: developing
    score_composite: 50.6
    slug: cisco-crosswork
  - &id014
    acquired: 2024
    agent_band: agent-ready
    agent_score: 34.0
    api_count: 14
    immediate_parent: cisco
    name: Splunk
    relationship: acquisition
    score_band: developing
    score_composite: 49.7
    slug: splunk
  - &id015
    acquired: null
    agent_band: agent-ready
    agent_score: 34.2
    api_count: 21
    immediate_parent: cisco
    name: AGNTCY
    relationship: initiative
    score_band: developing
    score_composite: 45.9
    slug: agntcy
  - &id016
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 18
    immediate_parent: webex
    name: Cisco Expressway
    relationship: product
    score_band: developing
    score_composite: 42.8
    slug: cisco-expressway
  - &id017
    acquired: 2018
    agent_band: agent-aware
    agent_score: 7.9
    api_count: 1
    immediate_parent: splunk
    name: Splunk SOAR
    relationship: acquisition
    score_band: developing
    score_composite: 40.9
    slug: splunk-soar
  - &id018
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
  count: 13
  items:
  - &id019
    acquired: null
    agent_band: agent-aware
    agent_score: 24.1
    api_count: 14
    immediate_parent: webex
    name: Cisco Webex Meetings
    relationship: product
    score_band: thin
    score_composite: 37.4
    slug: cisco-webex-meetings
  - &id020
    acquired: 2024
    agent_band: agent-aware
    agent_score: 23.9
    api_count: 10
    immediate_parent: cisco
    name: Isovalent
    relationship: acquisition
    score_band: thin
    score_composite: 34.2
    slug: isovalent
  - &id021
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
  - &id022
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
  - &id023
    acquired: null
    agent_band: agent-aware
    agent_score: 20.5
    api_count: 8
    immediate_parent: cisco
    name: Cisco Support APIs
    relationship: product
    score_band: thin
    score_composite: 32.0
    slug: cisco-support-apis
  - &id024
    acquired: 2019
    agent_band: human-only
    agent_score: 2.5
    api_count: 1
    immediate_parent: splunk
    name: SignalFx
    relationship: acquisition
    score_band: thin
    score_composite: 31.9
    slug: signalfx
  - &id025
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 4
    immediate_parent: webex
    name: Cisco Directory Connector
    relationship: product
    score_band: thin
    score_composite: 31.1
    slug: cisco-directory-connector
  - &id026
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
  - &id027
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
  - &id028
    acquired: 2017
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 25
    immediate_parent: cisco
    name: AppDynamics
    relationship: acquisition
    score_band: thin
    score_composite: 27.9
    slug: appdynamics
  - &id029
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
  - &id030
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 7
    immediate_parent: webex
    name: Cisco Control Hub
    relationship: product
    score_band: thin
    score_composite: 27.7
    slug: cisco-control-hub
  - &id031
    acquired: 2018
    agent_band: agent-aware
    agent_score: 12.9
    api_count: 2
    immediate_parent: splunk
    name: Splunk On-Call (VictorOps)
    relationship: acquisition
    score_band: thin
    score_composite: 26.8
    slug: victorops
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 3
  items:
  - &id032
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 12
    immediate_parent: webex
    name: Cisco Collaboration Hybrid Solutions
    relationship: product
    score_band: emerging
    score_composite: 24.1
    slug: cisco-collaboration-hybrid-solutions
  - &id033
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
  - &id034
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
  - &id035
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
  - &id036
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
  - &id037
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
member_on_network: 37
member_total: 37
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
- *id032
- *id033
- *id034
- *id035
- *id036
- *id037
members_unrated: []
name: Cisco
overview: 'Cisco publishes its API surface across 37 provider profiles indexed on the APIs.io network,
  of which 37 carry a rating. The rated members span 65.9 points, from 67.7 down to 1.8.


  Its highest-rated surfaces are ThousandEyes, Cisco Identity Services Engine, Cisco Catalyst Center,
  Cisco Catalyst SD-WAN, Cisco Umbrella.'
parent_provider: cisco
permalink: /estates/cisco/
slug: cisco
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco/refs/heads/main/apis.yml
subfamilies:
- member_count: 5
  members:
  - name: Cisco Expressway
    score_band: developing
    score_composite: 42.8
    slug: cisco-expressway
  - name: Cisco Webex Meetings
    score_band: thin
    score_composite: 37.4
    slug: cisco-webex-meetings
  - name: Cisco Directory Connector
    score_band: thin
    score_composite: 31.1
    slug: cisco-directory-connector
  - name: Cisco Control Hub
    score_band: thin
    score_composite: 27.7
    slug: cisco-control-hub
  - name: Cisco Collaboration Hybrid Solutions
    score_band: emerging
    score_composite: 24.1
    slug: cisco-collaboration-hybrid-solutions
  name: Webex
  on_network: true
  slug: webex
- member_count: 4
  members:
  - name: Splunk Observability Cloud
    score_band: strong
    score_composite: 58.7
    slug: splunk-observability
  - name: Splunk SOAR
    score_band: developing
    score_composite: 40.9
    slug: splunk-soar
  - name: SignalFx
    score_band: thin
    score_composite: 31.9
    slug: signalfx
  - name: Splunk On-Call (VictorOps)
    score_band: thin
    score_composite: 26.8
    slug: victorops
  name: Splunk
  on_network: true
  slug: splunk
tags:
- Fortune 100
- Collaboration
- Enterprise
- Networking
- Security
- SD-WAN
title: Cisco
---
