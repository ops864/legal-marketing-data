Mortgage delinquency by county and state (CFPB Mortgage Performance Trends), monthly from 2008

Version 1.0.1. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24116047

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Mortgage delinquency by county and state (CFPB Mortgage Performance Trends), monthly from 2008, version 1.0.1, https://doi.org/10.5281/zenodo.24116047, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Mortgage delinquency by county and state (CFPB Mortgage Performance Trends), monthly from 2008 (Version 1.0.1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24116047

Not legal advice. These are shares of mortgages in the CFPB's sample that were behind on payments, not counts of foreclosure filings or of people. A delinquent mortgage may be cured, modified or paid off. County figures exist only where the CFPB's sample holds at least 1,000 mortgages.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/mortgage-delinquency/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code (50 states and DC), or US
  level: us, state or county
  area: US, the 2-digit state FIPS code or the 5-digit county FIPS code
  areaName: County and state, state name, or United States
  stateName: State name (United States on the national record)
  month: The latest month in the CFPB's files (YYYY-MM)
  status: P: the CFPB's own published figure
  text: The record in one plain-English sentence
  value: Percent of mortgages 90 or more days delinquent in the latest month (the same as pct_90plus)
  unit: Unit of value
  pct_90plus: Percent of mortgages 90 or more days delinquent, latest month
  pct_90plus_year_ago: The same, twelve months earlier
  change_90plus_pts: Change over the twelve months, in percentage points
  pct_30_89: Percent of mortgages 30 to 89 days delinquent, latest month
  pct_30_89_year_ago: The same, twelve months earlier
  change_30_89_pts: Change over the twelve months, in percentage points
  peak_90plus: Highest monthly 90-day share since January 2008
  peak_90plus_month: First month the highest share was reached
  peak_90plus_last_month: Last month at the highest share (the same as peak_90plus_month when it held one month)
  peak_90plus_months: How many months the share stood at its highest value
  low_90plus: Lowest monthly 90-day share since January 2008
  low_90plus_month: First month the lowest share was reached
  low_90plus_last_month: Last month at the lowest share
  low_90plus_months: How many months the share stood at its lowest value
  months_published: Months with a published value since January 2008
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
