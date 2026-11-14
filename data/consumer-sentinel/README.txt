FTC Consumer Sentinel reports by state: fraud, identity theft and imposter scams, 2024 Data Book

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23963186

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, FTC Consumer Sentinel reports by state: fraud, identity theft and imposter scams, 2024 Data Book, version 2.0.0, https://doi.org/10.5281/zenodo.23963186, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). FTC Consumer Sentinel reports by state: fraud, identity theft and imposter scams, 2024 Data Book (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23963186

Cite as: Probative Growth, FTC Consumer Sentinel reports by state: fraud, identity theft and imposter scams, 2024 Data Book, 2026, https://doi.org/10.5281/zenodo.23963186

Not legal advice. These are counts of reports made to the FTC, kept for marketing planning. A report is a consumer's account, not a finding that fraud happened, and the state tables leave out reports from state-specific data contributors. Deadlines and rights are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/consumer-sentinel/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code, DC, US (federal), ABA, or PLATFORM:<name>
  jurisdictionName: Jurisdiction name
  measure: fraud-other, identity-theft, imposter-scams or fraud-losses
  measureLabel: The measure in plain words
  year: The calendar year the reports were made (the Data Book year)
  status: P primary source, S secondary source
  value: Reports as printed in the data book (imposter-scams is derived)
  unit: Unit of value
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  per100k: Reports per 100,000 people as the FTC prints it (fraud-other, identity-theft), or derived (imposter-scams) (in consumer-sentinel-values.csv, as id, column and value rows)
  rank: The FTC's rank among the 50 states by reports per 100,000 people; empty for DC, Puerto Rico and the country (in consumer-sentinel-values.csv, as id, column and value rows)
  rankOf:  (in consumer-sentinel-values.csv, as id, column and value rows)
  sharePct: imposter-scams: the whole percent of the state's reports that the FTC prints for imposter scams (in consumer-sentinel-values.csv, as id, column and value rows)
  topTenPosition: imposter-scams: its place in the state's top ten report categories as the FTC lists them (in consumer-sentinel-values.csv, as id, column and value rows)
  derived: true when value and per100k come from a printed percent (rounded, flags.noise); flags.moe is the margin in reports (in consumer-sentinel-values.csv, as id, column and value rows)
  pctReportingLoss: fraud-losses: percent of fraud reports that said money was lost (in consumer-sentinel-values.csv, as id, column and value rows)
  totalLossUsd: fraud-losses: dollars reported lost, as the FTC prints in Appendix C (in consumer-sentinel-values.csv, as id, column and value rows)
  medianLossUsd: fraud-losses: median dollar loss among reports with a loss (in consumer-sentinel-values.csv, as id, column and value rows)
