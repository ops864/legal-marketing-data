VA disability compensation, pension and survivor dollars by county (VA GDX report)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23753088

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, VA disability compensation, pension and survivor dollars by county (VA GDX report), version 1.0.0, https://doi.org/10.5281/zenodo.23753088, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). VA disability compensation, pension and survivor dollars by county (VA GDX report) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23753088

Not legal advice. These are dollars VA paid, placed by the address of the veteran or survivor receiving them; they are not claims, awards, backlogs or unmet need. Questions about a claim are for an accredited attorney, agent or veterans service officer.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/va-spending/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or territory, or US
  county: 5-digit county FIPS code (vintage 2025; Connecticut's retired counties keep their old codes); empty for other levels
  countyName: County name as the Census Bureau writes it
  stateName: State name
  level: county, state (states, DC, Puerto Rico and Guam), foreign, fas, other-territories, unknown or us
  fiscalYear: VA fiscal year of the dollars (it ends September 30)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Same as totalDirect: dollars of VA direct benefit expenditures
  unit: What the value counts
  totalDirect: Total direct expenditure in dollars: compPension + dicSurvivors + insurance + adaptedHousing, recomputed
  compPension: Disability compensation and veterans pension payments, dollars
  dicSurvivors: Dependency and indemnity compensation (DIC) and survivors pension, including benefits for children of certain veterans, dollars
  insurance: VA life insurance payments (death claims, dividends, cash surrenders and disability benefits), dollars
  adaptedHousing: Specially Adapted Housing and Special Housing Adaptation grants, dollars
  compSurvivors: compPension + dicSurvivors: the dollars that follow disability, pension and survivor awards
  compPension_prev: compPension a year earlier (previous fiscal year's workbook), dollars; empty where the county could not be matched
  dicSurvivors_prev: dicSurvivors a year earlier, dollars
  change_comp_survivors: compSurvivors less the year-earlier figures, dollars
  change_pct: change_comp_survivors as a percent of the year-earlier compSurvivors
  effectiveFrom: First day of the fiscal year
  effectiveTo: Last day of the fiscal year
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
