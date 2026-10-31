Marriage and divorce rates by state (CDC NCHS), 1990 to 2024

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23845898

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Marriage and divorce rates by state (CDC NCHS), 1990 to 2024, version 1.0.0, https://doi.org/10.5281/zenodo.23845898, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Marriage and divorce rates by state (CDC NCHS), 1990 to 2024 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23845898

Not legal advice. These are provisional counts that state health departments send to NCHS, turned into rates per 1,000 residents. Divorce figures include annulments and, for some counties or states, petitions filed or legal separations. Divorce records cover the states that report divorces to NCHS: 45 states and DC in 2024.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/marriage-divorce/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code (50 states and DC), or US
  level: us or state
  kind: divorce (divorces and annulments) or marriage
  stateName: State name (United States on the national records)
  year: The latest year of the NCHS table (states without a rate that year have no record of that kind)
  status: P: the NCHS figure as published
  text: The record in one plain-English sentence
  value: The rate in that year (the same as rate)
  unit: Unit of value
  rate: Per 1,000 residents in the latest year
  rate_2019: Per 1,000 residents in 2019
  base_year: The first year from 2000 on with a published rate (2000 for most states)
  rate_base: Per 1,000 residents in base_year
  change_since_base: rate minus rate_base
  years_published: How many years have a published rate (1990, 1995 and 2000 onward for states; 2000 onward for the US)
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
