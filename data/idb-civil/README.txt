How long federal civil cases take: outcomes, class actions and pro se share by district, nature of suit and year

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23739969

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, How long federal civil cases take: outcomes, class actions and pro se share by district, nature of suit and year, version 1.0.0, https://doi.org/10.5281/zenodo.23739969, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). How long federal civil cases take: outcomes, class actions and pro se share by district, nature of suit and year (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23739969

Not legal advice. These are counts, medians and shares from the Federal Judicial Center's court records, kept for marketing planning. A court's typical time to disposition says nothing about how any one case will go.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/how-long-federal-civil-cases-take/

Columns:
  id: Stable record id (never reused)
  district: The federal district court key (NYS, CAC, ...), or US for all district courts together
  districtName: 
  circuit: 
  group: Our nature-of-suit group (personal-injury, employment, ...) or all
  groupLabel: 
  kind: district-group (a district and a group) or nos (the whole US for one nature-of-suit code)
  nos: The nature-of-suit code on the civil cover sheet (nos records only)
  nosLabel: 
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  value: Median days from filing to disposition, over cases the district itself resolved in the window; empty when fewer than 10
  unit: Unit of value
  window: The fiscal years pooled in the record (three years, October to September)
  filed: Cases filed in the window
  terminated: Cases terminated in the window
  resolved: Terminated cases minus transfers out, remands, MDL transfers and statistical closings
  classActions: Filed cases flagged as alleging a class action (Rule 23)
  classPct: Class-action share of filed cases, percent; empty when fewer than 10
  proSePlaintiffPct: Share of filed cases with a pro se plaintiff, percent; empty when fewer than 10
  trials: Resolved cases that ended in a jury verdict, directed verdict or court trial
  trialPct: Trials as a percent of resolved cases; empty when fewer than 10
  medianDaysToTrial: Median days from filing to the start of trial, for jury and court trials with a recorded start date; empty when fewer than 10
  trialsWithDate: Trials with a usable start date
  medianDaysToTrialAllYears: The same median over all ten fiscal years
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
