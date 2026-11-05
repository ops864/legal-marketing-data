Attorneys by county in Ohio, California, Michigan, Idaho, Arizona, Washington and Pennsylvania, from each bar's public counts

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23962861

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Attorneys by county in Ohio, California, Michigan, Idaho, Arizona, Washington and Pennsylvania, from each bar's public counts, version 2.0.0, https://doi.org/10.5281/zenodo.23962861, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Attorneys by county in Ohio, California, Michigan, Idaho, Arizona, Washington and Pennsylvania, from each bar's public counts (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23962861

Not legal advice. These are counts of lawyers from state bars' and courts' public count pages, reports and directory, kept for research and marketing planning. A status is the bar's record, not a judgment of any lawyer's skill or standing, and a county is the county of the address the lawyer gave, not where the lawyer practices or where clients live. Rights and deadlines in a matter are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/attorneys/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state whose bar published the count: OH, CA, MI, ID, AZ, WA or PA
  level: county; district (Idaho judicial district); county-not-given (members in the state's total whom the source's county rows do not place, derived); out-of-state (members with an address outside the state, as the source defines it); state (the source's statewide figures)
  countyName: County name as the Census Bureau writes it; for other levels a plain label
  stateName: State name
  value: The record's main count; the unit says what it counts
  unit: What the value counts (for example active attorneys with an address in the county)
  total: Everyone the source counts in the group, any status
  year: Year of the source's as-of date
  status: P primary source, S secondary source
  effectiveFrom: As-of date as a day
  effectiveTo: As-of date as a day
  asOf: The source's as-of date: a day, a month or a year (California's page shows none, so it is the day it was read)
  basis: What the source counts, in a sentence
  lastChecked: Day the source was read
  sourceLabels: Source names
  sourceUrls: Source URLs
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  county: 5-digit county FIPS code (vintage 2025); empty for other levels (in attorneys-values.csv, as id, column and value rows)
  active: Active attorneys or members in the group (Washington: only on the state and King County records) (in attorneys-values.csv, as id, column and value rows)
  inactive: Inactive attorneys or members (Ohio: published where no small count can be worked out from it) (in attorneys-values.csv, as id, column and value rows)
  retired: Retired, senior, emeritus or permanently retired (Ohio: published where no small count can be worked out from it) (in attorneys-values.csv, as id, column and value rows)
  deceased: Ohio: deceased registrations (published from 5 up, where no smaller count can be worked out) (in attorneys-values.csv, as id, column and value rows)
  discipline_related: Ohio: suspended, disbarred, revoked or resigned with discipline pending (published from 5 up, where no smaller count can be worked out) (in attorneys-values.csv, as id, column and value rows)
  other_status: Other statuses (Ohio: corporate, resigned, pending admission and others, published from 5 up, where no smaller count can be worked out; Idaho: emeritus and house counsel; Washington: the other license types; Pennsylvania: in-house counsel) (in attorneys-values.csv, as id, column and value rows)
  active_in_state_county: Ohio state record: active attorneys with an address in an Ohio county (in attorneys-values.csv, as id, column and value rows)
  active_outside_state: Ohio state record: active attorneys with an address elsewhere (in attorneys-values.csv, as id, column and value rows)
  active_no_county: Ohio state record: active attorneys with no county on file (in attorneys-values.csv, as id, column and value rows)
  population: Residents, Census estimate of July 1, 2025 (in attorneys-values.csv, as id, column and value rows)
  note: Caveat for the record, if any (in attorneys-values.csv, as id, column and value rows)
  admitted_pre1970: Ohio: active attorneys admitted before 1970 (published from 5 up, where no smaller count can be worked out); the other admitted_ columns are the decades 1970s to 2020s (in attorneys-values.csv, as id, column and value rows)
  admitted_1970s:  (in attorneys-values.csv, as id, column and value rows)
  admitted_1980s:  (in attorneys-values.csv, as id, column and value rows)
  admitted_1990s:  (in attorneys-values.csv, as id, column and value rows)
  admitted_2000s:  (in attorneys-values.csv, as id, column and value rows)
  admitted_2010s:  (in attorneys-values.csv, as id, column and value rows)
  admitted_2020s:  (in attorneys-values.csv, as id, column and value rows)
  median_admission_year: Ohio: median admission year of the active attorneys (given from 20 active attorneys up) (in attorneys-values.csv, as id, column and value rows)
  private_practice: Ohio and Michigan: active attorneys in private practice (Ohio: published from 5 up, where no smaller count can be worked out) (in attorneys-values.csv, as id, column and value rows)
  spanish_speaking: Ohio: active attorneys who list Spanish (published from 5 up, where no smaller count can be worked out) (in attorneys-values.csv, as id, column and value rows)
  active_per_10k: Active attorneys per 10,000 residents, one decimal (in attorneys-values.csv, as id, column and value rows)
  judge: Judges or judicial members (in attorneys-values.csv, as id, column and value rows)
  not_eligible: California: licensees not eligible to practice (in attorneys-values.csv, as id, column and value rows)
  barDistrict: California: State Bar district of the county; Idaho: judicial district number (in attorneys-values.csv, as id, column and value rows)
  other_practice: Michigan: active members not in private practice (in attorneys-values.csv, as id, column and value rows)
  prior_value: Michigan: the 2024 count (in attorneys-values.csv, as id, column and value rows)
  change: Michigan: change from 2024 (in attorneys-values.csv, as id, column and value rows)
  districtCounties: Idaho district records: the counties in the district (in attorneys-values.csv, as id, column and value rows)
  per_10k: Washington county records: WSBA licensees of every type per 10,000 residents (in attorneys-values.csv, as id, column and value rows)
