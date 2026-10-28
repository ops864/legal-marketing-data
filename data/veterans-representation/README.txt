VA-accredited attorneys and claims agents per veteran, by state, with county counts and Board of Veterans' Appeals outcomes by type of representation

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23740008

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, VA-accredited attorneys and claims agents per veteran, by state, with county counts and Board of Veterans' Appeals outcomes by type of representation, version 1.0.0, https://doi.org/10.5281/zenodo.23740008, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). VA-accredited attorneys and claims agents per veteran, by state, with county counts and Board of Veterans' Appeals outcomes by type of representation (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23740008

Not legal advice. These are counts of people on the VA's public accreditation lists and of Board of Veterans' Appeals decisions, kept for marketing planning. An accreditation is the VA's permission to help with claims, not an endorsement or a measure of quality, and the counts say nothing about any veteran's claim. Deadlines and fees are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/veterans-representation/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state, DC or territory; US for the United States and the Board's rows; OTHER for people whose list entry shows a blank, military, foreign or unrecognised state
  areaName: Area name
  areaType: us, state, dc, territory, other, or bva (a Board of Veterans' Appeals row)
  state: 
  fips: 
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  value: Accredited attorneys plus accredited claims agents (the people on the VA lists); for a bva row, the Board's decisions in that row
  unit: Unit of value
  attorneys: Attorneys on the VA Office of General Counsel's list whose business address is in the state
  agents: Claims agents on the VA's list whose business address is in the state
  new12m: Attorneys plus agents accredited in the 12 months before the list was read
  veterans: Living veterans the VA projects for the date in veteransDate (VetPop2023), rounded to the nearest 1,000
  veteransDate: 
  veteransPerAttorney: veterans divided by attorneys; empty when there are none
  veteransPerRep: veterans divided by attorneys plus agents
  repsPer100kVeterans: Attorneys plus agents per 100,000 veterans
  countiesTotal: Counties in the VA's county table for the state (empty for Connecticut, Puerto Rico and the island territories)
  countiesWithNone: Counties with no accredited attorney or agent whose business ZIP code falls mostly in the county
  veteransInCountiesWithNone: Veterans in those counties (the VA's county counts, each rounded to 1,000, added up)
  bvaFy: 
  bvaSystem: 
  bvaRepresentation: For a bva row: Agent, Attorney, a veterans service organization, No Representation, or All
  allowed: 
  remanded: 
  denied: 
  other: 
  allowedPct: For a bva row: share of the row's decisions that were allowed (the Board's own percentage)
  remandedPct: 
  deniedPct: 
  otherPct: 
  shareOfLegacyPct: 
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
