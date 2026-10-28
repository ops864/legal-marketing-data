Immigration court backlog, representation and asylum outcomes (EOIR workload statistics and case data)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23739986

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Immigration court backlog, representation and asylum outcomes (EOIR workload statistics and case data), version 1.0.0, https://doi.org/10.5281/zenodo.23739986, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Immigration court backlog, representation and asylum outcomes (EOIR workload statistics and case data) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23739986

Not legal advice. These are counts from the Executive Office for Immigration Review's published statistics and case data, kept for marketing planning. EOIR says its statistics are subject to change, a count is not a case outcome, and eligibility, deadlines and strategy are a matter for each person's own lawyer.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/immigration-courts/

Columns:
  id: Stable record id (never reused)
  jurisdiction: US for national series, or the two-letter code of the state: the respondent's state of address for state records, and the state where the court sits for court records
  jurisdictionName: Jurisdiction name
  scope: national, state, court or nationality
  measure: What is counted, in plain words
  period: The fiscal year (2025), the fiscal year to a quarter end (2026Q3, the fiscal year runs October 1 to September 30) or the date of the case-data file (2026-10-01)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  value: The count, or a percent for the representation rate and the grant share (see unit); empty when suppressed (flags.suppressed)
  unit: Unit of value
  perMonth: The average a month, for new cases and completions
  represented: Pending proceedings with a representative of record on the case-data file; empty when a cell is under 11
  representedPct: Represented divided by pending, percent, one decimal
  shareOfPending: This record's pending proceedings as a percent of all pending proceedings in the case-data file
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
