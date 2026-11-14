TCPA and ADA federal lawsuits filed, by district and fiscal year

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24187571

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, TCPA and ADA federal lawsuits filed, by district and fiscal year, version 1.0.0, https://doi.org/10.5281/zenodo.24187571, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). TCPA and ADA federal lawsuits filed, by district and fiscal year (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24187571

Cite as: Probative Growth, TCPA and ADA federal lawsuits filed, by district and fiscal year, 2026, https://doi.org/10.5281/zenodo.24187571

Not legal advice. These are counts of federal civil cases filed, taken from court records and kept for research and marketing planning. A case filed is not a finding that any law was broken, and a count says nothing about how any one case ended.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/tcpa-ada-filings/

Columns:
  id: Stable record id (never reused)
  district: The federal district court's key (for example CAC, NYS)
  districtName: The district court's name
  circuit: The federal circuit the district belongs to
  natureOfSuit: The civil cover sheet's nature-of-suit code: 485 (Telephone Consumer Protection Act) or 446 (Americans with Disabilities Act, other)
  natureOfSuitName: The code's name
  code: tcpa or ada-other
  fiscalYear: The federal fiscal year the cases were filed in (fiscal year N runs October 1 of N-1 to September 30 of N, by filing date)
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: Cases filed in the district and fiscal year under the code, multidistrict litigation cases included
  unit: Unit of value
  filed: Of them, the cases outside a multidistrict litigation
  filedInMdl: Of them, the cases that carry a multidistrict litigation docket number
  total: Cases filed in the district and fiscal year under the code (filed plus filedInMdl)
  allCivilFiled: Every civil case filed in the district that fiscal year
  pctOfAllCivil: The code's cases as a percent of every civil case filed in the district that fiscal year
  effectiveFrom: First day of the fiscal year
  effectiveTo: Last day of the fiscal year
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  note: On the fiscal years in which courts were starting to use code 485: the count is lower than the cases filed (in tcpa-ada-filings-values.csv, as id, column and value rows)
