Toxic chemical releases by county (EPA Toxics Release Inventory)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23753052

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Toxic chemical releases by county (EPA Toxics Release Inventory), version 1.0.0, https://doi.org/10.5281/zenodo.23753052, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Toxic chemical releases by county (EPA Toxics Release Inventory) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23753052

Not legal advice. These are pounds that covered facilities reported releasing, kept for research and market sizing. A release is not an exposure, a finding that anyone was harmed or a finding of fault, and the Toxics Release Inventory covers only listed chemicals and facilities above reporting thresholds. Questions about exposure or injury are for a licensed attorney or a health professional.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/toxic-releases/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or territory, or US
  county: 5-digit county FIPS code (vintage 2025; Connecticut's retired counties keep their old codes); empty for other levels
  countyName: County name as the Census Bureau writes it
  stateName: State name
  topParents: State records: the three largest standard parent companies by on-site pounds (businesses)
  unplaced_lbs: State records: pounds on forms whose county could not be matched to a county code (included in the state total)
  level: county, state (states and territories) or us
  reportingYear: TRI reporting year of the figures
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Same as onsite_lbs: pounds released on site in the latest reporting year
  unit: What the value counts
  facilities: Facilities that filed a TRI form for the place that year
  onsite_lbs: Total on-site releases in pounds: to air, water, land and underground, including disposal in landfills
  air_lbs: Fugitive and stack air releases in pounds
  water_lbs: Releases to surface water in pounds
  land_lbs: Releases to land in pounds: underground injection, landfills, land treatment, surface impoundments and other disposal
  carcinogens_lbs: On-site pounds of chemicals TRI flags as known or suspected carcinogens (includes ethylene oxide and benzene)
  pfas_lbs: On-site pounds of per- and polyfluoroalkyl substances on the TRI list
  ethylene_oxide_lbs: On-site pounds of ethylene oxide
  benzene_lbs: On-site pounds of benzene
  lead_lbs: On-site pounds of lead and lead compounds
  onsite_lbs_2020: On-site releases in pounds in reporting year 2020
  onsite_lbs_2021: On-site releases in pounds in reporting year 2021
  onsite_lbs_2022: On-site releases in pounds in reporting year 2022
  onsite_lbs_2023: On-site releases in pounds in reporting year 2023
  onsite_lbs_2024: On-site releases in pounds in reporting year 2024
  change_pct: Percent change in on-site pounds from the previous reporting year
  effectiveFrom: First day of the reporting year
  effectiveTo: Last day of the reporting year
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
