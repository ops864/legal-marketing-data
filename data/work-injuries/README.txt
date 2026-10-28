Workplace injuries and fatal work injuries by state and industry (BLS SOII and CFOI)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23740010

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Workplace injuries and fatal work injuries by state and industry (BLS SOII and CFOI), version 1.0.0, https://doi.org/10.5281/zenodo.23740010, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Workplace injuries and fatal work injuries by state and industry (BLS SOII and CFOI) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23740010

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
  event: Cause of the fatal injury (cfoi-event records)
  year: The reference year
  status: P published by BLS; U suppressed (BLS did not publish it)
  value: The headline number of the record (see unit); empty when suppressed
  unit: What value counts
  rate: Injury and illness cases per 100 full-time workers (soii-industry) or fatal injuries per 100,000 full-time equivalent workers (cfoi records)
  dartRate: Cases with days away from work, job restriction or transfer, per 100 full-time workers
  casesThousands: Estimated recordable cases, in thousands (BLS rounds to 100)
  rse: Relative standard error of the rate, in percent; 20 or more is flagged as noisy
  count2023: The previous year's count (cfoi-total and cfoi-event records)
  text: The record in one plain-English sentence
  note: Caveats
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
