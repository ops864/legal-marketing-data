County income and migration from IRS tax returns

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23752984

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, County income and migration from IRS tax returns, version 1.0.0, https://doi.org/10.5281/zenodo.23752984, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). County income and migration from IRS tax returns (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23752984

Not legal advice. These are totals from filed individual tax returns, not a county's wealth, a person's income or a prediction of who needs a lawyer, and migration shows where filers' addresses changed, not why. Questions about taxes, estates or property are for a licensed attorney or tax professional.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/county-income/

Columns:
  id: Stable record id: dataset, place and period
  jurisdiction: Two-letter state code (DC included), or US for the national record
  level: county, state or us
  county: 5-digit county FIPS code (vintage 2025); empty for state and US
  countyName: County name as the Census Bureau writes it
  taxYear: Tax year of the income figures
  migrationYears: The two filing years the migration flows compare (people who filed in both)
  status: P: read from the primary source
  returns: Individual income tax returns filed (the IRS rounds county cells to the nearest 10)
  people: Individuals on those returns (exemptions)
  agi: Adjusted gross income of those returns, in dollars (the IRS publishes $ thousands)
  agi_per_return: agi divided by returns, rounded to whole dollars
  wage_returns: Returns with salary and wage income
  wages: Salaries and wages on those returns, in dollars
  wages_per_wage_return: wages divided by wage_returns, rounded to whole dollars
  returns_prev: Returns in the previous tax year
  agi_prev: Adjusted gross income in the previous tax year, in dollars
  agi_per_return_prev: agi_prev divided by returns_prev
  change_returns_pct: Percent change in returns from the previous tax year
  change_agi_per_return_pct: Percent change in AGI per return from the previous tax year
  mig_in_other_returns: Returns that moved in from other states (county: from a different state; state: from any other state), comparing the two filing years
  mig_in_other_agi: AGI of those returns, in dollars
  mig_out_other_returns: Returns that moved out to other states
  mig_out_other_agi: AGI of those returns, in dollars
  mig_in_same_returns: Returns that moved in from elsewhere in the same state (state record: moves within the state)
  mig_in_same_agi: AGI of those returns, in dollars
  mig_out_same_returns: Returns that moved out to elsewhere in the same state
  mig_out_same_agi: AGI of those returns, in dollars
  mig_net_other_returns: mig_in_other_returns less mig_out_other_returns
  mig_net_other_agi: mig_in_other_agi less mig_out_other_agi, in dollars
  text: One plain sentence with the county's income and migration
  value: Adjusted gross income in dollars (same as agi)
  unit: What value counts
  suppressedFields: Migration fields the IRS withheld (under 20 returns), left empty and never estimated
  effectiveFrom: First day of the tax year
  effectiveTo: Last day of the tax year
  lastChecked: Date the IRS files were last read
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
