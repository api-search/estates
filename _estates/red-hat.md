---
api_total: 18
category: Estates
description: APIs and developer resources from Red Hat, a leading provider of enterprise open source solutions
  including Linux, cloud, container, and Kubernetes technologies.
estate_rating:
  agent_avg: 14.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 16.7
  agent_ready: 1
  band: emerging
  best: 65.0
  composite_avg: 28.0
  composite_band: thin
  composite_raw: 34.0
  developing: 3
  exemplar: 0
  rating: 22.4
  scored: 7
  spread: 62.4
  strength: 5
  strong: 1
  worst: 2.6
estate_root: ibm
estate_root_name: IBM
image: https://www.redhat.com/cms/managed-files/Logo-Red_Hat-A-Standard-RGB.svg
is_subfamily: true
layout: estate
member_bands:
- band: strong
  blurb: Solid coverage with minor gaps
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-ready
    agent_score: 33.4
    api_count: 5
    api_count_basis: published
    immediate_parent: red-hat
    name: Red Hat Ansible Automation Platform
    relationship: product
    score_band: strong
    score_composite: 65.0
    slug: red-hat-ansible-automation-platform
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 3
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 23.7
    api_count: 5
    api_count_basis: published
    immediate_parent: red-hat
    name: Red Hat 3scale
    relationship: product
    score_band: developing
    score_composite: 49.7
    slug: red-hat-3scale
    source: declared
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 17.9
    api_count: 2
    api_count_basis: published
    immediate_parent: red-hat
    name: Red Hat OpenShift
    relationship: product
    score_band: developing
    score_composite: 48.0
    slug: red-hat-openshift
    source: declared
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 25.8
    api_count: 1
    api_count_basis: published
    immediate_parent: red-hat
    name: Red Hat Enterprise Linux 8
    relationship: product
    score_band: developing
    score_composite: 45.4
    slug: red-hat-enterprise-linux-8
    source: declared
  label: Developing
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id005
    acquired: null
    agent_band: agent-aware
    agent_score: 16.1
    api_count: 5
    api_count_basis: split
    immediate_parent: red-hat
    name: JBoss
    relationship: subsidiary
    score_band: emerging
    score_composite: 24.6
    slug: jboss
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: red-hat-openshift
    name: CoreOS
    relationship: product
    score_band: minimal
    score_composite: 2.9
    slug: coreos
    source: prose
  - &id007
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: red-hat
    name: Qumranet
    relationship: acquisition
    score_band: minimal
    score_composite: 2.6
    slug: qumranet
    source: prose
  label: Minimal
  open: false
- band: unrated
  blurb: Not yet scored
  count: 1
  items:
  - &id008
    acquired: null
    agent_band: null
    agent_score: null
    api_count: 0
    api_count_basis: split
    immediate_parent: red-hat
    name: NeuralMagic
    relationship: acquisition
    score_band: null
    score_composite: null
    slug: neuralmagic
    source: prose
  label: Unrated
  open: false
member_on_network: 8
member_total: 8
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
- *id007
- *id008
members_unrated: []
name: Red Hat
overview: 'Red Hat publishes its API surface across 8 provider profiles indexed on the APIs.io network,
  of which 8 carry a rating. The rated members span 62.4 points, from 65.0 down to 2.6.


  Its highest-rated surfaces are Red Hat Ansible Automation Platform, Red Hat 3scale, Red Hat OpenShift,
  Red Hat Enterprise Linux 8, JBoss.'
parent_provider: red-hat
permalink: /estates/red-hat/
slug: red-hat
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/red-hat/refs/heads/main/apis.yml
subfamilies:
- has_page: false
  member_count: 1
  members:
  - name: CoreOS
    score_band: minimal
    score_composite: 2.9
    slug: coreos
  name: Red Hat OpenShift
  on_network: true
  permalink: /estates/red-hat-openshift/
  slug: red-hat-openshift
tags:
- Red Hat
- Cloud
- Containers
- Enterprise
- Hybrid Cloud
- Kubernetes
- Linux
- Open Source
title: Red Hat
---
