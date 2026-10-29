Eviction filings by county and year (LSC Civil Court Data Initiative)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23752996

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Eviction filings by county and year (LSC Civil Court Data Initiative), version 1.0.0, https://doi.org/10.5281/zenodo.23752996, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Eviction filings by county and year (LSC Civil Court Data Initiative) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23752996

Not legal advice. These are counts of eviction cases filed in court, kept for research and market sizing. A filing is not an eviction carried out, a finding against a tenant or a measure of need, and one household can be filed against more than once. Questions about an eviction are for a licensed attorney or a local legal aid office.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/evictions/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or territory, or US
  county: 5-digit county FIPS code (vintage 2025; Connecticut's retired counties keep their old codes); empty for other levels
  countyName: County name as the Census Bureau writes it
  stateName: State name
  level: county, state (states and territories LSC reports on) or us
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Eviction filings in the last twelve months where all twelve are present; otherwise the filings in the months LSC reports (unit says which)
  unit: What the value counts
  months_reported: Months with a filing count in LSC's file
  first_month: First month in LSC's file (YYYY-MM)
  last_month: Last month in LSC's file (YYYY-MM)
  filings_total: Filings in all months reported
  filings_2016: Eviction filings in calendar year 2016; empty unless all twelve months are in LSC's file
  filings_2017: Eviction filings in calendar year 2017; empty unless all twelve months are in LSC's file
  filings_2018: Eviction filings in calendar year 2018; empty unless all twelve months are in LSC's file
  filings_2019: Eviction filings in calendar year 2019; empty unless all twelve months are in LSC's file
  filings_2020: Eviction filings in calendar year 2020; empty unless all twelve months are in LSC's file
  filings_2021: Eviction filings in calendar year 2021; empty unless all twelve months are in LSC's file
  filings_2022: Eviction filings in calendar year 2022; empty unless all twelve months are in LSC's file
  filings_2023: Eviction filings in calendar year 2023; empty unless all twelve months are in LSC's file
  filings_2024: Eviction filings in calendar year 2024; empty unless all twelve months are in LSC's file
  filings_last12: Filings in the twelve months through the latest month in LSC's files; empty unless all twelve are present
  renter_households: Renter-occupied housing units, as LSC reports them (American Community Survey)
  poverty_rate: Poverty rate in percent, as LSC reports it
  filings_per_100_renters_last12: filings_last12 per 100 renter households
  pct_of_historical_average: The latest month's filings as a percent of the county's own historical average for that month (LSC)
  effectiveFrom: First day of the first month reported
  effectiveTo: Last month reported
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
