---
api_total: 14
category: Estates
description: APIs and developer resources from Red Hat, a leading provider of enterprise open source solutions
  including Linux, cloud, container, and Kubernetes technologies.
estate_rating:
  agent_avg: 16.3
  agent_band: emerging
  agent_native: 0
  agent_raw: 25.4
  agent_ready: 1
  band: thin
  best: 63.2
  composite_avg: 34.0
  composite_band: thin
  composite_raw: 54.0
  developing: 2
  exemplar: 0
  rating: 26.9
  scored: 3
  spread: 14.1
  strength: 4
  strong: 1
  worst: 49.1
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
  label: Developing
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Red Hat
overview: 'Red Hat publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 14.1 points, from 63.2 down to 49.1.


  Its highest-rated surfaces are Red Hat Ansible Automation Platform, Red Hat 3scale, Red Hat OpenShift.'
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
