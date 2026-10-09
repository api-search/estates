---
api_total: 9
category: Estates
description: The National Oceanic and Atmospheric Administration (NOAA) is the United States scientific
  and regulatory agency within the Department of Commerce charged with monitoring oceanic and atmospheric
  conditions, charting the seas, conducting deep-sea exploration, managing fishing and protection of marine
  mammals, and providing weather, climate, space weather, and ecosystem forecasts and warnings. NOAA's
  developer surface spans six line offices — the National Weather Service (NWS), the National Environmental
  Satellite, Data, and Information Service (NESDIS) including the National Centers for Environmental Information
  (NCEI), the National Ocean Service (NOS) including Tides & Currents (CO-OPS), the National Marine Fisheries
  Service (NMFS / NOAA Fisheries), the Office of Oceanic and Atmospheric Research (OAR), and the Office
  of Marine and Aviation Operations (OMAO). NOAA exposes free, open APIs at api.weather.gov, services.swpc.noaa.gov,
  api.tidesandcurrents.noaa.gov, ncei.noaa.gov/access, ERDDAP servers across line offices, the National
  Data Buoy Center (NDBC), and bulk forecast model output (GFS, GEFS, HRRR, GOES) through the NOAA Open
  Data Dissemination (NODD) program on AWS, GCP, and Azure.
estate_rating:
  agent_avg: 13.0
  agent_band: emerging
  agent_native: 0
  agent_raw: 17.1
  agent_ready: 0
  band: emerging
  best: 36.8
  composite_avg: 22.7
  composite_band: emerging
  composite_raw: 26.7
  developing: 0
  exemplar: 0
  rating: 18.8
  scored: 3
  spread: 24.3
  strength: 0
  strong: 0
  worst: 12.5
estate_root: null
estate_root_name: null
image: https://www.noaa.gov/themes/custom/noaa_components/logo.svg
is_subfamily: false
layout: estate
member_bands:
- band: thin
  blurb: Limited public surface area
  count: 2
  items:
  - &id001
    acquired: null
    agent_band: agent-aware
    agent_score: 25.8
    api_count: 1
    api_count_basis: published
    immediate_parent: noaa-gov
    name: Weather.gov
    relationship: division
    score_band: thin
    score_composite: 36.8
    slug: weather-gov
    source: declared
  - &id002
    acquired: null
    agent_band: agent-aware
    agent_score: 22.9
    api_count: 3
    api_count_basis: published
    immediate_parent: noaa-gov
    name: NOAA CO-OPS
    relationship: division
    score_band: thin
    score_composite: 30.7
    slug: noaa-co-ops
    source: declared
  label: Thin
  open: false
- band: emerging
  blurb: Early or largely undocumented
  count: 1
  items:
  - &id003
    acquired: null
    agent_band: human-only
    agent_score: 2.5
    api_count: 5
    api_count_basis: split
    immediate_parent: noaa-gov
    name: NDBC — National Data Buoy Center
    relationship: division
    score_band: emerging
    score_composite: 12.5
    slug: ndbc
    source: declared
  label: Emerging
  open: false
member_on_network: 3
member_total: 3
members:
- *id001
- *id002
- *id003
members_unrated: []
name: NOAA — National Oceanic and Atmospheric Administration
overview: 'NOAA — National Oceanic and Atmospheric Administration publishes its API surface across 3 provider
  profiles indexed on the APIs.io network, of which 3 carry a rating. The rated members span 24.3 points,
  from 36.8 down to 12.5.


  Its highest-rated surfaces are Weather.gov, NOAA CO-OPS, NDBC — National Data Buoy Center.'
parent_provider: noaa-gov
permalink: /estates/noaa-gov/
slug: noaa-gov
source_filename: apis.yml
source_heading: Source (apis.yml)
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/noaa-gov/refs/heads/main/apis.yml
subfamilies: []
subfamily_page_count: 0
tags:
- Weather
- Climate
- Ocean
- Space Weather
- Government
- Open Data
- Forecast
- Marine
- Atmospheric
- Hydrology
- Satellite
- Fisheries
title: NOAA — National Oceanic and Atmospheric Administration
---
