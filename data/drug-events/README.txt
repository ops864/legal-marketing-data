Serious drug adverse event reports by active ingredient (openFDA FAERS)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23752994

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Serious drug adverse event reports by active ingredient (openFDA FAERS), version 1.0.0, https://doi.org/10.5281/zenodo.23752994, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Serious drug adverse event reports by active ingredient (openFDA FAERS) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23752994

Not legal advice. This is not medical advice either. A report in the FDA Adverse Event Reporting System is not proof that a drug caused an event; reports come from patients, clinicians and manufacturers, can be duplicated and are not verified. Questions about a medicine are for a health professional, and questions about an injury are for a licensed attorney.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/drug-events/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or territory, or US
  ingredient: Active ingredient as openFDA names it (patient.drug.openfda.substance_name), or 'All drugs'
  level: us (all drugs together) or ingredient
  rank: Rank by reports in the window among the published ingredients (0 for the all-drug record)
  quarters: The eight calendar quarters of the window, oldest first, comma separated
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Same as reports: FAERS reports received in the window that list the ingredient
  unit: What the value counts
  reports: Reports received in the window that list the ingredient (all drugs: all reports)
  serious: Of those, reports openFDA marks serious
  deaths: Of those, reports with a death outcome (seriousnessdeath)
  serious_pct: serious as a percent of reports
  death_pct: deaths as a percent of reports
  reports_q1: Reports received in quarter 1 of the window (quarter 1 = the 1st quarter listed in `quarters`, oldest first)
  reports_q2: Reports received in quarter 2 of the window (quarter 2 = the 2nd quarter listed in `quarters`, oldest first)
  reports_q3: Reports received in quarter 3 of the window (quarter 3 = the 3rd quarter listed in `quarters`, oldest first)
  reports_q4: Reports received in quarter 4 of the window (quarter 4 = the 4th quarter listed in `quarters`, oldest first)
  reports_q5: Reports received in quarter 5 of the window (quarter 5 = the 5th quarter listed in `quarters`, oldest first)
  reports_q6: Reports received in quarter 6 of the window (quarter 6 = the 6th quarter listed in `quarters`, oldest first)
  reports_q7: Reports received in quarter 7 of the window (quarter 7 = the 7th quarter listed in `quarters`, oldest first)
  reports_q8: Reports received in quarter 8 of the window (quarter 8 = the 8th quarter listed in `quarters`, oldest first)
  serious_q1: Serious reports received in quarter 1 of the window
  serious_q2: Serious reports received in quarter 2 of the window
  serious_q3: Serious reports received in quarter 3 of the window
  serious_q4: Serious reports received in quarter 4 of the window
  serious_q5: Serious reports received in quarter 5 of the window
  serious_q6: Serious reports received in quarter 6 of the window
  serious_q7: Serious reports received in quarter 7 of the window
  serious_q8: Serious reports received in quarter 8 of the window
  topReactions: The five most reported reactions (MedDRA preferred terms) among the window's reports for the ingredient, with counts
  mdl: Open multidistrict litigation dockets (from the mdl dataset) that name the ingredient
  effectiveFrom: First day of the window
  effectiveTo: Last day of the window
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
