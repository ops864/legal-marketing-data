What US state bars charge, and require, to file or review lawyer advertising

Version 3.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23963654

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, What US state bars charge, and require, to file or review lawyer advertising, version 3.0.0, https://doi.org/10.5281/zenodo.23963654, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). What US state bars charge, and require, to file or review lawyer advertising (Version 3.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23963654

Not legal advice. This is a plain-English summary of public sources, kept for marketing planning, and rules change. Check with your state bar and your own counsel before you run an ad.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/lawyer-ad-filing-fees/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code, DC, US (federal), ABA, or PLATFORM:<name>
  jurisdictionName: Jurisdiction name
  status: P primary source, S secondary source
  category: Filing category: files_ads, files_solicitations_only, voluntary_review_only, no_filing or unknown
  category_label: The category in words
  filing_required: yes, no, solicitations_only, voluntary_only or unknown
  rule_cite: The rule or statute cited
  text: The record in one plain-English sentence
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  timing: When the filing is due: before_first_use, at_or_before_first_use, after_first_use, not_applicable or unknown (in filing-values.csv, as id, column and value rows)
  timing_detail: The rule’s timing in words, including any review period (in filing-values.csv, as id, column and value rows)
  days_before_first_use_required: Fewest days before first use the filing may be made, where the rule states a number (0 = it may be made at first use); empty when no number is stated (in filing-values.csv, as id, column and value rows)
  days_after_first_use_allowed: Most days after first use the filing may be made, where the rule states a number; empty when none (in filing-values.csv, as id, column and value rows)
  review_response_days: Days the bar says it takes to respond to a filing or an advisory request, where it states a number; empty when none (in filing-values.csv, as id, column and value rows)
  advance_opinion_lead_days: Days before first use an optional advisory opinion is requested, where the rule states a number; empty when none (in filing-values.csv, as id, column and value rows)
  days_detail: The rule on days from filing to first use, in one sentence; each number cites its source (in filing-values.csv, as id, column and value rows)
  ad_review_fy: The most recent year for which the bar itself states how many lawyer ads it reviewed (each bar's own year; empty when none is stated) (in filing-values.csv, as id, column and value rows)
  ad_review_count: How many lawyer ads the bar reviewed in that year, as the bar states it. Not comparable across states: each bar counts something different (ads reviewed, submissions, applications, filings) under a different filing duty. Empty when no count is stated. (in filing-values.csv, as id, column and value rows)
  ad_review_resubmissions: Revised ads reviewed again that year, where the bar states a number; empty when none (in filing-values.csv, as id, column and value rows)
  ad_review_basis: exact, approximate (the bar says about or nearly) or lower_bound (more than, or a plus sign) (in filing-values.csv, as id, column and value rows)
  ad_review_series: Every year the bar states a count for, in one line (the JSON file also carries each year's source and quote) (in filing-values.csv, as id, column and value rows)
  fee_standard_usd: Standard filing fee per advertisement in US dollars (0 when there is none); empty when unknown (in filing-values.csv, as id, column and value rows)
  late_fee_usd: Late filing fee in US dollars; empty when none or unknown (in filing-values.csv, as id, column and value rows)
  advisory_fee_usd: Fee for an optional advance advisory opinion in US dollars; empty when none or unknown (in filing-values.csv, as id, column and value rows)
  expedited_available: Whether an expedited review exists (yes, no, not_applicable or unknown) (in filing-values.csv, as id, column and value rows)
  fee_effective_date: The day the fee took effect (YYYY-MM-DD), if stated (in filing-values.csv, as id, column and value rows)
  portal_url: The bar’s filing portal or page (in filing-values.csv, as id, column and value rows)
  retention_years: Years a lawyer must keep copies of ads or solicitations (0 = no rule) (in filing-values.csv, as id, column and value rows)
  coverage: verified, verified_with_gaps or unknown: how much of the row was read from a primary source (in filing-values.csv, as id, column and value rows)
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known (in filing-values.csv, as id, column and value rows)
  detail: A short sourced detail on the record (in filing-values.csv, as id, column and value rows)
