Crime and arrests by county and state: violent and property crime, DUI and drug arrests (FBI)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23772522

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Crime and arrests by county and state: violent and property crime, DUI and drug arrests (FBI), version 1.0.0, https://doi.org/10.5281/zenodo.23772522, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Crime and arrests by county and state: violent and property crime, DUI and drug arrests (FBI) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23772522

Not legal advice. These are counts of crimes and arrests that police agencies reported to the FBI, kept for research and marketing planning. An arrest says an officer took someone into custody, not that a charge was filed or proved. Whether and how to defend a charge, and every deadline, are for the person's own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/crime-data/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, or US
  level: county (agencies the FBI places in that county), county-not-given (statewide, tribal, transit and other agencies that list no single county; they count in the state total), state (the FBI's own state series) or us (the sum of the states)
  county: 5-digit county FIPS code (vintage 2025; one Alaska census area carries the former code the FBI agency list still uses); empty for other levels
  countyName: County name as the Census Bureau writes it
  stateName: State name
  year: The latest full calendar year in the record
  window: The five calendar years covered
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: DUI arrests reported in the latest year
  unit: Unit of value
  violent_crimes: Violent crimes (murder, rape, robbery, aggravated assault) agencies reported in the latest year
  property_crimes: Property crimes (burglary, larceny-theft, motor vehicle theft, arson) agencies reported in the latest year
  dui_arrests: Arrests for driving under the influence reported in the latest year (FBI offense id 260)
  drug_arrests: Arrests for drug abuse violations (the eleven FBI drug categories, ids 150-160, summed); state records only, empty for counties
  all_arrests: All arrests reported in the latest year
  violent_per_100k: Violent crimes per 100,000 residents of the agencies that reported
  property_per_100k: Property crimes per 100,000 residents of the agencies that reported
  dui_per_100k: DUI arrests per 100,000 residents of the agencies that reported
  drug_per_100k: Drug arrests per 100,000 residents of the agencies that reported (state records only)
  arrests_per_100k: All arrests per 100,000 residents of the agencies that reported
  violent_5y: Violent crimes over the years the record lists under years (the five-year window, or the years in which the county's agencies reported)
  property_5y: Property crimes over the years the record lists under years (the five-year window, or the years in which the county's agencies reported)
  dui_5y: DUI arrests over the years the record lists under years (the five-year window, or the years in which the county's agencies reported)
  drug_5y: Drug arrests over the years the record lists under years (the five-year window, or the years in which the county's agencies reported) (state records only)
  all_arrests_5y: All arrests over the years the record lists under years (the five-year window, or the years in which the county's agencies reported)
  years_reported: How many calendar years of the window the record lists under years
  population: Residents the record covers in the latest year: for a county, the larger of its agencies' FBI populations summed and its Census residents (vintage 2025); the state's population for state records
  coverage_offenses_pct: Share of those residents whose agencies reported offenses in the latest year, weighted by months reported (for every level, read from the agency answers; a year of zeros in every month from an agency serving 1,000 or more residents counts as not reported)
  coverage_arrests_pct: Share of those residents whose agencies reported arrests in the latest year, weighted by months reported (read the same way as the offense coverage)
  agencies: Agencies the FBI lists for the place (reporting or not)
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
