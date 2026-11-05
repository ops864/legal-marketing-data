Eviction laws by state and territory: notice, cure, just cause, fees and timing (LSC)

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23963453

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Eviction laws by state and territory: notice, cure, just cause, fees and timing (LSC), version 2.0.0, https://doi.org/10.5281/zenodo.23963453, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Eviction laws by state and territory: notice, cure, just cause, fees and timing (LSC) (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23963453

Not legal advice. The file is a research coding of the laws in effect on January 1, 2021, made by the Legal Services Corporation and Temple University from statutes, regulations and court rules. Laws change and local rules can differ; confirm the current rule in the official code before relying on it. Prepared for research and marketing planning.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/eviction-laws/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code, or US for the national summary
  level: state, or us for the national summary
  status: S: a compilation of the law made by LSC and Temple University, not the statute text
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  stateName:  (in eviction-laws-values.csv, as id, column and value rows)
  value: Days of notice before an eviction filing for nonpayment (the shortest period where the law gives more than one); on the national record, the number of jurisdictions (in eviction-laws-values.csv, as id, column and value rows)
  unit: Unit of value (in eviction-laws-values.csv, as id, column and value rows)
  noticeNonpayment: The notice rule for nonpayment of rent, in words (in eviction-laws-values.csv, as id, column and value rows)
  noticeNonpaymentDays: Shortest notice period in days (in eviction-laws-values.csv, as id, column and value rows)
  noticeOtherCauses: True when the law also requires notice for reasons other than nonpayment (in eviction-laws-values.csv, as id, column and value rows)
  cureNonpayment: True when a tenant may cure a nonpayment default (in eviction-laws-values.csv, as id, column and value rows)
  cureCauses: The defaults a tenant may cure (in eviction-laws-values.csv, as id, column and value rows)
  justCause: True when the law requires a landlord to have a stated cause to evict (in eviction-laws-values.csv, as id, column and value rows)
  lateFeeRegulated: True when the law regulates late fees (in eviction-laws-values.csv, as id, column and value rows)
  lateFeeCap: The cap, in the law's own terms (in eviction-laws-values.csv, as id, column and value rows)
  filingFeeUsd: Eviction filing fee in dollars where the state law sets one (in eviction-laws-values.csv, as id, column and value rows)
  summonsDays: Shortest time in days the law gives a tenant between summons and hearing (in eviction-laws-values.csv, as id, column and value rows)
  appealDays: Days after judgment to appeal (shortest where more than one) (in eviction-laws-values.csv, as id, column and value rows)
  writWaitDays: Days between issuing the writ and carrying it out (0 = at once) (in eviction-laws-values.csv, as id, column and value rows)
  mediation: Whether the law has a mediation rule (in eviction-laws-values.csv, as id, column and value rows)
  rightToCounsel: True when the law gives tenants a right to free counsel (in eviction-laws-values.csv, as id, column and value rows)
  courts: Courts that first hear eviction cases (in eviction-laws-values.csv, as id, column and value rows)
  service: How the summons is served (in eviction-laws-values.csv, as id, column and value rows)
  citation: The statute the notice rule comes from (in eviction-laws-values.csv, as id, column and value rows)
  effectiveDate: Date the coded law took effect (in eviction-laws-values.csv, as id, column and value rows)
  validThrough: Last date the coded law is known to be in force (January 1, 2021) (in eviction-laws-values.csv, as id, column and value rows)
  jurisdictions:  (in eviction-laws-values.csv, as id, column and value rows)
  justCauseCount:  (in eviction-laws-values.csv, as id, column and value rows)
  cureNonpaymentCount:  (in eviction-laws-values.csv, as id, column and value rows)
  lateFeeRegulatedCount:  (in eviction-laws-values.csv, as id, column and value rows)
  noNoticeNonpaymentCount:  (in eviction-laws-values.csv, as id, column and value rows)
  mediationCount:  (in eviction-laws-values.csv, as id, column and value rows)
  rightToCounselCount:  (in eviction-laws-values.csv, as id, column and value rows)
  notice3DaysCount:  (in eviction-laws-values.csv, as id, column and value rows)
  notice14PlusCount:  (in eviction-laws-values.csv, as id, column and value rows)
