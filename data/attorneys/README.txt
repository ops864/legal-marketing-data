Attorneys by county in Ohio, California, Michigan, Idaho, Arizona, Washington and Pennsylvania, from each bar's public counts

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23777037

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Attorneys by county in Ohio, California, Michigan, Idaho, Arizona, Washington and Pennsylvania, from each bar's public counts, version 1.0.0, https://doi.org/10.5281/zenodo.23777037, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Attorneys by county in Ohio, California, Michigan, Idaho, Arizona, Washington and Pennsylvania, from each bar's public counts (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23777037

Not legal advice. These are counts of lawyers from state bars' and courts' public count pages, reports and directory, kept for research and marketing planning. A status is the bar's record, not a judgment of any lawyer's skill or standing, and a county is the county of the address the lawyer gave, not where the lawyer practices or where clients live. Rights and deadlines in a matter are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/attorneys/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state whose bar published the count: OH, CA, MI, ID, AZ, WA or PA
  level: county; district (Idaho judicial district); county-not-given (members in the state's total whom the source's county rows do not place, derived); out-of-state (members with an address outside the state, as the source defines it); state (the source's statewide figures)
  county: 5-digit county FIPS code (vintage 2025); empty for other levels
  countyName: County name as the Census Bureau writes it; for other levels a plain label
  stateName: State name
  value: The record's main count; the unit says what it counts
  unit: What the value counts (for example active attorneys with an address in the county)
  active: Active attorneys or members in the group (Washington: only on the state and King County records)
  inactive: Inactive attorneys or members (Ohio: withheld in a few counties so that a withheld small count cannot be worked out)
  retired: Retired, senior, emeritus or permanently retired (Ohio: withheld in some counties so that a withheld small count cannot be worked out)
  deceased: Ohio: deceased registrations (withheld when 1 to 4, or where needed so a withheld count cannot be worked out)
  discipline_related: Ohio: suspended, disbarred, revoked or resigned with discipline pending (withheld when 1 to 4, or where needed so a withheld count cannot be worked out)
  other_status: Other statuses (Ohio: corporate, resigned, pending admission and others, withheld when 1 to 4, or where needed so a withheld count cannot be worked out; Idaho: emeritus and house counsel; Washington: the other license types; Pennsylvania: in-house counsel)
  total: Everyone the source counts in the group, any status
  active_in_state_county: Ohio state record: active attorneys with an address in an Ohio county
  active_outside_state: Ohio state record: active attorneys with an address elsewhere
  active_no_county: Ohio state record: active attorneys with no county on file
  population: Residents, Census estimate of July 1, 2025
  year: Year of the source's as-of date
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  effectiveFrom: As-of date as a day
  effectiveTo: As-of date as a day
  asOf: The source's as-of date: a day, a month or a year (California's page shows none, so it is the day it was read)
  basis: What the source counts, in a sentence
  lastChecked: Day the source was read
  note: Caveat for the record, if any
  admitted_pre1970: Ohio: active attorneys admitted before 1970 (withheld when 1 to 4, or where needed so a withheld count cannot be worked out); the other admitted_ columns are the decades 1970s to 2020s
  admitted_1970s: 
  admitted_1980s: 
  admitted_1990s: 
  admitted_2000s: 
  admitted_2010s: 
  admitted_2020s: 
  median_admission_year: Ohio: median admission year of the active attorneys (empty below 20)
  private_practice: Ohio and Michigan: active attorneys in private practice (Ohio withheld when 1 to 4, or where needed so a withheld count cannot be worked out)
  spanish_speaking: Ohio: active attorneys who list Spanish (withheld when 1 to 4, or where needed so a withheld count cannot be worked out)
  active_per_10k: Active attorneys per 10,000 residents, one decimal
  judge: Judges or judicial members
  not_eligible: California: licensees not eligible to practice
  barDistrict: California: State Bar district of the county; Idaho: judicial district number
  other_practice: Michigan: active members not in private practice
  prior_value: Michigan: the 2024 count
  change: Michigan: change from 2024
  districtCounties: Idaho district records: the counties in the district
  per_10k: Washington county records: WSBA licensees of every type per 10,000 residents
  sourceLabels: Source names
  sourceUrls: Source URLs
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
