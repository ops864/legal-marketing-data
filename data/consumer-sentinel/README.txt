FTC Consumer Sentinel reports by state: fraud, identity theft and imposter scams, 2024 Data Book

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23741876

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, FTC Consumer Sentinel reports by state: fraud, identity theft and imposter scams, 2024 Data Book, version 1.0.0, https://doi.org/10.5281/zenodo.23741876, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). FTC Consumer Sentinel reports by state: fraud, identity theft and imposter scams, 2024 Data Book (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23741876

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
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  value: Reports (the count as the FTC prints it, except imposter-scams, which is derived); empty for imposter-scams when the FTC prints no share for the state (flags.suppressed)
  unit: Unit of value
  per100k: Reports per 100,000 people as the FTC prints it (fraud-other, identity-theft), or derived (imposter-scams)
  rank: The FTC's rank among the 50 states by reports per 100,000 people; empty for DC, Puerto Rico and the country
  rankOf: 
  sharePct: imposter-scams: the whole percent of the state's reports that the FTC prints for imposter scams
  topTenPosition: imposter-scams: its place in the state's top ten report categories as the FTC lists them
  derived: true when value and per100k come from a printed percent (rounded, flags.noise); flags.moe is the margin in reports
  pctReportingLoss: fraud-losses: percent of fraud reports that said money was lost
  totalLossUsd: fraud-losses: dollars reported lost, as the FTC prints in Appendix C
  medianLossUsd: fraud-losses: median dollar loss among reports with a loss
  text: The record in one plain-English sentence
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
