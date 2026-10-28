Bankruptcy filings by chapter, court district, state and county, quarterly (U.S. Courts)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23739952

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Bankruptcy filings by chapter, court district, state and county, quarterly (U.S. Courts), version 1.0.0, https://doi.org/10.5281/zenodo.23739952, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Bankruptcy filings by chapter, court district, state and county, quarterly (U.S. Courts) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23739952

Not legal advice. These are counts from the courts' published statistics, kept for marketing planning. A filing is not a discharge or an outcome, and the courts revise the tables as their database updates; check the current table at uscourts.gov.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/bankruptcy-filings-by-county/

Columns:
  id: Stable record id (never reused)
  area: US, a 2-digit state FIPS code, a court district such as CA-C (the state, then N, S, E, W, M or C; a state with one district is just the state code) or a 5-digit county FIPS code
  areaName: The area's name; counties end with their state code
  areaType: us, state, district or county
  state: Two-letter state or territory code; empty for the United States
  period: The 12 months end on this date (YYYY-MM-DD); the window starts on the first day of the 12th month before
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: The machine value (see unit)
  unit: Unit of value
  filings: Bankruptcy cases commenced in the 12 months, all chapters
  ch7: Chapter 7 cases commenced
  ch11: Chapter 11 cases commenced
  ch13: Chapter 13 cases commenced
  other: Chapters 9, 12 and 15 and Section 304 cases commenced
  business: Cases where the court classed the debt as predominantly business
  nonbusiness: Cases where the court classed the debt as nonbusiness, mostly consumer debt
  ch7Share: Chapter 7 cases as a percent of all cases
  ch13Share: Chapter 13 cases as a percent of all cases
  priorFilings: Cases in the same 12-month window a year earlier
  changePct: Percent change on the year; empty when the year before had fewer than 10 cases (the court's rule in Table F)
  population: Census July 1, 2025 population estimate; empty for districts, territories and Connecticut counties
  perThousand: Cases per 1,000 residents; empty where there is no population
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
