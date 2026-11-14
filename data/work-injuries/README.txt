Workplace injuries and fatal work injuries by state and industry (BLS SOII and CFOI)

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23898154

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Workplace injuries and fatal work injuries by state and industry (BLS SOII and CFOI), version 2.0.0, https://doi.org/10.5281/zenodo.23898154, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Workplace injuries and fatal work injuries by state and industry (BLS SOII and CFOI) (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23898154

Cite as: Probative Growth, Workplace injuries and fatal work injuries by state and industry (BLS SOII and CFOI), 2026, https://doi.org/10.5281/zenodo.23898154

Not legal advice. These are survey and census statistics from the Bureau of Labor Statistics, kept for planning. A rate describes a whole industry in a state, not any one employer, and it does not say whether anyone has a workers' compensation claim.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/work-injuries/

Columns:
  id: Stable record id (never reused)
  state: US or a two-letter state code (DC included)
  areaName: Area name
  kind: soii-industry (nonfatal rate), cfoi-total (fatal injuries in the state), cfoi-industry (fatal rate in an industry) or cfoi-event (fatal injuries by cause)
  measure: nonfatal or fatal
  level: all, supersector, sector (2-digit NAICS), subsector (3-digit NAICS) or event
  naics: NAICS code (2 or 3 digits), a range such as 31-33, or ALL
  industry: Industry name, as BLS words it
  year: The reference year
  status: P: published by BLS
  value: The headline number of the record (see unit)
  unit: What value counts
  text: The record in one plain-English sentence
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  event: Cause of the fatal injury (cfoi-event records) (in work-injuries-values.csv, as id, column and value rows)
  rate: Injury and illness cases per 100 full-time workers (soii-industry) or fatal injuries per 100,000 full-time equivalent workers (cfoi records) (in work-injuries-values.csv, as id, column and value rows)
  dartRate: Cases with days away from work, job restriction or transfer, per 100 full-time workers (in work-injuries-values.csv, as id, column and value rows)
  casesThousands: Estimated recordable cases, in thousands (BLS rounds to 100) (in work-injuries-values.csv, as id, column and value rows)
  rse: Relative standard error of the rate, in percent; 20 or more is flagged as noisy (in work-injuries-values.csv, as id, column and value rows)
  count2023: The previous year's count (cfoi-total and cfoi-event records) (in work-injuries-values.csv, as id, column and value rows)
  detail: A short sourced detail on the record (in work-injuries-values.csv, as id, column and value rows)
