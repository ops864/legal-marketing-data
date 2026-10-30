IRS Data Book by state: returns filed, gross tax collections and refunds, fiscal years 2019 to 2025

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23792826

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, IRS Data Book by state: returns filed, gross tax collections and refunds, fiscal years 2019 to 2025, version 1.0.0, https://doi.org/10.5281/zenodo.23792826, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). IRS Data Book by state: returns filed, gross tax collections and refunds, fiscal years 2019 to 2025 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23792826

Not legal advice. These are the IRS's own counts of returns, collections and refunds by the state of the filer's address; they describe IRS workload and tax flows, not any person's tax position. A state's collections depend on where taxpayers (including multi-state companies) are located, not only on where income was earned. Tax questions are for a qualified professional.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/irs-databook/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code (50 states, DC, PR), or US
  level: state or us
  stateName: 
  fiscalYear: IRS fiscal year, October of the prior year to September (2025 = October 2024 to September 2025)
  status: P: IRS's own published figure
  text: The record in one plain-English sentence
  value: Gross tax collections in dollars (the same as collections_total)
  unit: Unit of value
  returns_total: Returns and other forms filed (excludes information returns)
  returns_individual: Individual income tax returns (Form 1040 series)
  returns_employment: Employment tax returns
  returns_c_corp: C or other corporation income tax returns
  returns_s_corp: S corporation returns
  returns_partnership: Partnership returns
  collections_total: Gross collections in dollars, including penalties and interest
  collections_business: Business income taxes
  collections_individual_employment: Individual income, employment and estate and trust income taxes
  collections_withheld: Individual income tax withheld, including Social Security and Medicare
  collections_individual_payments: Individual income tax payments
  collections_estate: Estate tax
  collections_gift: Gift tax
  collections_excise: Excise taxes
  refunds_number_total: Number of refunds issued
  refunds_number_individual: Number of individual income tax refunds
  refunds_amount_total: Amount of refunds issued, in dollars, including interest
  refunds_amount_individual: Individual income tax refunds, in dollars
  collections_outside_states: US record: collections IRS counts in the nation but assigns to no state (armed forces overseas, international, undistributed, other areas)
  returns_outside_states: US record: returns assigned to no state
  refunds_number_outside_states: US record: refunds assigned to no state
  refunds_amount_outside_states: US record: refund dollars assigned to no state
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
