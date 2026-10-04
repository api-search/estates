---
api_total: 2
category: Estates
description: 'Anthropic is an AI safety company and the creator of the Claude family of large language
  models (Opus, Sonnet, Haiku, and the Fable/Mythos frontier line). The Claude Developer Platform exposes
  them through a single REST API at api.anthropic.com: the Messages API for text, vision, tool use, thinking,
  streaming and structured outputs; Message Batches for asynchronous work at half price; Files, Token
  Counting, Models, and experimental Prompt Tools; Managed Agents with sessions, environments, memory
  stores, vaults and scheduled deployments; a Skills API; and an Admin API for organizations, workspaces,
  members, invites and API keys. Authentication is x-api-key with a required anthropic-version date header
  and dated anthropic-beta opt-ins. Anthropic also authors two of the open standards the agent ecosystem
  runs on — the Model Context Protocol and the Agent Skills specification — and ships Claude Code, the
  terminal agentic coding tool, which doubles as a first-party stdio MCP server.'
estate_rating:
  agent_avg: 12.5
  agent_band: emerging
  agent_native: 0
  agent_raw: 15.6
  agent_ready: 0
  band: emerging
  best: 53.6
  composite_avg: 25.4
  composite_band: thin
  composite_raw: 33.6
  developing: 1
  exemplar: 0
  rating: 20.2
  scored: 3
  spread: 45.0
  strength: 1
  strong: 0
  worst: 8.6
estate_root: null
estate_root_name: null
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/anthropic.png
is_subfamily: false
layout: estate
member_bands:
- band: developing
  blurb: Usable, with meaningful gaps to close
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 27.1
    api_count: 1
    immediate_parent: anthropic
    name: Claude
    relationship: product
    score_band: developing
    score_composite: 53.6
    slug: claude
    source: declared
  label: Developing
  open: false
- band: thin
  blurb: Limited public surface area
  count: 1
  items:
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 19.8
    api_count: 1
    immediate_parent: anthropic
    name: Humanloop
    relationship: product
    score_band: thin
    score_composite: 38.6
    slug: humanloop
    source: parent-company-property
  label: Thin
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    immediate_parent: anthropic
    name: Vercept
    relationship: acquisition
    score_band: minimal
    score_composite: 8.6
    slug: vercept
    source: prose
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: Anthropic
overview: 'Anthropic publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 45.0 points, from 53.6 down to 8.6.


  Its highest-rated surfaces are Claude, Humanloop, Vercept.'
parent_provider: anthropic
permalink: /estates/anthropic/
slug: anthropic
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/anthropic/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- LLM
- Anthropic
- Artificial Intelligence
- Claude
- Foundation Models
- Machine Learning
- MCP
- Agents
title: Anthropic
---
