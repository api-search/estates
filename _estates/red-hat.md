---
api_total: 19
category: Estates
description: APIs and developer resources from Red Hat, a leading provider of enterprise open source solutions
  including Linux, cloud, container, and Kubernetes technologies.
estate_rating:
  agent_avg: 13.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 15.7
  agent_ready: 1
  band: emerging
  best: 63.2
  composite_avg: 28.6
  composite_band: thin
  composite_raw: 34.1
  developing: 2
  exemplar: 0
  rating: 22.6
  scored: 6
  spread: 58.2
  strength: 4
  strong: 1
  worst: 5.0
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
    agent_score: 31.0
    api_count: 7
    immediate_parent: red-hat
    name: Red Hat Ansible Automation Platform
    relationship: product
    score_band: strong
    score_composite: 63.2
    slug: red-hat-ansible-automation-platform
    source: declared
  label: Strong
  open: true
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 25.5
    api_count: 5
    immediate_parent: red-hat
    name: Red Hat 3scale
    relationship: product
    score_band: developing
    score_composite: 49.6
    slug: red-hat-3scale
    source: declared
  - &id003
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 2
    immediate_parent: red-hat
    name: Red Hat OpenShift
    relationship: product
    score_band: developing
    score_composite: 49.1
    slug: red-hat-openshift
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id004
    acquired: null
    agent_band: agent-aware
    agent_score: 18.0
    api_count: 5
    immediate_parent: red-hat
    name: JBoss
    relationship: product
    score_band: thin
    score_composite: 26.7
    slug: jboss
    source: prose
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id005
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: red-hat
    name: NeuralMagic
    relationship: product
    score_band: minimal
    score_composite: 10.7
    slug: neuralmagic
    source: prose
  - &id006
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: red-hat
    name: Qumranet
    relationship: product
    score_band: minimal
    score_composite: 5.0
    slug: qumranet
    source: prose
  label: Minimal
  open: false
member_on_network: 6
member_total: 6
members:
- *id001
- *id002
- *id003
- *id004
- *id005
- *id006
members_unrated: []
name: Red Hat
overview: 'Red Hat publishes its API surface across 6 provider profiles indexed on the APIs.io network,
  of which 6 carry a rating. The rated members span 58.2 points, from 63.2 down to 5.0.


  Its highest-rated surfaces are Red Hat Ansible Automation Platform, Red Hat 3scale, Red Hat OpenShift,
  JBoss, NeuralMagic.'
parent_provider: red-hat
permalink: /estates/red-hat/
slug: red-hat
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/red-hat/refs/heads/main/apis.yml
subfamilies: []
tags:
- Cloud
- Containers
- Enterprise
- Hybrid Cloud
- Kubernetes
- Linux
- Open-Source
title: Red Hat
---
