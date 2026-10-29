New business applications by county (Census Business Formation Statistics)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23752969

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, New business applications by county (Census Business Formation Statistics), version 1.0.0, https://doi.org/10.5281/zenodo.23752969, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). New business applications by county (Census Business Formation Statistics) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23752969

Not legal advice. A business application is a request for an Employer Identification Number, not a company formed, an owner or a client, and the Census Bureau adds noise to county counts, so small differences are not meaningful. Questions about forming or running a business are for a licensed attorney.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/business-applications/

Columns:
  id: Stable record id: dataset, place and period
  jurisdiction: Two-letter state code (DC included), or US for the national record
  level: county, state or us
  county: 5-digit county FIPS code (vintage 2025; the old Connecticut counties and planning regions both appear, for the years each is published); empty for state and US
  countyName: County or county-equivalent name
  latestYear: Latest year in the file
  status: P: read from the primary source
  text: One plain sentence with the latest count and change
  value: Business applications in the latest year
  unit: What value counts
  ba_2005: Business applications in 2005; null where the county has no figure under this code for that year
  ba_2006: Business applications in 2006; null where the county has no figure under this code for that year
  ba_2007: Business applications in 2007; null where the county has no figure under this code for that year
  ba_2008: Business applications in 2008; null where the county has no figure under this code for that year
  ba_2009: Business applications in 2009; null where the county has no figure under this code for that year
  ba_2010: Business applications in 2010; null where the county has no figure under this code for that year
  ba_2011: Business applications in 2011; null where the county has no figure under this code for that year
  ba_2012: Business applications in 2012; null where the county has no figure under this code for that year
  ba_2013: Business applications in 2013; null where the county has no figure under this code for that year
  ba_2014: Business applications in 2014; null where the county has no figure under this code for that year
  ba_2015: Business applications in 2015; null where the county has no figure under this code for that year
  ba_2016: Business applications in 2016; null where the county has no figure under this code for that year
  ba_2017: Business applications in 2017; null where the county has no figure under this code for that year
  ba_2018: Business applications in 2018; null where the county has no figure under this code for that year
  ba_2019: Business applications in 2019; null where the county has no figure under this code for that year
  ba_2020: Business applications in 2020; null where the county has no figure under this code for that year
  ba_2021: Business applications in 2021; null where the county has no figure under this code for that year
  ba_2022: Business applications in 2022; null where the county has no figure under this code for that year
  ba_2023: Business applications in 2023; null where the county has no figure under this code for that year
  ba_2024: Business applications in 2024; null where the county has no figure under this code for that year
  ba_2025: Business applications in 2025; null where the county has no figure under this code for that year
  change_pct_1y: Percent change from the previous year
  change_pct_since_2019: Percent change since 2019, the last year before the pandemic
  effectiveFrom: First day of the first year
  effectiveTo: Last day of the latest year
  lastChecked: Date the Census file was last read
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
