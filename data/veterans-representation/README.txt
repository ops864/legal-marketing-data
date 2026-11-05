VA-accredited attorneys and claims agents per veteran, by state, with county counts and Board of Veterans' Appeals outcomes by type of representation

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23964365

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, VA-accredited attorneys and claims agents per veteran, by state, with county counts and Board of Veterans' Appeals outcomes by type of representation, version 2.0.0, https://doi.org/10.5281/zenodo.23964365, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). VA-accredited attorneys and claims agents per veteran, by state, with county counts and Board of Veterans' Appeals outcomes by type of representation (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23964365

Not legal advice. These are counts of people on the VA's public accreditation lists and of Board of Veterans' Appeals decisions, kept for marketing planning. An accreditation is the VA's permission to help with claims, not an endorsement or a measure of quality, and the counts say nothing about any veteran's claim. Deadlines and fees are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/veterans-representation/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or territory; US for the United States and the Board's rows; OTHER for people whose list entry shows a blank, military, foreign or unrecognised state
  areaName: Area name
  areaType: us, state, dc, territory, other, or bva (a Board of Veterans' Appeals row)
  status: P primary source, S secondary source
  value: Accredited attorneys plus accredited claims agents (the people on the VA lists); for a bva row, the Board's decisions in that row
  unit: Unit of value
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  state:  (in veterans-representation-values.csv, as id, column and value rows)
  fips:  (in veterans-representation-values.csv, as id, column and value rows)
  attorneys: Attorneys on the VA Office of General Counsel's list whose business address is in the state (in veterans-representation-values.csv, as id, column and value rows)
  agents: Claims agents on the VA's list whose business address is in the state (in veterans-representation-values.csv, as id, column and value rows)
  new12m: Attorneys plus agents accredited in the 12 months before the list was read (in veterans-representation-values.csv, as id, column and value rows)
  veterans: Living veterans the VA projects for the date in veteransDate (VetPop2023), rounded to the nearest 1,000 (in veterans-representation-values.csv, as id, column and value rows)
  veteransDate:  (in veterans-representation-values.csv, as id, column and value rows)
  veteransPerAttorney: veterans divided by attorneys; empty when there are none (in veterans-representation-values.csv, as id, column and value rows)
  veteransPerRep: veterans divided by attorneys plus agents (in veterans-representation-values.csv, as id, column and value rows)
  repsPer100kVeterans: Attorneys plus agents per 100,000 veterans (in veterans-representation-values.csv, as id, column and value rows)
  countiesTotal: Counties in the VA's county table for the state (empty for Connecticut, Puerto Rico and the island territories) (in veterans-representation-values.csv, as id, column and value rows)
  countiesWithNone: Counties with no accredited attorney or agent whose business ZIP code falls mostly in the county (in veterans-representation-values.csv, as id, column and value rows)
  veteransInCountiesWithNone: Veterans in those counties (the VA's county counts, each rounded to 1,000, added up) (in veterans-representation-values.csv, as id, column and value rows)
  bvaFy:  (in veterans-representation-values.csv, as id, column and value rows)
  bvaSystem:  (in veterans-representation-values.csv, as id, column and value rows)
  bvaRepresentation: For a bva row: Agent, Attorney, a veterans service organization, No Representation, or All (in veterans-representation-values.csv, as id, column and value rows)
  allowed:  (in veterans-representation-values.csv, as id, column and value rows)
  remanded:  (in veterans-representation-values.csv, as id, column and value rows)
  denied:  (in veterans-representation-values.csv, as id, column and value rows)
  other:  (in veterans-representation-values.csv, as id, column and value rows)
  allowedPct: For a bva row: share of the row's decisions that were allowed (the Board's own percentage) (in veterans-representation-values.csv, as id, column and value rows)
  remandedPct:  (in veterans-representation-values.csv, as id, column and value rows)
  deniedPct:  (in veterans-representation-values.csv, as id, column and value rows)
  otherPct:  (in veterans-representation-values.csv, as id, column and value rows)
  shareOfLegacyPct:  (in veterans-representation-values.csv, as id, column and value rows)
  effectiveTo: When it stopped applying; empty while current (in veterans-representation-values.csv, as id, column and value rows)
