Employment discrimination charges to the EEOC, by state and basis, FY 2009 to FY 2025

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23733005

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Employment discrimination charges to the EEOC, by state and basis, FY 2009 to FY 2025, version 1.0.0, https://doi.org/10.5281/zenodo.23733005, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Employment discrimination charges to the EEOC, by state and basis, FY 2009 to FY 2025 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23733005

Not legal advice. These are counts of charges received by the EEOC, kept for marketing planning. A charge is an allegation, not a finding of discrimination, and the counts leave out charges filed only with state and local agencies. Deadlines and rights are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/eeoc-charges/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code, DC, US (federal), ABA, or PLATFORM:<name>
  jurisdictionName: Jurisdiction name
  basis: all, race, sex, national-origin, religion, color, retaliation (all statutes), retaliation-title-vii, age, disability, equal-pay, genetic-information or pregnancy-pwfa
  basisLabel: The basis in plain words
  fy: The EEOC fiscal year (October 1 to September 30)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  value: Charges received; empty when the EEOC suppressed the cell (flags.suppressed)
  unit: Unit of value
  shareOfStateTotal: Charges for the basis divided by the jurisdiction's total charges that year (a charge can name several bases)
  per100kWorkers: Charges per 100,000 private-sector workers (BLS QCEW annual average employment, the calendar year the fiscal year ends in); empty before fiscal year 2014 and where QCEW has no figure
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
