New green cards (lawful permanent residents) by county, country of birth and class of admission

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23753002

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, New green cards (lawful permanent residents) by county, country of birth and class of admission, version 1.0.0, https://doi.org/10.5281/zenodo.23753002, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). New green cards (lawful permanent residents) by county, country of birth and class of admission (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23753002

Not legal advice. These are counts of people who became lawful permanent residents in the listed counties, rounded by the agency, not a measure of anyone's eligibility, case or need. Questions about a green card or citizenship are for a licensed immigration attorney or an accredited representative.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/green-cards/

Columns:
  id: Stable record id: dataset, place and period
  jurisdiction: Two-letter state or territory code, or US for the national record
  level: county, state or us
  county: 5-digit county FIPS code (vintage 2025; the three Connecticut counties OHSS still uses are the crosswalks' former codes); empty for state and US
  countyName: County name as the Census Bureau writes it
  stateName: State name
  fiscalYear: Federal fiscal year (October 1 to September 30)
  status: P: read from the primary source
  text: One plain sentence with the county's counts
  admissions_listed: New lawful permanent residents: the sum of the workbook's cells, each rounded to the nearest 10 by OHSS, so it understates the true figure
  immediate_relatives: Immediate relatives of U.S. citizens (spouses, children, parents)
  family_preference: Family preference categories 1st to 4th
  employment: Employment preference categories 1st to 5th
  diversity: Diversity Program
  refugee_asylee: Refugee and asylee adjustments
  other_class: Other classes of admission
  top_countries: The ten countries of birth with the most listed admissions in the county, with the count, largest first
  admissions_listed_prev: The same county's listed admissions in the previous fiscal year, when it was also on the top 200 list
  counties_listed: State and US records: how many top-200 counties are in the sum
  state_total_yearbook: State and US records: the Yearbook of Immigration Statistics total for the state (or nation) in the fiscal year
  listed_share_pct: admissions_listed as a percent of state_total_yearbook
  value: Same as admissions_listed
  unit: What value counts
  effectiveFrom: First day of the fiscal year
  effectiveTo: Last day of the fiscal year
  lastChecked: Date the OHSS files were last read
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
