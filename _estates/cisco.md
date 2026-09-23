---
api_total: 444
category: Estates
description: Cisco provides a comprehensive suite of APIs across its networking, security, collaboration,
  and cloud infrastructure platforms. Through Cisco DevNet, developers can access REST APIs, SDKs, and
  developer tools for Meraki, Webex, Catalyst Center, ACI, ISE, Intersight, ThousandEyes, SD-WAN, and
  other Cisco products to automate network operations, build integrations, and extend platform capabilities.
estate_rating:
  agent_avg: 18.1
  agent_band: emerging
  agent_native: 1
  agent_raw: 18.7
  agent_ready: 15
  band: thin
  best: 72.1
  composite_avg: 33.6
  composite_band: thin
  composite_raw: 34.7
  developing: 13
  exemplar: 2
  rating: 27.4
  scored: 49
  spread: 70.3
  strength: 37
  strong: 9
  worst: 1.8
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cisco.png
is_subfamily: false
layout: estate
member_bands:
- band: exemplar
  blurb: Complete, well-documented, and agent-ready
  count: 2
  items:
  - &id001
    acquired: 2020
    agent_band: agent-ready
    agent_score: 56.3
    api_count: 53
    immediate_parent: cisco
    name: ThousandEyes
    relationship: acquisition
    score_band: exemplar
    score_composite: 72.1
    slug: thousandeyes
    source: declared
  - &id002
    acquired: 2017
    agent_band: agent-ready
    agent_score: 33.1
    api_count: 13
    immediate_parent: cisco
    name: Cisco Catalyst SD-WAN
    relationship: acquisition
    score_band: exemplar
    score_composite: 68.4
    slug: cisco-catalyst-sdwan
    source: declared
  label: Exemplar
  open: true
- band: strong
  blurb: Solid coverage with minor gaps
  count: 9
  items:
  - &id003
    acquired: null
    agent_band: agent-ready
    agent_score: 38.3
    api_count: 104
    immediate_parent: cisco
    name: Cisco Identity Services Engine
    relationship: product
    score_band: strong
    score_composite: 64.4
    slug: cisco-ise
    source: declared
  - &id004
    acquired: null
    agent_band: agent-ready
    agent_score: 37.4
    api_count: 27
    immediate_parent: cisco
    name: Cisco Catalyst Center
    relationship: product
    score_band: strong
    score_composite: 63.4
    slug: cisco-catalyst-center
    source: declared
  - &id005
    acquired: null
    agent_band: agent-ready
    agent_score: 38.5
    api_count: 12
    immediate_parent: cisco
    name: Cisco XDR
    relationship: product
    score_band: strong
    score_composite: 63.2
    slug: cisco-xdr
    source: declared
  - &id006
    acquired: null
    agent_band: agent-ready
    agent_score: 34.6
    api_count: 48
    immediate_parent: splunk
    name: Splunk Observability Cloud
    relationship: product
    score_band: strong
    score_composite: 62.9
    slug: splunk-observability
    source: declared
  - &id007
    acquired: 2015
    agent_band: agent-ready
    agent_score: 29.7
    api_count: 52
    immediate_parent: cisco
    name: Cisco Umbrella
    relationship: acquisition
    score_band: strong
    score_composite: 59.3
    slug: cisco-umbrella
    source: declared
  - &id008
    acquired: 2013
    agent_band: agent-ready
    agent_score: 39.2
    api_count: 14
    immediate_parent: cisco
    name: Cisco Secure Firewall
    relationship: acquisition
    score_band: strong
    score_composite: 59.2
    slug: cisco-secure-firewall
    source: declared
  - &id009
    acquired: null
    agent_band: agent-ready
    agent_score: 33.6
    api_count: 11
    immediate_parent: cisco
    name: Cisco Intersight
    relationship: product
    score_band: strong
    score_composite: 57.7
    slug: intersight
    source: declared
  - &id010
    acquired: 2007
    agent_band: agent-ready
    agent_score: 43.5
    api_count: 9
    immediate_parent: cisco
    name: Webex
    relationship: acquisition
    score_band: strong
    score_composite: 55.4
    slug: webex
    source: declared
  - &id011
    acquired: null
    agent_band: agent-ready
    agent_score: 34.0
    api_count: 1
    immediate_parent: cisco
    name: Cisco PSIRT openVuln API
    relationship: product
    score_band: strong
    score_composite: 55.0
    slug: cisco-psirt
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 13
  items:
  - &id012
    acquired: 2024
    agent_band: agent-ready
    agent_score: 34.0
    api_count: 1
    immediate_parent: cisco
    name: Splunk
    relationship: acquisition
    score_band: developing
    score_composite: 54.0
    slug: splunk
    source: declared
  - &id013
    acquired: null
    agent_band: agent-ready
    agent_score: 35.5
    api_count: 1
    immediate_parent: cisco
    name: Cisco ACI
    relationship: product
    score_band: developing
    score_composite: 53.7
    slug: cisco-aci
    source: declared
  - &id014
    acquired: null
    agent_band: agent-ready
    agent_score: 35.1
    api_count: 50
    immediate_parent: cisco
    name: Cisco Crosswork
    relationship: product
    score_band: developing
    score_composite: 52.1
    slug: cisco-crosswork
    source: declared
  - &id015
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 2
    immediate_parent: webex
    name: Cisco Expressway
    relationship: product
    score_band: developing
    score_composite: 52.0
    slug: cisco-expressway
    source: declared
  - &id016
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: cisco
    name: Cisco Hardware
    relationship: product
    score_band: developing
    score_composite: 48.3
    slug: cisco-hardware
    source: declared
  - &id017
    acquired: null
    agent_band: agent-native
    agent_score: 39.2
    api_count: 4
    immediate_parent: cisco
    name: AGNTCY
    relationship: initiative
    score_band: developing
    score_composite: 47.9
    slug: agntcy
    source: declared
  - &id018
    acquired: null
    agent_band: agent-aware
    agent_score: 24.1
    api_count: 1
    immediate_parent: webex
    name: Cisco Webex Meetings
    relationship: product
    score_band: developing
    score_composite: 46.4
    slug: cisco-webex-meetings
    source: declared
  - &id019
    acquired: null
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 1
    immediate_parent: cisco
    name: Cisco Nexus Dashboard
    relationship: product
    score_band: developing
    score_composite: 42.2
    slug: cisco-nexus
    source: declared
  - &id020
    acquired: 2018
    agent_band: agent-aware
    agent_score: 7.9
    api_count: 1
    immediate_parent: splunk
    name: Splunk SOAR
    relationship: acquisition
    score_band: developing
    score_composite: 42.0
    slug: splunk-soar
    source: declared
  - &id021
    acquired: null
    agent_band: agent-aware
    agent_score: 20.9
    api_count: 4
    immediate_parent: cisco
    name: Cisco Voice Portal
    relationship: product
    score_band: developing
    score_composite: 41.6
    slug: cisco-voice-portal
    source: declared
  - &id022
    acquired: 2024
    agent_band: agent-aware
    agent_score: 23.9
    api_count: 2
    immediate_parent: cisco
    name: Isovalent
    relationship: acquisition
    score_band: developing
    score_composite: 40.7
    slug: isovalent
    source: declared
  - &id023
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: webex
    name: Cisco Directory Connector
    relationship: product
    score_band: developing
    score_composite: 40.3
    slug: cisco-directory-connector
    source: declared
  - &id024
    acquired: 2017
    agent_band: agent-aware
    agent_score: 22.3
    api_count: 9
    immediate_parent: cisco
    name: AppDynamics
    relationship: acquisition
    score_band: developing
    score_composite: 39.3
    slug: appdynamics
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 9
  items:
  - &id025
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: cisco
    name: Cisco Secure Client
    relationship: product
    score_band: thin
    score_composite: 36.9
    slug: cisco-secure-client
    source: declared
  - &id026
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: webex
    name: Cisco Control Hub
    relationship: product
    score_band: thin
    score_composite: 35.9
    slug: cisco-control-hub
    source: declared
  - &id027
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
    source: declared
  - &id028
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: webex
    name: Cisco Collaboration Hybrid Solutions
    relationship: product
    score_band: thin
    score_composite: 32.2
    slug: cisco-collaboration-hybrid-solutions
    source: declared
  - &id029
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
    source: declared
  - &id030
    acquired: 2012
    agent_band: agent-ready
    agent_score: 31.2
    api_count: 6
    immediate_parent: cisco
    name: Cisco Meraki
    relationship: acquisition
    score_band: thin
    score_composite: 30.0
    slug: cisco-meraki
    source: declared
  - &id031
    acquired: 2018
    agent_band: agent-aware
    agent_score: 21.5
    api_count: 1
    immediate_parent: cisco
    name: Duo Security
    relationship: acquisition
    score_band: thin
    score_composite: 28.4
    slug: duo-security
    source: declared
  - &id032
    acquired: 2023
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 0
    immediate_parent: cisco
    name: Valtix
    relationship: acquisition
    score_band: thin
    score_composite: 27.5
    slug: valtix
    source: declared
  - &id033
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
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 5
  items:
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
    source: declared
  - &id035
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: Astrix Security
    relationship: product
    score_band: emerging
    score_composite: 15.5
    slug: astrix-security
    source: parent-company-property
  - &id036
    acquired: null
    agent_band: agent-aware
    agent_score: 5.4
    api_count: 0
    immediate_parent: cisco
    name: CloudLock
    relationship: product
    score_band: emerging
    score_composite: 15.0
    slug: cloudlock
    source: parent-company-property
  - &id037
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: OpenDNS
    relationship: product
    score_band: emerging
    score_composite: 12.8
    slug: opendns
    source: parent-company-property
  - &id038
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: MindMeld *
    relationship: product
    score_band: emerging
    score_composite: 12.4
    slug: mindmeld
    source: parent-company-property
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 11
  items:
  - &id039
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: Opsani
    relationship: product
    score_band: minimal
    score_composite: 10.4
    slug: opsani
    source: prose
  - &id040
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
    source: declared
  - &id041
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
    source: declared
  - &id042
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: 1 Mainstream
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: 1-mainstream
    source: prose
  - &id043
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: Metacloud
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: metacloud
    source: parent-company-property
  - &id044
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: Prism Skylabs
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: prism-skylabs
    source: parent-company-property
  - &id045
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: splunk
    name: Rocana
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: rocana
    source: parent-company-property
  - &id046
    acquired:
      announced: '2019-08-06'
      by: cisco
      evidence: https://newsroom.cisco.com/press-release-content?type=webcontent&articleId=2007901
      notes: Rebranded Voicera to Voicea prior to acquisition; technology absorbed into Cisco Webex Assistant.
        voicera.com unreachable and voicea.com returns 404 / redirects to webex.com as of 2026-07-21.
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: Voicera
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: voicera
    source: prose
  - &id047
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: cisco
    name: WorkLife
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: worklife
    source: prose
  - &id048
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: splunk
    name: Streamlio
    relationship: product
    score_band: minimal
    score_composite: 4.1
    slug: streamlio
    source: prose
  - &id049
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
    source: declared
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id050
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    immediate_parent: cisco
    name: Accompany
    relationship: product
    score_band: null
    score_composite: null
    slug: accompany
    source: prose
  label: Unrated
  open: false
member_on_network: 50
member_total: 50
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
- *id038
- *id039
- *id040
- *id041
- *id042
- *id043
- *id044
- *id045
- *id046
- *id047
- *id048
- *id049
- *id050
members_unrated: []
name: Cisco
overview: 'Cisco publishes its API surface across 50 provider profiles indexed on the APIs.io network,
  of which 50 carry a rating. The rated members span 70.3 points, from 72.1 down to 1.8.


  Its highest-rated surfaces are ThousandEyes, Cisco Catalyst SD-WAN, Cisco Identity Services Engine,
  Cisco Catalyst Center, Cisco XDR.'
parent_provider: cisco
permalink: /estates/cisco/
slug: cisco
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco/refs/heads/main/apis.yml
subfamilies:
- has_page: true
  member_count: 6
  members:
  - name: Splunk Observability Cloud
    score_band: strong
    score_composite: 62.9
    slug: splunk-observability
  - name: Splunk SOAR
    score_band: developing
    score_composite: 42.0
    slug: splunk-soar
  - name: SignalFx
    score_band: thin
    score_composite: 31.9
    slug: signalfx
  - name: Splunk On-Call (VictorOps)
    score_band: thin
    score_composite: 26.8
    slug: victorops
  - name: Rocana
    score_band: minimal
    score_composite: 5.0
    slug: rocana
  - name: Streamlio
    score_band: minimal
    score_composite: 4.1
    slug: streamlio
  name: Splunk
  on_network: true
  permalink: /estates/splunk/
  slug: splunk
- has_page: true
  member_count: 5
  members:
  - name: Cisco Expressway
    score_band: developing
    score_composite: 52.0
    slug: cisco-expressway
  - name: Cisco Webex Meetings
    score_band: developing
    score_composite: 46.4
    slug: cisco-webex-meetings
  - name: Cisco Directory Connector
    score_band: developing
    score_composite: 40.3
    slug: cisco-directory-connector
  - name: Cisco Control Hub
    score_band: thin
    score_composite: 35.9
    slug: cisco-control-hub
  - name: Cisco Collaboration Hybrid Solutions
    score_band: thin
    score_composite: 32.2
    slug: cisco-collaboration-hybrid-solutions
  name: Webex
  on_network: true
  permalink: /estates/webex/
  slug: webex
subfamily_page_count: 2
tags:
- Fortune 100
- Collaboration
- Enterprise
- Networking
- Security
- SD-WAN
title: Cisco
---
