Law offices, jobs and pay by county, with solo-practice counts: BLS QCEW, Census CBP and Nonemployer Statistics

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23963687

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Law offices, jobs and pay by county, with solo-practice counts: BLS QCEW, Census CBP and Nonemployer Statistics, version 2.0.0, https://doi.org/10.5281/zenodo.23963687, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Law offices, jobs and pay by county, with solo-practice counts: BLS QCEW, Census CBP and Nonemployer Statistics (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23963687

Cite as: Probative Growth, Law offices, jobs and pay by county, with solo-practice counts: BLS QCEW, Census CBP and Nonemployer Statistics, 2026, https://doi.org/10.5281/zenodo.23963687

Not legal advice. These are counts of business establishments from government statistics, kept for marketing planning. An office of lawyers includes support staff, and the figures are revised by the agencies; check the agency's current release.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/law-firm-competition-by-county/

Columns:
  id: Stable record id (never reused)
  area: County FIPS code (5 digits), state FIPS code (2 digits) or US
  areaName: County, state or nation name; counties end with the state abbreviation
  areaType: county, state or us
  state: Two-letter state code
  period: The quarter of the BLS figures, e.g. 2026-Q1
  qcew_estabs: BLS QCEW private establishments in NAICS 541110 (offices of lawyers) in the quarter
  cbp_offices: Census County Business Patterns 2023 employer offices of lawyers, exactly as first published
  cbp_employees: CBP 2023 employment (the Census adds noise to protect confidentiality)
  population: Census population estimate for July 1, 2025
  estabs_per_10k: qcew_estabs per 10,000 residents
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: The machine value (see unit)
  unit: Unit of value
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  cbsa_type: Counties only: metro, micro (OMB 2023 core-based areas) or rural (outside any) (in law-offices-values.csv, as id, column and value rows)
  qcew_employment: BLS QCEW employment in the quarter's third month, as BLS publishes it for the area (in law-offices-values.csv, as id, column and value rows)
  qcew_avg_weekly_wage: BLS QCEW average weekly wage in dollars, as BLS publishes it for the area (in law-offices-values.csv, as id, column and value rows)
  qcew_estabs_yoy_pct: Percent change in establishments from the same quarter a year earlier, as BLS prints it (in law-offices-values.csv, as id, column and value rows)
  cbp_employees_noise: G = changed by under 2 percent, H = 2 to under 5 percent, J = 5 percent or more (in law-offices-values.csv, as id, column and value rows)
  cbp_payroll_thousands: CBP 2023 annual payroll in thousands of dollars (noise-infused) (in law-offices-values.csv, as id, column and value rows)
  nes_firms: Census Nonemployer Statistics 2024 firms with no employees in legal services (NAICS 5411, the finest county level published), as published (in law-offices-values.csv, as id, column and value rows)
  nes_receipts_thousands: Nonemployer receipts in thousands of dollars (noise-infused) (in law-offices-values.csv, as id, column and value rows)
  solos_per_10k: nes_firms per 10,000 residents (in law-offices-values.csv, as id, column and value rows)
  employees_per_10k: qcew_employment per 10,000 residents (in law-offices-values.csv, as id, column and value rows)
  solos_per_office: nes_firms divided by qcew_estabs, for areas with at least one establishment (in law-offices-values.csv, as id, column and value rows)
