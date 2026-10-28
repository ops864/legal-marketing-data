VA disability compensation recipients by county and combined rating

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23744210

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, VA disability compensation recipients by county and combined rating, version 1.0.0, https://doi.org/10.5281/zenodo.23744210, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). VA disability compensation recipients by county and combined rating (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23744210

Not legal advice. These are counts of veterans already receiving VA disability compensation, not claims, appeals or unmet need: a rating says how VA scored a service-connected condition, not whether a veteran needs a lawyer or could get a higher rating. Questions about a claim are for an accredited attorney, agent or veterans service officer.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/va-compensation/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or Puerto Rico, or US (the US record and the rows for other territories, veterans abroad and unknown addresses)
  level: county, state (states, DC and Puerto Rico), other-territories, abroad, unknown or us
  county: 5-digit county FIPS code (vintage 2025; Connecticut planning regions); empty for other levels
  countyName: County name as the Census Bureau writes it
  stateName: State name
  fiscalYear: VA fiscal year of the count (it ends September 30)
  asOf: The day the count describes: veterans receiving compensation on September 30 of the fiscal year
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Same as recipients
  unit: Unit of value
  recipients: Veterans receiving VA disability compensation; null where VA suppressed the count
  rating_0_20: Recipients with a combined service-connected rating of 0% to 20%
  rating_30_40: Combined rating 30% to 40%
  rating_50_60: Combined rating 50% to 60%
  rating_70_90: Combined rating 70% to 90%
  rating_100: Combined rating 100%. VA's Annual Benefits Report counts veterans paid at the 100% rate for individual unemployability at their combined rating, and this file's bands match that report within 1%
  rating_suppressed: Recipients in rating cells VA suppressed: the total less the published bands (0 when all five are published)
  age_17_44: Recipients aged 17 to 44
  age_45_64: Recipients aged 45 to 64
  age_65_plus: Recipients aged 65 or older
  male: Male recipients
  female: Female recipients (age and sex groups can fall short of the total where VA has no birth date or sex on file)
  share_rated_70_plus: Percent of recipients rated 70% or higher (70-90% plus 100%), where both cells are published
  share_rated_100: Percent of recipients rated 100%
  recipients_prev: Recipients a year earlier (previous fiscal year's county file)
  rating_100_prev: Recipients rated 100% a year earlier
  change_recipients: recipients less recipients_prev
  change_pct: change_recipients as a percent of recipients_prev
  countiesSuppressed: State and US records: counties whose total VA suppressed (their veterans are missing from the sum)
  suppressedFields: Fields VA left blank for this row (suppressed to protect privacy)
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
