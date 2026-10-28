State trial-court caseloads by court level, county and case type: Texas district, constitutional county and statutory county courts, fiscal years 2023–24 and 2024–25

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23723926

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, State trial-court caseloads by court level, county and case type: Texas district, constitutional county and statutory county courts, fiscal years 2023–24 and 2024–25, version 1.0.0, https://doi.org/10.5281/zenodo.23723926, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). State trial-court caseloads by court level, county and case type: Texas district, constitutional county and statutory county courts, fiscal years 2023–24 and 2024–25 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23723926

Not legal advice. These are counts from the Texas Office of Court Administration's published statistics, kept for marketing planning. A case added is a new case or motion on a court's docket, not a person or a client. Check the Office of Court Administration's current report.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/state-courts/

Columns:
  id: Stable record id (never reused)
  state: Two-letter state code (TX for now)
  area: TX for the whole state, or TX-COUNTYNAME for a county (uppercase, hyphens for spaces)
  areaName: Area name
  areaType: us, state or cbsa
  courtLevel: district, constitutional-county or statutory-county: the court level the count is for
  courtLevelName: 
  group: The state's case group: civil, family, juvenile, criminal, felony or misdemeanor
  measure: Court level, group and what is counted: added (cases and motions put on the docket) or filed-<case type> (district-court filings by case type, statewide)
  measureLabel: 
  caseType: The state's case type, as its report names it; empty for a whole group
  fy: The state fiscal year (Texas: September 1 to August 31), e.g. 2024-25
  value: Cases added to the docket (or filed, for a case type) in the fiscal year
  unit: Unit of value
  priorFy: 
  priorValue: The same count for the year before
  change: 
  changePct: 
  disposed: Cases disposed of in the year
  pendingStart: Active cases pending at the start of the year (county rows)
  pendingEnd: Active cases pending at the end of the year
  reactivated: Cases reactivated during the year (county rows)
  inactive: Cases placed on inactive status during the year (county rows)
  population: The county's population estimate printed in the report (2024), or the sum of counties for TX
  per100k: Cases added per 100,000 residents (county and state rows, not case types)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
