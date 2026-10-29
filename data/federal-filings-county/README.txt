Federal civil cases filed, by county of the plaintiff's residence, case type and year (Federal Judicial Center)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23750628

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Federal civil cases filed, by county of the plaintiff's residence, case type and year (Federal Judicial Center), version 1.0.0, https://doi.org/10.5281/zenodo.23750628, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Federal civil cases filed, by county of the plaintiff's residence, case type and year (Federal Judicial Center) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23750628

Not legal advice. These are counts of federal civil case filings from court records, kept for research and marketing planning. A filing says where a plaintiff lives and what kind of case was brought, not that a claim has merit, that a lawyer was hired or how a case ended. County means the county of residence of the first-listed plaintiff (the first-listed defendant's county when the United States sues; the tract's county in land condemnation cases), as the Federal Judicial Center codes it; the court also has codes for a plaintiff who lives in the U.S. outside the court's state and for one who lives abroad. Rights and deadlines in a matter are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/federal-filings-county/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state or territory of the federal court (the court's state, not the plaintiff's), or US
  level: county (the first-listed plaintiff lives in that county), former-county (a retired county code with several successors, such as Connecticut's old counties), county-not-recorded (a county code in no county list), out-of-state (code 88888: the plaintiff lives in the U.S. outside the court's state), outside-us (code 99999), retired-codes (a reconciliation row, not added to totals), district (one federal district court), state (the sum of the rows above for the state's courts) or us
  county: 5-digit county FIPS code (vintage 2025; Connecticut by planning region); the retired code on former-county rows; empty for other levels
  countyName: County name as the Census Bureau writes it, or the name of the category
  stateName: State or territory name
  district: District records: the federal district key (for example NYS, CAC)
  districtName: District records: the district court's name
  year: The latest complete federal fiscal year in the record (FY N runs October 1 of N-1 to September 30 of N, by filing date)
  fiscalYears: The ten fiscal years covered
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Federal civil cases filed over the ten fiscal years
  unit: Unit of value
  filed: Cases filed in the latest fiscal year, counted where the first-listed plaintiff lives
  filed_prior: Cases filed in the fiscal year before
  filed_change: Change from the prior fiscal year, in cases
  filed_change_pct: Change from the prior fiscal year, in percent (empty when the prior year had no cases)
  filed_10y: Cases filed over the ten fiscal years
  mdl: Of the latest year's cases, those that carry a multidistrict litigation (MDL) docket number
  mdl_pct: The MDL share of the latest year's cases, in percent
  mdl_10y: MDL cases over the ten fiscal years
  mdl_pct_10y: The MDL share of the ten-year total, in percent
  filed_personal_injury: Latest fiscal year: cases in the nature-of-suit group personal injury
  filed_product_liability: Latest fiscal year: cases in the nature-of-suit group product liability and mass tort
  filed_medical_malpractice: Latest fiscal year: cases in the nature-of-suit group medical malpractice
  filed_employment: Latest fiscal year: cases in the nature-of-suit group employment and wage claims
  filed_labor_benefits: Latest fiscal year: cases in the nature-of-suit group labor relations and employee benefits
  filed_civil_rights: Latest fiscal year: cases in the nature-of-suit group civil rights
  filed_immigration: Latest fiscal year: cases in the nature-of-suit group immigration
  filed_social_security: Latest fiscal year: cases in the nature-of-suit group Social Security and Medicare
  filed_consumer: Latest fiscal year: cases in the nature-of-suit group consumer credit and phone-call suits
  filed_contract_insurance: Latest fiscal year: cases in the nature-of-suit group contract and insurance
  filed_intellectual_property: Latest fiscal year: cases in the nature-of-suit group intellectual property
  filed_securities_antitrust: Latest fiscal year: cases in the nature-of-suit group securities, antitrust and banking
  filed_bankruptcy_appeals: Latest fiscal year: cases in the nature-of-suit group bankruptcy appeals and withdrawals
  filed_prisoner: Latest fiscal year: cases in the nature-of-suit group prisoner petitions
  filed_property_collections: Latest fiscal year: cases in the nature-of-suit group real property and federal collections
  filed_other: Latest fiscal year: cases in the nature-of-suit group other civil cases
  effectiveFrom: First day of the first fiscal year covered
  effectiveTo: Last day of the latest fiscal year covered
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
