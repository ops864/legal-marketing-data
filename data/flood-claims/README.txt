Flood insurance claims by county and year (FEMA NFIP, OpenFEMA), 1978 to 2026

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23845801

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Flood insurance claims by county and year (FEMA NFIP, OpenFEMA), 1978 to 2026, version 1.0.0, https://doi.org/10.5281/zenodo.23845801, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Flood insurance claims by county and year (FEMA NFIP, OpenFEMA), 1978 to 2026 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23845801

Cite as: Probative Growth, Flood insurance claims by county and year (FEMA NFIP, OpenFEMA), 1978 to 2026, 2026, https://doi.org/10.5281/zenodo.23845801

Not legal advice. These are counts of claims in FEMA's public NFIP claims file, not findings about any claim or insurer; private flood insurance is outside the file. This product uses the Federal Emergency Management Agency’s OpenFEMA API, but is not endorsed by FEMA. The Federal Government or FEMA cannot vouch for the data or analyses derived from these data after the data have been retrieved from the Agency's website(s).
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/flood-claims/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code, or US
  level: us, state or county
  area: US, the 2-digit state FIPS code or the 5-digit county FIPS code
  areaName: County and state, state name, or United States
  stateName: State name (United States on the national record)
  status: P: FEMA's own file
  text: The record in one plain-English sentence
  value: Claims with a loss in the ten full years (the same as claims_10y)
  unit: Unit of value
  firstYear: First year of loss with a claim for this place
  dataThrough: FEMA's as-of date for the file
  claims_total: NFIP claims, every year of loss in the file
  paid_claims_total: Claims with a payment above zero
  paid_usd_total: Dollars paid: building, contents and increased cost of compliance
  tenYears: The ten full years of loss counted in the _10y columns
  claims_10y: Claims with a loss in those ten years
  paid_claims_10y: Of them, claims with a payment
  paid_usd_10y: Dollars paid on them
  latestYear: The latest full year of loss
  claims_latest: Claims with a loss in the latest full year
  paid_usd_latest: Dollars paid on them
  currentYear: The current year (partial: losses to the as-of date)
  claims_current: Claims with a loss so far this year
  paid_usd_current: Dollars paid on them so far
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
