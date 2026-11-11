Legal marketing and intake hiring demand: pay, headcount and openings (Bureau of Labor Statistics)

Version 1.0.2. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24116041

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Legal marketing and intake hiring demand: pay, headcount and openings (Bureau of Labor Statistics), version 1.0.2, https://doi.org/10.5281/zenodo.24116041, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Legal marketing and intake hiring demand: pay, headcount and openings (Bureau of Labor Statistics) (Version 1.0.2) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24116041

Not legal advice. These are survey estimates from the Bureau of Labor Statistics. OEWS counts employees only and is rounded by the bureau; the monthly series are seasonally adjusted and revised; the state rates cover all nonfarm employers in a state, not only law firms. Pay is a statistic for a group of workers, not an offer or a guide to what one firm should pay.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/legal-hiring-demand/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code, or US
  level: us or state
  stateName: State name (United States on national records)
  kind: pay (annual role pay and headcount), month (a national monthly series) or state-demand (a state's job-openings and hires rates)
  scope: legal-services or all-industries for pay records; national-monthly or state-monthly for the monthly records
  seriesId: The statistics bureau's series id behind the record (for pay records, the median annual wage series)
  status: P: the figure as published by the bureau
  text: The record in one plain-English sentence
  value: The headline figure: median annual wage (pay), the month's value (month) or the average job-openings rate over the latest year (state-demand)
  unit: What value is measured in
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  role: The occupation (OEWS), pay records only (in legal-hiring-demand-values.csv, as id, column and value rows)
  soc: Standard Occupational Classification code of the role (pay records) (in legal-hiring-demand-values.csv, as id, column and value rows)
  seriesName: What a monthly series measures (month records) (in legal-hiring-demand-values.csv, as id, column and value rows)
  year: The OEWS year (May reference month; pay records) (in legal-hiring-demand-values.csv, as id, column and value rows)
  period: The month (YYYY-MM) of a monthly record, or the first and last month averaged for a state's rates (in legal-hiring-demand-values.csv, as id, column and value rows)
  employment: Employees in the role (OEWS) (in legal-hiring-demand-values.csv, as id, column and value rows)
  mean_annual: Mean annual wage, US dollars (in legal-hiring-demand-values.csv, as id, column and value rows)
  p10: 10th percentile annual wage (in legal-hiring-demand-values.csv, as id, column and value rows)
  p25: 25th percentile annual wage (in legal-hiring-demand-values.csv, as id, column and value rows)
  median_annual: Median annual wage (in legal-hiring-demand-values.csv, as id, column and value rows)
  p75: 75th percentile annual wage (in legal-hiring-demand-values.csv, as id, column and value rows)
  p90: 90th percentile annual wage (in legal-hiring-demand-values.csv, as id, column and value rows)
  employmentRsePct: Relative standard error of the employment estimate, percent, as published (in legal-hiring-demand-values.csv, as id, column and value rows)
  wageRsePct: Relative standard error of the mean wage, percent, as published (in legal-hiring-demand-values.csv, as id, column and value rows)
  months: Number of months averaged (state-demand) (in legal-hiring-demand-values.csv, as id, column and value rows)
  openingsRate: Average job-openings rate, percent of employment plus openings (state-demand) (in legal-hiring-demand-values.csv, as id, column and value rows)
  hiresRate: Average hires rate, percent of employment (state-demand) (in legal-hiring-demand-values.csv, as id, column and value rows)
