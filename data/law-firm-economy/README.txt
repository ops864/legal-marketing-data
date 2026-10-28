Law firm size, solos and receipts, by state: Census SUSB 2022, Nonemployer Statistics 2024 and Economic Census 2022

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23739997

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Law firm size, solos and receipts, by state: Census SUSB 2022, Nonemployer Statistics 2024 and Economic Census 2022, version 1.0.0, https://doi.org/10.5281/zenodo.23739997, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Law firm size, solos and receipts, by state: Census SUSB 2022, Nonemployer Statistics 2024 and Economic Census 2022 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23739997

Not legal advice. These are Census Bureau business statistics, kept for marketing planning. Counts are for 2022 (employer firms and the Economic Census) and 2024 (businesses with no employees); small differences come from the Census Bureau's disclosure noise.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/law-firm-size-and-revenue/

Columns:
  id: Stable record id (never reused)
  jurisdiction: US, a two-letter state code or DC
  jurisdictionName: Jurisdiction name
  sizeClass: all, lt5, 5-9, 10-19, 20-99, 100-499 or 500+ (employees in the firm, SUSB); nonemployer (no employees, NES); econ-census (Economic Census 2022); and, for the US only, nes-<receipts band>, ec-top4/8/20/50 and ec-rcpt-<receipts band>
  sizeLabel: The class in plain words
  survey: SUSB (Statistics of U.S. Businesses 2022), NES (Nonemployer Statistics 2024) or EC (Economic Census 2022)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  value: Firms in the class (businesses for nonemployer); for ec-top records, the share of all law-firm receipts in percent. Empty where the Census Bureau published no figure (flags.suppressed)
  unit: Unit of value
  firms: Employer law firms (SUSB, EC) or nonemployer businesses (NES). A firm is counted once in each state where it has an office
  establishments: Offices (establishments) of those firms
  employees: Paid employees in March (SUSB) or at the pay period including March 12 (EC); 0 for nonemployers
  payrollUsd: Annual payroll in whole dollars (the tables print $1,000)
  receiptsUsd: Receipts (revenue) in whole dollars (the tables print $1,000)
  shareOfFirms: The class's firms divided by all employer firms in the same jurisdiction (US records: of the US total)
  shareOfReceipts: The class's receipts divided by all receipts in the same jurisdiction
  receiptsPerFirmUsd: Receipts divided by firms, in whole dollars
  employeesPerFirm: Employees divided by firms, one decimal
  withheld: Economic Census records: the figures the Census Bureau withheld (printed as 0 in its table) and left empty here: firms, employees, payrollUsd, receiptsUsd
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
