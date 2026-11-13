The new-lawyer pipeline by jurisdiction: bar exam pass rates and new admissions, 2025

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23962982

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, The new-lawyer pipeline by jurisdiction: bar exam pass rates and new admissions, 2025, version 2.0.0, https://doi.org/10.5281/zenodo.23962982, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). The new-lawyer pipeline by jurisdiction: bar exam pass rates and new admissions, 2025 (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23962982

Not legal advice. This is a plain-English summary of public sources, kept for marketing and recruiting planning. The figures are derived from the National Conference of Bar Examiners' published statistics and credited to NCBE; for the original tables, go to NCBE.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/bar-pipeline/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code, DC, US (federal), ABA, or PLATFORM:<name>
  jurisdictionName: Jurisdiction name
  status: P primary source, S secondary source
  year: The year the figures are for
  pass_rate_pct: Overall bar exam pass rate for the year (February and July together), in percent: passers divided by takers, as we compute it from NCBE's table. Empty when NCBE shows no results for the jurisdiction.
  admitted: New lawyers admitted in the year: the sum of the pathways NCBE shows (by examination, by transferred UBE score, on motion). Where NCBE shows a dash for a pathway it is left out and named in admitted_pathways_reported.
  admitted_pathways_reported: Which admission pathways are in the admitted figure
  text: The record in one plain-English sentence
  unit: What the value measures
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: The NCBE tables the figures are derived from
  sourceUrls: Links to those tables
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  admitted_change_2021_2025_pct: Change in admissions by exam or by transferred UBE score between 2021 and 2025, in percent. Like for like: it compares exam and transferred-score admissions. (in bar-pipeline-values.csv, as id, column and value rows)
  transfer_share_pct: Share of the admitted figure that came by transferred UBE score, in percent (in bar-pipeline-values.csv, as id, column and value rows)
  motion_share_pct: Share of the admitted figure that came on motion (from another jurisdiction's license), in percent (in bar-pipeline-values.csv, as id, column and value rows)
  note: Caveats (in bar-pipeline-values.csv, as id, column and value rows)
