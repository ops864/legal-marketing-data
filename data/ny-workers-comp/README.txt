New York workers' compensation claims by county and accident year

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23964068

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, New York workers' compensation claims by county and accident year, version 2.0.0, https://doi.org/10.5281/zenodo.23964068, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). New York workers' compensation claims by county and accident year (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23964068

Cite as: Probative Growth, New York workers' compensation claims by county and accident year, 2026, https://doi.org/10.5281/zenodo.23964068

Not legal advice. These are counts of claims the Board assembled, not claims accepted or paid, and a share with an attorney says how often workers were represented, not whether they needed to be. Questions about a workers' compensation claim are for a licensed New York attorney or the Board.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/ny-workers-comp/

Columns:
  id: Stable record id: dataset, place and period
  jurisdiction: NY for every record (the dataset is New York only)
  level: county, state (all of New York) or unknown (claims with no county in the source)
  accidentYear: Calendar year of the accident or disease onset (the claim's accident_date)
  status: P: aggregated from the primary source
  text: One plain sentence with the county's counts
  value: Same as claims
  unit: What value counts
  claims: Claims the Board assembled with this injury county and accident year; published from 11 claims up
  effectiveFrom: First day of the accident year
  effectiveTo: Last day of the accident year
  lastChecked: Date the Board's file was last read
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  county: 5-digit county FIPS code (vintage 2025); empty for the state and unknown records (in ny-workers-comp-values.csv, as id, column and value rows)
  countyName: County name as the Census Bureau writes it (Unknown for the unknown record) (in ny-workers-comp-values.csv, as id, column and value rows)
  atty_rep_claims: Claims with an attorney or representative (atty_rep_ind = Y); published when it and the claims without one are each 11 or more (in ny-workers-comp-values.csv, as id, column and value rows)
  controverted_claims: Claims with a controverted date (the carrier or employer disputed the claim); published from 11 up (in ny-workers-comp-values.csv, as id, column and value rows)
  hearing_claims: Claims with at least one hearing held; published from 11 up (in ny-workers-comp-values.csv, as id, column and value rows)
  hearings: Hearings held on those claims (sum of hearing_count); published with hearing_claims (in ny-workers-comp-values.csv, as id, column and value rows)
  ppd_claims: Claims classified permanent partial disability (a scheduled or non-scheduled loss date is set); published from 11 up (in ny-workers-comp-values.csv, as id, column and value rows)
  ptd_claims: Claims classified permanent total disability (a PTD date is set); published from 11 up (in ny-workers-comp-values.csv, as id, column and value rows)
  occ_disease_claims: Claims flagged as occupational disease; published from 11 up (in ny-workers-comp-values.csv, as id, column and value rows)
  atty_rep_share_pct: atty_rep_claims as a percent of claims (in ny-workers-comp-values.csv, as id, column and value rows)
  controverted_share_pct: controverted_claims as a percent of claims (in ny-workers-comp-values.csv, as id, column and value rows)
