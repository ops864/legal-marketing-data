Fatal crashes by county and type: trucks, motorcycles, pedestrians and bicyclists, NHTSA FARS 2019 to 2024

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23733739

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Fatal crashes by county and type: trucks, motorcycles, pedestrians and bicyclists, NHTSA FARS 2019 to 2024, version 1.0.0, https://doi.org/10.5281/zenodo.23733739, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Fatal crashes by county and type: trucks, motorcycles, pedestrians and bicyclists, NHTSA FARS 2019 to 2024 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23733739

Not legal advice. These are counts from NHTSA's public crash census, kept for marketing planning. A county's count says nothing about who was at fault, and the newest year can change when NHTSA issues its final file.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/fatal-crashes-by-county/

Columns:
  id: Stable record id (never reused)
  area: The place: a 5-digit county FIPS code (e.g. 48201), a 2-digit state FIPS code (e.g. 48) or US
  areaName: The county, state or country name
  areaType: county, state or us
  state: Two-letter state code (empty for the US)
  year: The newest FARS year in this record (the other years are under `years` in the JSON and in fatal_crashes_YYYY)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Fatal crashes in that year
  unit: Unit of value
  fatalities: People who died within 30 days of the crash, in that year
  large_truck_crashes: Fatal crashes with at least one truck over 10,000 lb GVWR (FARS body types 60-64, 66, 67, 71, 72, 78)
  large_truck_deaths: People killed in those crashes (anyone: truck occupants, other drivers, pedestrians)
  motorcycle_crashes: Fatal crashes with at least one motorcycle, moped, scooter or three-wheeler (body types 80-89)
  motorcyclist_deaths: Drivers and passengers killed on those vehicles
  pedestrian_crashes: Fatal crashes with at least one pedestrian
  pedestrian_deaths: Pedestrians killed
  bicyclist_crashes: Fatal crashes with at least one bicyclist
  bicyclist_deaths: Bicyclists killed
  alcohol_impaired_crashes: Fatal crashes with a driver at 0.08 BAC or more, from NHTSA's 10 multiple-imputation draws (MIDRVACC), rounded
  alcohol_impaired_deaths: People killed in those crashes, same method, rounded
  speeding_crashes: Fatal crashes with a vehicle coded speeding-related (SPEEDREL 1 to 5)
  work_zone_crashes: Fatal crashes in a work zone (WRK_ZONE 1 to 4)
  rural_crashes: Fatal crashes on a rural road (RUR_URB 1)
  urban_crashes: Fatal crashes on an urban road (RUR_URB 2); roads of another or unknown setting are in neither column
  population: Census Bureau population estimate for that county and year (Vintage 2025; Vintage 2019 for 2019); empty where the Bureau has no matching county (Connecticut from 2020)
  fatal_crashes_per_100k: Fatal crashes per 100,000 residents
  fatalities_per_100k: Deaths per 100,000 residents
  county_class: mostly rural if half or more of the county's 2020 residents live in rural areas (Census Bureau), else mostly urban; counties only
  pct_rural_2020: Percent of the county's 2020 residents in rural areas
  file_status: final or annual report file (NHTSA's first release of a year, which can change)
  fatal_crashes_2019: Fatal crashes in 2019
  fatal_crashes_2020: Fatal crashes in 2020
  fatal_crashes_2021: Fatal crashes in 2021
  fatal_crashes_2022: Fatal crashes in 2022
  fatal_crashes_2023: Fatal crashes in 2023
  fatal_crashes_2024: Fatal crashes in 2024
  change_pct_since_2019: Percent change in fatal crashes from 2019 to the newest year (empty when 2019 was zero)
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
