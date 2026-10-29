State trial-court case filings by county, court level and case type: Texas, Washington, Maryland, Indiana and Wisconsin (more states to follow)

Version 1.1.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23753032

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, State trial-court case filings by county, court level and case type: Texas, Washington, Maryland, Indiana and Wisconsin (more states to follow), version 1.1.0, https://doi.org/10.5281/zenodo.23753032, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). State trial-court case filings by county, court level and case type: Texas, Washington, Maryland, Indiana and Wisconsin (more states to follow) (Version 1.1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23753032

Not legal advice. These are counts from the Texas Office of Court Administration's published statistics, kept for marketing planning. A case added is a new case or motion on a court's docket, not a person or a client. Check the Office of Court Administration's current report.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/state-courts/

Columns:
  id: Stable record id (never reused)
  state: Two-letter state code (TX, WA, MD, IN or WI so far)
  area: The state code for the whole state, or STATE-COUNTYNAME for a county (uppercase, hyphens for spaces), e.g. WA-KING, MD-BALTIMORE-CITY
  areaName: Area name
  areaType: us, state or cbsa
  courtLevel: The court level the count is for (Texas: district, constitutional-county or statutory-county; Washington: superior or limited; Maryland: circuit or district; Indiana: trial; Wisconsin: circuit)
  courtLevelName: 
  group: The group: civil, family, probate, juvenile, criminal, traffic, small-claims or landlord-tenant (Texas: civil, family, juvenile, criminal, felony or misdemeanor)
  measure: Texas: court level, group and what is counted. Other states: the harmonized group (for example civil-eviction, family-divorce, criminal-dui)
  measureLabel: 
  caseType: The state's own category or categories added into the value, as the state names them; empty for a whole group (Texas)
  harm: Our harmonized group for non-Texas states; empty for Texas
  practices: The practice-area ids from the shared taxonomy (/data/v1/crosswalks/) the group bears on, separated by semicolons
  periodKind: fiscal year or calendar year: what the state counts by
  fy: The period: a Texas or Maryland fiscal year (e.g. 2024-25) or a calendar year (Washington, Indiana)
  value: Cases filed in the period (Texas: added to the docket; Wisconsin: cases opened, the state's Total Opened)
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
