Wage-and-hour and OSHA enforcement by county, state, act and industry (U.S. Department of Labor)

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23898146

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Wage-and-hour and OSHA enforcement by county, state, act and industry (U.S. Department of Labor), version 2.0.0, https://doi.org/10.5281/zenodo.23898146, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Wage-and-hour and OSHA enforcement by county, state, act and industry (U.S. Department of Labor) (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23898146

Cite as: Probative Growth, Wage-and-hour and OSHA enforcement by county, state, act and industry (U.S. Department of Labor), 2026, https://doi.org/10.5281/zenodo.23898146

Not legal advice. These are counts and sums of federal enforcement findings, kept for research and marketing planning. A WHD back-wage finding or an OSHA citation is the agency's finding, not a court judgment, and employers can contest them. Rights and deadlines in a wage or injury matter are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/wage-enforcement/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state or territory, or US
  level: county, county-not-given (cases and inspections in the state whose ZIP code places them in no county of it), state, state-not-given (no usable state code), us, act (one law WHD enforces, state or US) or industry (one NAICS sector, state or US)
  year: The latest complete federal fiscal year in the record (FY N runs October 1 of N-1 to September 30 of N)
  fiscalYears: The ten fiscal years covered
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: Back wages WHD found owed over the ten fiscal years, in dollars
  unit: Unit of value
  whd_cases_10y: WHD cases over the ten fiscal years
  whd_back_wages_10y: Back wages over the ten fiscal years, in dollars
  whd_employees_owed_10y: Employees due back wages over the ten fiscal years
  whd_penalties_10y: Civil money penalties over the ten fiscal years, in dollars
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  county: 5-digit county FIPS code (vintage 2025; Connecticut by planning region), placed by ZIP code; county rows (in wage-enforcement-values.csv, as id, column and value rows)
  countyName: County name as the Census Bureau writes it (in wage-enforcement-values.csv, as id, column and value rows)
  stateName: State or territory name (in wage-enforcement-values.csv, as id, column and value rows)
  act: Act records: the law's short id (flsa, flsa-overtime, flsa-minimum-wage, flsa-retaliation, child-labor, fmla, davis-bacon, service-contract, contract-work-hours, h-2a, h-2b, h-1b, mspa, garnishment, polygraph, other) (in wage-enforcement-values.csv, as id, column and value rows)
  actName: Act records: the law's name (in wage-enforcement-values.csv, as id, column and value rows)
  sector: Industry records: the NAICS sector code (2 digits, or 31-33, 44-45, 48-49), or unclassified (in wage-enforcement-values.csv, as id, column and value rows)
  sectorName: Industry records: the NAICS sector name (in wage-enforcement-values.csv, as id, column and value rows)
  whd_cases: Latest fiscal year: concluded WHD compliance actions (cases) whose findings ended in that year; for act records, cases with a finding under that law (in wage-enforcement-values.csv, as id, column and value rows)
  whd_cases_with_violations: Of those, cases where WHD recorded at least one violation (in wage-enforcement-values.csv, as id, column and value rows)
  whd_back_wages: Back wages the employers agreed to pay or were found to owe, in dollars (given where 3 or more employees were owed) (in wage-enforcement-values.csv, as id, column and value rows)
  whd_employees_owed: Employees due back wages (given where 3 or more) (in wage-enforcement-values.csv, as id, column and value rows)
  whd_penalties: Civil money penalties assessed, in dollars (in wage-enforcement-values.csv, as id, column and value rows)
  whd_flsa_overtime_back_wages: Back wages for Fair Labor Standards Act overtime violations, in dollars (in wage-enforcement-values.csv, as id, column and value rows)
  whd_flsa_minimum_wage_back_wages: Back wages for FLSA minimum wage violations, in dollars (in wage-enforcement-values.csv, as id, column and value rows)
  whd_child_labor_violations: FLSA child labor violations (in wage-enforcement-values.csv, as id, column and value rows)
  osha_inspections: Latest fiscal year: OSHA inspections opened (federal OSHA and state-plan offices; records of no inspection left out) (in wage-enforcement-values.csv, as id, column and value rows)
  osha_complaint_inspections: Of those, inspections that followed a complaint (in wage-enforcement-values.csv, as id, column and value rows)
  osha_fatality_catastrophe_inspections: Of those, inspections that followed a fatality or catastrophe (OSHA's Fat/Cat type; the separate Accident type is in osha_accident_inspections in the JSON) (in wage-enforcement-values.csv, as id, column and value rows)
  osha_violations: Citation items from those inspections (deleted items left out) (in wage-enforcement-values.csv, as id, column and value rows)
  osha_serious: Serious violations cited (in wage-enforcement-values.csv, as id, column and value rows)
  osha_willful: Willful violations cited (in wage-enforcement-values.csv, as id, column and value rows)
  osha_repeat: Repeat violations cited (in wage-enforcement-values.csv, as id, column and value rows)
  osha_current_penalties: Current OSHA penalties on those citations (after any settlement or decision), in dollars (in wage-enforcement-values.csv, as id, column and value rows)
  osha_inspections_10y: OSHA inspections over the ten fiscal years (in wage-enforcement-values.csv, as id, column and value rows)
  osha_violations_10y: Violations cited over the ten fiscal years (in wage-enforcement-values.csv, as id, column and value rows)
  osha_serious_10y: Serious violations over the ten fiscal years (in wage-enforcement-values.csv, as id, column and value rows)
  osha_current_penalties_10y: Current OSHA penalties over the ten fiscal years, in dollars (in wage-enforcement-values.csv, as id, column and value rows)
  note: Caveats (in wage-enforcement-values.csv, as id, column and value rows)
