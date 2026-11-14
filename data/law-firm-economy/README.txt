Law firm size, solos and receipts, by state: Census SUSB 2022, Nonemployer Statistics 2024 and Economic Census 2022

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23898123

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Law firm size, solos and receipts, by state: Census SUSB 2022, Nonemployer Statistics 2024 and Economic Census 2022, version 2.0.0, https://doi.org/10.5281/zenodo.23898123, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Law firm size, solos and receipts, by state: Census SUSB 2022, Nonemployer Statistics 2024 and Economic Census 2022 (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23898123

Cite as: Probative Growth, Law firm size, solos and receipts, by state: Census SUSB 2022, Nonemployer Statistics 2024 and Economic Census 2022, 2026, https://doi.org/10.5281/zenodo.23898123

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
  status: P primary source, S secondary source
  value: Firms in the class (businesses for nonemployer); for ec-top records, the share of all law-firm receipts in percent
  unit: Unit of value
  firms: Employer law firms (SUSB, EC) or nonemployer businesses (NES). A firm is counted once in each state where it has an office
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  establishments: Offices (establishments) of those firms (in law-firm-economy-values.csv, as id, column and value rows)
  employees: Paid employees in March (SUSB) or at the pay period including March 12 (EC); 0 for nonemployers (in law-firm-economy-values.csv, as id, column and value rows)
  payrollUsd: Annual payroll in whole dollars (the tables print $1,000) (in law-firm-economy-values.csv, as id, column and value rows)
  receiptsUsd: Receipts (revenue) in whole dollars (the tables print $1,000) (in law-firm-economy-values.csv, as id, column and value rows)
  shareOfFirms: The class's firms divided by all employer firms in the same jurisdiction (US records: of the US total) (in law-firm-economy-values.csv, as id, column and value rows)
  shareOfReceipts: The class's receipts divided by all receipts in the same jurisdiction (in law-firm-economy-values.csv, as id, column and value rows)
  receiptsPerFirmUsd: Receipts divided by firms, in whole dollars (in law-firm-economy-values.csv, as id, column and value rows)
  employeesPerFirm: Employees divided by firms, one decimal (in law-firm-economy-values.csv, as id, column and value rows)
