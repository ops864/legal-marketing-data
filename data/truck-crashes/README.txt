Truck and bus crashes by county, state and year (FMCSA crash file)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23743677

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Truck and bus crashes by county, state and year (FMCSA crash file), version 1.0.0, https://doi.org/10.5281/zenodo.23743677, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Truck and bus crashes by county, state and year (FMCSA crash file) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23743677

Not legal advice. These are counts of crash reports kept for research and marketing planning. A reported crash says nothing about who was at fault, and the counts leave out crashes that did not meet the federal reporting threshold. Rights and deadlines after a crash are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/truck-crashes/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state or territory the crash happened in, or US
  level: county, county-not-given (reports in the state without a usable county code), state, state-not-given (reports without a U.S. state code) or us
  county: 5-digit county FIPS code (the crash state's code plus the report's county code); a few are former codes still used by state reports (Connecticut's old counties); empty for other levels
  countyName: County name as the Census Bureau writes it
  stateName: State or territory name
  year: The latest complete calendar year in the record (the others are under `years` in the JSON)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Crashes in that year (same as crashes)
  unit: Unit of value
  crashes: Federally reportable crashes involving at least one truck or bus, counted once per state crash report
  fatal_crashes: Crashes in which someone died
  injury_crashes: Crashes in which someone was injured
  towaway_crashes: Crashes in which a vehicle was towed away because of damage
  bus_crashes: Crashes involving at least one bus
  deaths: People killed in those crashes (anyone: truck or bus occupants, other drivers, pedestrians), counted once per crash
  injuries: People injured in those crashes, counted once per crash
  crashes_10y: Crashes over the ten years in `years`
  deaths_10y: Deaths over the ten years in `years`
  active_carriers: State and US records: active FMCSA-registered carriers with at least one power unit whose main address is in the state (Company Census File, current); not where their trucks crash
  interstate_carriers: Of those, carriers registered for interstate operation
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
