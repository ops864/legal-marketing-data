Legal deserts: law offices and lawyers per resident in every U.S. county

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23721430

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Legal deserts: law offices and lawyers per resident in every U.S. county, version 1.0.0, https://doi.org/10.5281/zenodo.23721430, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Legal deserts: law offices and lawyers per resident in every U.S. county (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23721430

Not legal advice. These are counts and rates from government statistics and state bar or court registries, kept for marketing planning. A county with few offices is not a finding about anyone's access to a lawyer; bar addresses are not places of practice.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/legal-deserts/

Columns:
  id: Stable record id (never reused)
  area: County FIPS code (5 digits), state FIPS code (2 digits) or US
  areaName: County, state or nation name
  areaType: county, state or us
  state: Two-letter state code
  cbsa_type: Counties only: metro, micro or rural (outside any core-based area, OMB 2023)
  period: The quarter of the BLS office count, e.g. 2026-Q1
  population: Census population estimate for July 1, 2025
  law_offices: Private law-office establishments (BLS QCEW, NAICS 541110) in the quarter
  offices_per_10k: law_offices per 10,000 residents
  solos: Census Nonemployer Statistics 2024 legal-services firms with no employees; empty where withheld
  solos_per_10k: solos per 10,000 residents
  desert_flag_offices: true when offices_per_10k is under 1 (including none)
  no_law_office: true when the county has no private law-office establishment in the BLS count
  no_office_no_solo: true when it has no law office and the Census file shows no nonemployer legal-services firm
  bar_lawyers: Lawyers in the county from the state's own table (CA, NY, MS, IL only); see bar_status_definition
  bar_lawyers_per_1k: bar_lawyers per 1,000 residents
  desert_flag_lawyers: true when bar_lawyers_per_1k is under 1 (the ABA 2020 threshold); empty where no state count is published
  bar_status_definition: Which lawyers the state's count includes, and how the state defines the county
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: The machine value (see unit)
  unit: Unit of value
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
