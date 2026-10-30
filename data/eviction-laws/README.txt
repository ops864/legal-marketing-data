Eviction laws by state and territory: notice, cure, just cause, fees and timing (LSC)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23792754

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Eviction laws by state and territory: notice, cure, just cause, fees and timing (LSC), version 1.0.0, https://doi.org/10.5281/zenodo.23792754, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Eviction laws by state and territory: notice, cure, just cause, fees and timing (LSC) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23792754

Not legal advice. This is a research coding of the laws in effect on January 1, 2021, made by the Legal Services Corporation and Temple University from statutes, regulations and court rules. Laws change and local rules can differ; confirm the current rule in the official code before relying on it. Prepared for research and marketing planning.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/eviction-laws/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code, or US for the national summary
  stateName: 
  level: state, or us for the national summary
  status: S: a compilation of the law made by LSC and Temple University, not the statute text
  text: The record in one plain-English sentence
  value: Days of notice before an eviction filing for nonpayment (the shortest period where the law gives more than one); on the national record, the number of jurisdictions
  unit: Unit of value
  noticeNonpayment: The notice rule for nonpayment of rent, in words
  noticeNonpaymentDays: Shortest notice period in days
  noticeOtherCauses: True when the law also requires notice for reasons other than nonpayment
  cureNonpayment: True when a tenant may cure a nonpayment default
  cureCauses: The defaults a tenant may cure
  justCause: True when the law requires a landlord to have a stated cause to evict
  lateFeeRegulated: True when the law regulates late fees
  lateFeeCap: The cap, in the law's own terms
  filingFeeUsd: Eviction filing fee in dollars where the state law sets one
  summonsDays: Shortest time in days the law gives a tenant between summons and hearing
  appealDays: Days after judgment to appeal (shortest where more than one)
  writWaitDays: Days between issuing the writ and carrying it out (0 = at once)
  mediation: Whether the law has a mediation rule
  rightToCounsel: True when the law gives tenants a right to free counsel
  courts: Courts that first hear eviction cases
  service: How the summons is served
  citation: The statute the notice rule comes from
  effectiveDate: Date the coded law took effect
  validThrough: Last date the coded law is known to be in force (January 1, 2021)
  jurisdictions: 
  justCauseCount: 
  cureNonpaymentCount: 
  lateFeeRegulatedCount: 
  noNoticeNonpaymentCount: 
  mediationCount: 
  rightToCounselCount: 
  notice3DaysCount: 
  notice14PlusCount: 
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
