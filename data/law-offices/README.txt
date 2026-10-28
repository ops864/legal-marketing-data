Law offices, jobs and pay by county, with solo-practice counts: BLS QCEW, Census CBP and Nonemployer Statistics

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23721415

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Law offices, jobs and pay by county, with solo-practice counts: BLS QCEW, Census CBP and Nonemployer Statistics, version 1.0.0, https://doi.org/10.5281/zenodo.23721415, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Law offices, jobs and pay by county, with solo-practice counts: BLS QCEW, Census CBP and Nonemployer Statistics (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23721415

Not legal advice. These are counts of business establishments from government statistics, kept for marketing planning. An office of lawyers includes support staff, and the figures are revised by the agencies; check the agency's current release.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/law-firm-competition-by-county/

Columns:
  id: Stable record id (never reused)
  area: County FIPS code (5 digits), state FIPS code (2 digits) or US
  areaName: County, state or nation name; counties end with the state abbreviation
  areaType: county, state or us
  state: Two-letter state code
  cbsa_type: Counties only: metro, micro (OMB 2023 core-based areas) or rural (outside any)
  period: The quarter of the BLS figures, e.g. 2026-Q1
  qcew_estabs: BLS QCEW private establishments in NAICS 541110 (offices of lawyers) in the quarter
  qcew_employment: BLS QCEW employment in the quarter's third month; empty where BLS suppresses it (qcew_disclosure N)
  qcew_avg_weekly_wage: BLS QCEW average weekly wage in dollars; empty where suppressed
  qcew_disclosure: N = BLS suppresses employment and pay to protect confidentiality; none = no establishment reported; empty = published
  qcew_estabs_yoy_pct: Percent change in establishments from the same quarter a year earlier, as BLS prints it
  cbp_offices: Census County Business Patterns 2023 employer offices of lawyers, exactly as first published
  cbp_employees: CBP 2023 employment (the Census adds noise to protect confidentiality)
  cbp_employees_noise: G = changed by under 2 percent, H = 2 to under 5 percent, J = 5 percent or more
  cbp_payroll_thousands: CBP 2023 annual payroll in thousands of dollars (noise-infused)
  nes_firms: Census Nonemployer Statistics 2024 firms with no employees in legal services (NAICS 5411, the finest county level published); empty where withheld
  nes_receipts_thousands: Nonemployer receipts in thousands of dollars (noise-infused)
  population: Census population estimate for July 1, 2025
  estabs_per_10k: qcew_estabs per 10,000 residents
  solos_per_10k: nes_firms per 10,000 residents
  employees_per_10k: qcew_employment per 10,000 residents
  solos_per_office: nes_firms divided by qcew_estabs; empty when there are no establishments
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: The machine value (see unit)
  unit: Unit of value
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
