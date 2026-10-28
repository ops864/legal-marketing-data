California court filings by county: civil, criminal, family, juvenile, probate and appeals, fiscal years 2023–24 and 2024–25

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23658524

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, California court filings by county: civil, criminal, family, juvenile, probate and appeals, fiscal years 2023–24 and 2024–25, version 1.0.0, https://doi.org/10.5281/zenodo.23658524, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). California court filings by county: civil, criminal, family, juvenile, probate and appeals, fiscal years 2023–24 and 2024–25 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23658524

Not legal advice. These are counts from the Judicial Council of California's published statistics, kept for marketing planning. A filing is a new case opened in the court, not a person or a client. Check the Judicial Council's current report.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/ca-courts/

Columns:
  id: Stable record id (never reused)
  county: County key (a lowercase slug), or CA for the state
  countyName: County name
  areaType: us, state or cbsa
  group: The Council’s case group: civil, criminal, family, juvenile, probate, mental health or appeals
  table: The report table the figure comes from
  column: The column letter in that table
  measure: What the estimate measures
  measureLabel: The case type, as the report names it
  fy: The state fiscal year (e.g. 2024-25)
  value: The machine value (see unit)
  unit: Unit of value
  priorFy: The fiscal year before it
  priorValue: The prior-year count
  change: This year’s count minus the prior year’s
  changePct: The change as a percent of the prior year; empty when the prior count is zero or missing
  incomplete: true when the Council flags the cell as incomplete data
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
