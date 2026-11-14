Railroad casualties and crossing incidents by county (FRA Forms 55a, 57 and 54)

Version 2.0.1. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24116057

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Railroad casualties and crossing incidents by county (FRA Forms 55a, 57 and 54), version 2.0.1, https://doi.org/10.5281/zenodo.24116057, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Railroad casualties and crossing incidents by county (FRA Forms 55a, 57 and 54) (Version 2.0.1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24116057

Cite as: Probative Growth, Railroad casualties and crossing incidents by county (FRA Forms 55a, 57 and 54), 2026, https://doi.org/10.5281/zenodo.24116057

Not legal advice. These are counts of events railroads reported to the Federal Railroad Administration, kept for research and market sizing. A report is not a finding of fault, and it says nothing about whether anyone has a claim; a railroad employee's injury claim has its own federal rules and deadlines. Questions about an injury are for a licensed attorney.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/rail-casualties/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or territory, or US
  level: county, state (states and DC) or us
  yearsFrom: First incident year kept
  yearsTo: Last incident year kept
  dataThrough: Date of the latest casualty in FRA's Form 55a view
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: Same as casualties
  unit: What the value counts
  casualties: Railroad casualties (deaths plus nonfatal injuries and illnesses) reported on Form 55a
  deaths: Casualties that were fatal
  injuries: Nonfatal injuries and illnesses
  employee_on_duty: Casualties of railroad employees on duty
  employee_off_duty: Casualties of railroad employees not on duty
  contractor_volunteer: Casualties of contractors and volunteers (on duty or not)
  passenger: Casualties of passengers on trains
  trespasser: Casualties of trespassers
  nontrespasser: Casualties of non-trespassers on or off railroad property
  other_person: Casualties with no person class on the report
  employee_casualties: employee_on_duty + employee_off_duty
  employee_deaths: Deaths among railroad employees (on or off duty)
  crossing_incidents: Highway-rail grade crossing incidents reported on Form 57
  crossing_killed: People killed in those incidents (Form 57 total killed)
  crossing_injured: People injured in those incidents (Form 57 total injured)
  train_accidents: Rail equipment accidents and incidents above FRA's damage threshold (Form 54)
  casualties_2021: Casualties with an incident date in 2021
  casualties_2022: Casualties with an incident date in 2022
  casualties_2023: Casualties with an incident date in 2023
  casualties_2024: Casualties with an incident date in 2024
  casualties_2025: Casualties with an incident date in 2025
  casualties_2026: Casualties with an incident date in 2026 (through July)
  effectiveFrom: First day of the first incident year kept
  effectiveTo: Date of the latest casualty
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  county: 5-digit county FIPS code (vintage 2025; Connecticut's retired counties keep their old codes); empty for other levels (in rail-casualties-values.csv, as id, column and value rows)
  countyName: County name as the Census Bureau writes it (in rail-casualties-values.csv, as id, column and value rows)
  stateName: State name (in rail-casualties-values.csv, as id, column and value rows)
  unplaced: State records: reports FRA gives no usable county for (included in the state totals) (in rail-casualties-values.csv, as id, column and value rows)
