---
api_total: 2
category: Estates
description: OpenAI publishes a single unversioned REST API at https://api.openai.com/v1 covering text
  and reasoning (Responses, Chat Completions), embeddings, images, audio and speech, video, moderation,
  file storage, vector stores and file search, containers, batch inference at half price, fine-tuning,
  evals, ChatKit, agent skills, and a full organization administration plane for projects, users, groups,
  roles, API keys, certificates, usage and audit logs. The contract is OpenAPI 3.1.0 with 242 operations,
  published by OpenAI itself under MIT at github.com/openai/openai-openapi. Realtime is a separate WebSocket
  surface at wss://api.openai.com/v1/realtime. Authentication is a project-scoped bearer API key; OAuth
  2.0 / OIDC at auth.openai.com grants user identity only, not API authority. First-party SDKs ship for
  Python, JavaScript, Go, Java, .NET and Ruby, alongside the Codex CLI and an anonymous documentation
  MCP server at developers.openai.com/mcp.
estate_rating:
  agent_avg: 6.6
  agent_band: minimal
  agent_native: 0
  agent_raw: 0.2
  agent_ready: 0
  band: emerging
  best: 16.4
  composite_avg: 14.8
  composite_band: emerging
  composite_raw: 5.5
  developing: 0
  exemplar: 0
  rating: 11.5
  scored: 3
  spread: 16.4
  strength: 0
  strong: 0
  worst: 0.0
estate_root: null
estate_root_name: null
image: https://openai.com/favicon.ico
is_subfamily: false
layout: estate
member_bands:
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id001
    acquired: null
    agent_band: human-only
    agent_score: 0.6
    api_count: 2
    api_count_basis: split
    immediate_parent: openai
    name: Neptune.ai
    relationship: acquisition
    score_band: emerging
    score_composite: 16.4
    slug: neptune-ai
    source: prose
  label: Emerging
  open: false
- band: minimal
  blurb: Almost no public developer surface
  count: 2
  items:
  - &id002
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: openai
    name: Rockset
    relationship: acquisition
    score_band: minimal
    score_composite: 0.0
    slug: rockset
    source: prose
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 0.0
    api_count: 0
    api_count_basis: split
    immediate_parent: openai
    name: Vegafund
    relationship: product
    score_band: minimal
    score_composite: 0.0
    slug: vegafund
    source: parent-company-property
  label: Minimal
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: OpenAI
overview: 'OpenAI publishes its API surface across 3 provider profiles indexed on the APIs.io network,
  of which 3 carry a rating. The rated members span 16.4 points, from 16.4 down to 0.0.


  Its highest-rated surfaces are Neptune.ai, Rockset, Vegafund.'
parent_provider: openai
permalink: /estates/openai/
slug: openai
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- LLM
- OpenAI
- Artificial Intelligence
- Generative AI
- Chatbot
- Foundation Models
- T1
title: OpenAI
---
