WARN Act layoff and closure notices by county: California and Texas

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23753097

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, WARN Act layoff and closure notices by county: California and Texas, version 1.0.0, https://doi.org/10.5281/zenodo.23753097, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). WARN Act layoff and closure notices by county: California and Texas (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23753097

Not legal advice. These are counts of notices employers filed with state agencies, kept for research and marketing planning. A notice is a plan, not a layoff that has happened, and says nothing about whether any worker has a legal claim; rights and deadlines are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/warn-layoffs/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code (CA or TX)
  level: county, county-not-given (blank or out-of-state sites) or state
  county: 5-digit county FIPS code; empty for other levels
  countyName: 
  stateName: 
  period: 
  year: 
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Notices received in the 12 months to the end of the file
  unit: Unit of value
  warn_notices_12m: WARN notices received in the 12 months to coverage_to (one per work site)
  warn_employees_12m: Employees those notices cover, as the employer reported
  last_complete_year: The last complete calendar year in the file
  warn_notices_last_year: Notices received in that year
  warn_employees_last_year: Employees covered in that year
  warn_notices_total: Notices received since coverage_from
  warn_employees_total: Employees covered since coverage_from
  coverage_from: Date of the first notice in the state's file
  coverage_to: Date of the last notice in the state's file
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
