Nursing home fines and harm citations by county: CMS penalties, actual-harm, immediate-jeopardy and abuse citations

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23741901

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Nursing home fines and harm citations by county: CMS penalties, actual-harm, immediate-jeopardy and abuse citations, version 1.0.0, https://doi.org/10.5281/zenodo.23741901, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Nursing home fines and harm citations by county: CMS penalties, actual-harm, immediate-jeopardy and abuse citations (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23741901

Not legal advice. This is a count of public CMS inspection and penalty records, kept for marketing planning. A citation is an inspector's finding, not a court's; a fine can be reduced or withdrawn on appeal; and nothing here says any home or person did anything unlawful.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/nursing-homes/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code, or US for the national record
  jurisdictionName: State or territory name
  level: county, state or us
  county: 5-digit county FIPS code (vintage 2025; Connecticut planning regions), empty for state and US records
  countyName: County name as in the crosswalks dataset
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Same as fines_total_usd
  unit: What value measures
  facilities: Medicare- or Medicaid-certified nursing homes in the CMS Provider Information file
  certified_beds: Certified beds in those homes
  rated_facilities: Homes with a CMS overall star rating
  one_star_facilities: Homes rated one star overall (the lowest)
  one_star_share_pct: one_star_facilities as a percent of rated_facilities
  abuse_icon_facilities: Homes CMS marks with its abuse icon on Care Compare
  fines_count: Fines (civil money penalties) CMS lists in the last three years
  fines_total_usd: Dollars of those fines, as CMS lists them (before any later reduction CMS has not yet posted)
  facilities_fined: Homes with at least one fine
  payment_denials: Denials of payment for new admissions in the last three years
  payment_denial_days: Total length of those payment denials, in days
  citations_total: Health citations (deficiencies) in the inspections CMS publishes for each home
  citations_harm: Citations at scope and severity G to L: actual harm or immediate jeopardy
  citations_ij: Citations at scope and severity J to L: immediate jeopardy to resident health or safety
  citations_abuse: Citations under federal tags F600 to F610 (abuse, neglect, exploitation, misappropriation and how homes prevent, report and investigate them)
  facilities_with_harm: Homes with at least one citation at G to L
  facilities_with_ij: Homes with at least one citation at J to L
  facilities_without_county: State and US records: homes whose county could not be placed (Puerto Rico and Guam have no county rows), counted in the state only
  cms_avg_fines_per_facility: State and US records: CMS's own published average number of fines per home (second source)
  cms_avg_fine_amount_usd: State and US records: CMS's own published average fine dollars per home (second source)
  cms_avg_cycle1_health_deficiencies: State and US records: CMS's own published average health deficiencies in the latest standard inspection (second source)
  penalty_from: Earliest penalty date in the CMS Penalties file
  penalty_to: Latest penalty date in the CMS Penalties file
  survey_from: Earliest inspection date in the CMS Health Deficiencies file
  survey_to: Latest inspection date in the CMS Health Deficiencies file
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: The CMS files the record is built from
  sourceUrls: Links to those files
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
