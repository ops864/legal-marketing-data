VA disability compensation recipients by county and combined rating

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23898138

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, VA disability compensation recipients by county and combined rating, version 2.0.0, https://doi.org/10.5281/zenodo.23898138, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). VA disability compensation recipients by county and combined rating (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23898138

Cite as: Probative Growth, VA disability compensation recipients by county and combined rating, 2026, https://doi.org/10.5281/zenodo.23898138

Not legal advice. These are counts of veterans already receiving VA disability compensation, not claims, appeals or unmet need: a rating says how VA scored a service-connected condition, not whether a veteran needs a lawyer or could get a higher rating. Questions about a claim are for an accredited attorney, agent or veterans service officer.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/va-compensation/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or Puerto Rico, or US (the US record and the rows for other territories, veterans abroad and unknown addresses)
  level: county, state (states, DC and Puerto Rico), other-territories, abroad, unknown or us
  fiscalYear: VA fiscal year of the count (it ends September 30)
  asOf: The day the count describes: veterans receiving compensation on September 30 of the fiscal year
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: Same as recipients
  unit: Unit of value
  recipients: Veterans receiving VA disability compensation
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  county: 5-digit county FIPS code (vintage 2025; Connecticut planning regions); county rows (in va-compensation-values.csv, as id, column and value rows)
  countyName: County name as the Census Bureau writes it (in va-compensation-values.csv, as id, column and value rows)
  stateName: State name (in va-compensation-values.csv, as id, column and value rows)
  rating_0_20: Recipients with a combined service-connected rating of 0% to 20% (in va-compensation-values.csv, as id, column and value rows)
  rating_30_40: Combined rating 30% to 40% (in va-compensation-values.csv, as id, column and value rows)
  rating_50_60: Combined rating 50% to 60% (in va-compensation-values.csv, as id, column and value rows)
  rating_70_90: Combined rating 70% to 90% (in va-compensation-values.csv, as id, column and value rows)
  rating_100: Combined rating 100%. VA's Annual Benefits Report counts veterans paid at the 100% rate for individual unemployability at their combined rating, and this file's bands match that report within 1% (in va-compensation-values.csv, as id, column and value rows)
  age_17_44: Recipients aged 17 to 44 (in va-compensation-values.csv, as id, column and value rows)
  age_45_64: Recipients aged 45 to 64 (in va-compensation-values.csv, as id, column and value rows)
  age_65_plus: Recipients aged 65 or older (in va-compensation-values.csv, as id, column and value rows)
  male: Male recipients (in va-compensation-values.csv, as id, column and value rows)
  female: Female recipients (age and sex groups count the recipients with a birth date and sex on file) (in va-compensation-values.csv, as id, column and value rows)
  share_rated_70_plus: Percent of recipients rated 70% or higher (70-90% plus 100%), where both cells are published (in va-compensation-values.csv, as id, column and value rows)
  share_rated_100: Percent of recipients rated 100% (in va-compensation-values.csv, as id, column and value rows)
  recipients_prev: Recipients a year earlier (previous fiscal year's county file) (in va-compensation-values.csv, as id, column and value rows)
  rating_100_prev: Recipients rated 100% a year earlier (in va-compensation-values.csv, as id, column and value rows)
  change_recipients: recipients less recipients_prev (in va-compensation-values.csv, as id, column and value rows)
  change_pct: change_recipients as a percent of recipients_prev (in va-compensation-values.csv, as id, column and value rows)
  note: Caveats (in va-compensation-values.csv, as id, column and value rows)
