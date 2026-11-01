Google searches for a lawyer by practice area and state, English and Spanish (Google Ads Keyword Planner, Trends and Autocomplete)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23851294

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Google searches for a lawyer by practice area and state, English and Spanish (Google Ads Keyword Planner, Trends and Autocomplete), version 1.0.0, https://doi.org/10.5281/zenodo.23851294, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Google searches for a lawyer by practice area and state, English and Spanish (Google Ads Keyword Planner, Trends and Autocomplete) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23851294

Not legal advice. These are search counts and indexes from Google's keyword, Trends and Autocomplete data on the dates shown, kept for research and marketing planning. A search is not a client or a case, and the counts say nothing about any firm or lawyer.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/search-demand/

Columns:
  id: Stable record id (never reused)
  jurisdiction: US for the whole country, else the two-letter code of a state or DC; together the records cover the whole US, all 50 states and DC
  stateName: The place's name: United States, or the name of the state or DC
  level: family (measured searches for one query family in one place), crosscheck (agreement of the two measured sources in one place), trends (US: Google Trends interest by state over 12 months for one head query), autocomplete (US: Google's suggestions for one head query) or opportunity (searches a month per firm website advertising the practice)
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: The record's main figure, in `unit` (every other measure is in the JSON record and its text)
  unit: Unit of value
  asOf: Date of the Keyword Planner export the figures come from (or of the DataForSEO pull, crosscheck rows)
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
