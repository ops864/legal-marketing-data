Federal sentencing by district and offense: individuals sentenced, prison rates and sentence lengths, fiscal years 2021 to 2025

Version 1.0.1. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24022955

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Federal sentencing by district and offense: individuals sentenced, prison rates and sentence lengths, fiscal years 2021 to 2025, version 1.0.1, https://doi.org/10.5281/zenodo.24022955, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Federal sentencing by district and offense: individuals sentenced, prison rates and sentence lengths, fiscal years 2021 to 2025 (Version 1.0.1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24022955

Not legal advice. These are counts of sentences imposed in federal court, reported to the U.S. Sentencing Commission, not predictions for any person or case. Sentences depend on the facts, the guideline range and the judge; an average says nothing about a particular defendant.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/federal-sentencing/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code of the district, or US
  level: us or district
  scope: all (every offense type) or offense (one primary offense type)
  area: US, or the district's USSC code
  areaName: United States or the district's name
  stateName: State or territory name (United States for the nation)
  districtCode: The Commission's two-digit district code (US for the nation)
  districtName: Name of the federal judicial district (All districts for the nation)
  offense: The Commission's primary offense type code 1-30 (all for all offenses)
  offenseName: Primary offense type (All offenses for all offenses)
  status: P: the Commission's own datafile
  text: The record in one plain-English sentence
  value: Individuals sentenced in the latest fiscal year (the same as sentenced)
  unit: Unit of value
  year: Latest fiscal year in the record (October to September)
  window: Fiscal years covered
  sentenced: Individuals sentenced in the latest fiscal year (felonies and Class A misdemeanors the Commission received documents for)
  prison_pct: Percent sentenced to prison, alone or with confinement conditions
  probation_pct: Percent sentenced to probation, alone or with confinement conditions
  fine_only_pct: Percent with no prison or probation (fine only)
  mean_months: Average sentence in months (prison plus months of alternative confinement), probation counted as 0 months and sentences of 470 months or more, including life, as 470, per the Commission's tables
  median_months: Median sentence in months, counted the same way
  plea_pct: Percent convicted by guilty plea
  trial_pct: Percent convicted after a trial
  effectiveFrom: First day of the latest fiscal year (October 1)
  effectiveTo: Last day of the latest fiscal year (September 30)
  lastChecked: Date the files were last re-read from the Commission
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
