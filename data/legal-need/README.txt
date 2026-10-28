Legal need by county: who may need a lawyer, from the American Community Survey

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23741886

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Legal need by county: who may need a lawyer, from the American Community Survey, version 1.0.0, https://doi.org/10.5281/zenodo.23741886, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Legal need by county: who may need a lawyer, from the American Community Survey (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23741886

Not legal advice. These are survey estimates of people with a characteristic, not counts of legal problems or cases: a renter, a veteran or a noncitizen does not necessarily need a lawyer. Each estimate has a margin of error, and small counties' estimates are rough.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/legal-need/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code (50 states and DC), or US for the national row
  county: 5-digit county FIPS code (2025 county list, as in the crosswalks dataset); empty on state and US rows
  level: county, state or us
  name: County and state, state name, or United States
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Total residents (ACS 2020-2024 5-year estimate, table B01001)
  unit: Unit of value
  period: The survey years the 5-year estimate pools (2020-2024)
  pop_total: Total residents (B01001 line 1)
  pop_total_moe90: 90% margin of error of pop_total (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  age_65plus: Residents aged 65 and over (B01001 lines 20-25 and 44-49); share of total residents
  age_65plus_moe90: 90% margin of error of age_65plus (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  age_65plus_pct: age_65plus as a percentage of its universe (pop_total), one decimal
  noncitizens: Residents who are not U.S. citizens (B05001 line 6); share of total residents
  noncitizens_moe90: 90% margin of error of noncitizens (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  noncitizens_pct: noncitizens as a percentage of its universe (pop_total), one decimal
  recent_arrivals: Foreign-born residents who entered the U.S. in 2010 or later (B05005 line 4); share of residents born outside the U.S.
  recent_arrivals_moe90: 90% margin of error of recent_arrivals (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  recent_arrivals_pct: recent_arrivals as a percentage of its universe (born_abroad), one decimal
  lep: Residents aged 5+ who speak English less than "very well", any language (B16005, the well / not well / not at all lines); share of residents aged 5+
  lep_moe90: 90% margin of error of lep (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  lep_pct: lep as a percentage of its universe (pop_5plus), one decimal
  spanish_lep: Spanish speakers aged 5+ who speak English less than "very well" (B16005 lines 6-8 and 28-30); share of residents aged 5+
  spanish_lep_moe90: 90% margin of error of spanish_lep (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  spanish_lep_pct: spanish_lep as a percentage of its universe (pop_5plus), one decimal
  divorced: Residents aged 15+ whose current marital status is divorced (B12001 lines 10 and 19); share of residents aged 15+
  divorced_moe90: 90% margin of error of divorced (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  divorced_pct: divorced as a percentage of its universe (pop_15plus), one decimal
  divorced_last_year: Residents aged 15+ divorced in the last 12 months (B12503 lines 5 and 10); the Census Bureau publishes this table for states and the US only, so county rows are empty
  divorced_last_year_moe90: 90% margin of error of divorced_last_year (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  divorced_last_year_pct: divorced_last_year as a percentage of its universe (pop_15plus), one decimal
  veterans: Civilian veterans aged 18+ (B21001 line 2); share of civilians aged 18+
  veterans_moe90: 90% margin of error of veterans (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  veterans_pct: veterans as a percentage of its universe (civ_pop_18plus), one decimal
  va_rated: Civilian veterans with a VA service-connected disability rating, any percentage (B21100 line 3); share of civilian veterans
  va_rated_moe90: 90% margin of error of va_rated (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  va_rated_pct: va_rated as a percentage of its universe (civ_veterans), one decimal
  va_rated_70plus: Civilian veterans rated 70 percent or higher (B21100 line 8); share of civilian veterans
  va_rated_70plus_moe90: 90% margin of error of va_rated_70plus (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  va_rated_70plus_pct: va_rated_70plus as a percentage of its universe (civ_veterans), one decimal
  disability: Civilian noninstitutionalized residents with a disability (B18101, the 12 'with a disability' lines); share of that population
  disability_moe90: 90% margin of error of disability (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  disability_pct: disability as a percentage of its universe (civ_noninst_pop), one decimal
  ssi_households: Households with Supplemental Security Income (B19056 line 2); share of households
  ssi_households_moe90: 90% margin of error of ssi_households (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  ssi_households_pct: ssi_households as a percentage of its universe (households), one decimal
  renter_households: Renter-occupied housing units (B25003 line 3); share of occupied housing units
  renter_households_moe90: 90% margin of error of renter_households (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  renter_households_pct: renter_households as a percentage of its universe (occupied_units), one decimal
  rent_burdened: Renter households paying 30 percent or more of household income on gross rent (B25070 lines 7-10); share of renter households whose rent share is computed
  rent_burdened_moe90: 90% margin of error of rent_burdened (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  rent_burdened_pct: rent_burdened as a percentage of its universe (renter_units), one decimal
  rent_severe: Renter households paying 50 percent or more (B25070 line 10); same universe
  rent_severe_moe90: 90% margin of error of rent_severe (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  rent_severe_pct: rent_severe as a percentage of its universe (renter_units), one decimal
  uninsured: Civilian noninstitutionalized residents with no health insurance coverage (B27010 lines 17, 33, 50 and 66); share of that population (B27010 line 1)
  uninsured_moe90: 90% margin of error of uninsured (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  uninsured_pct: uninsured as a percentage of its universe (B27010 line 1), one decimal
  median_household_income: Median household income in the past 12 months, in 2024 inflation-adjusted dollars (B19013 line 1); not a count, so not summed
  median_household_income_moe90: 90% margin of error of median_household_income (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  commute_vehicle: Workers aged 16+ who commute by car, truck or van, driving alone or carpooling (B08301 line 2); share of workers aged 16+
  commute_vehicle_moe90: 90% margin of error of commute_vehicle (a sum of lines: root of the summed squares, the Census Bureau's approximation); 0 where the estimate is controlled
  commute_vehicle_pct: commute_vehicle as a percentage of its universe (workers_16plus), one decimal
  born_abroad: Universe: residents born outside the United States (B05005 line 1)
  pop_5plus: Universe: residents aged 5 and over (B16005 line 1)
  pop_15plus: Universe: residents aged 15 and over (B12001 line 1)
  civ_pop_18plus: Universe: civilians aged 18 and over (B21001 line 1)
  civ_veterans: Universe: civilian veterans aged 18 and over (B21100 line 1)
  civ_noninst_pop: Universe: civilian noninstitutionalized residents (B18101 line 1)
  households: Universe: households (B19056 line 1)
  occupied_units: Universe: occupied housing units (B25003 line 1)
  renter_units: Universe: renter-occupied units whose rent share of income is computed (B25070 line 1 minus line 11)
  workers_16plus: Universe: workers aged 16 and over (B08301 line 1)
  noisy: Measures whose 90% margin of error is more than half the estimate (or whose estimate is 0 with a margin above 0): read them as rough
  suppressedMeasures: Measures the Census Bureau did not publish for this place (sample too small); their value is empty
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
