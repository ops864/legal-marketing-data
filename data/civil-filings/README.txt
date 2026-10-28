Federal civil filings by nature of suit and district, 12-month periods since 2018

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23720009

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Federal civil filings by nature of suit and district, 12-month periods since 2018, version 1.0.0, https://doi.org/10.5281/zenodo.23720009, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Federal civil filings by nature of suit and district, 12-month periods since 2018 (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23720009

Not legal advice. These are counts from the U.S. Courts' published statistics, kept for marketing planning. A filing is a civil case commenced in a federal district court, not a person or a client. Check the Administrative Office's current tables.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/federal-civil-filings-by-type/

Columns:
  id: Stable record id (never reused)
  district: The district's code (two or three letters: CAC is the Central District of California, NJ is the District of New Jersey) or US for the nation
  districtName: The district's name
  circuit: The federal circuit (1st to 11th, or DC); empty for the nation
  table: C-3 (by district) or C-2 (national, by nature of suit)
  category: The case type: a Table C-3 column id (for example priv-motor-vehicle-pi) or a Table C-2 row id (for example health-care-pharma)
  categoryLabel: The case type as the table prints it
  group: all, us (the U.S. government is a party), priv (private cases) or nos (a Table C-2 nature-of-suit row)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: The machine value (see unit)
  unit: Unit of value
  periodEnd: The last day of the 12-month period (YYYY-MM-DD)
  priorValue: The count for the 12 months ending a year earlier; empty when that table is not in the series
  yoyChange: This period's count minus the prior one
  yoyPct: The change as a percent of the prior count; empty when the prior count is zero or missing. Read it with flags.noise: counts under 20 swing a lot
  comparePeriod: The period end of the prior count
  nationalSharePct: The district's share of the national count for the same case type, in percent (Table C-3 rows)
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
