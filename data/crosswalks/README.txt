Legal market crosswalks: practice areas, federal case codes, states, federal districts and counties

Version 1.1.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23744618

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Legal market crosswalks: practice areas, federal case codes, states, federal districts and counties, version 1.1.0, https://doi.org/10.5281/zenodo.23744618, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Legal market crosswalks: practice areas, federal case codes, states, federal districts and counties (Version 1.1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23744618

Not legal advice. This is a reference table of public codes and boundaries, kept for research and marketing planning. Which court hears a case depends on more than a county line; check the statute and the court's own rules.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/crosswalks/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code the record belongs to, or US for the national tables (practice areas, case codes, datasets, special keys)
  table: STATE, DISTRICT, COUNTY, FORMER (a county code no longer current that older sources still use), ALIAS (another code a source uses for a place that has a key here), SPECIAL (a code a source uses that is not a U.S. place), PRACTICE, NOS (federal nature-of-suit code) or DATASET
  code: The record's key in its table: a postal code, a district key (CAC, NYS), a 5-digit county FIPS code, a source's alias or special code (WQ, OTHER), a practice-area id, a 3-digit nature-of-suit code or a dataset id
  name: Name in English
  nameEs: Name in Spanish (county names are proper names and stay as the Census Bureau writes them)
  status: P read from the primary source; S secondary: a nature-of-suit code no longer on the current U.S. Courts list (kept for older cases), a Virginia independent city placed by 28 U.S.C. 127(c) using the U.S. Courts county lists, or a former county code in a multi-district state placed by the district of its successors; D Probative's own classification (practice areas and dataset links)
  text: The record in one plain-English sentence
  value: STATE and COUNTY: residents on July 1, 2025 (Census estimate), or on April 1, 2020 (2020 Census) for Guam, the Virgin Islands, the Northern Mariana Islands and American Samoa, which have no annual estimates (the unit says which); empty for Midway, which the Census Bureau does not count; DISTRICT: residents of its counties; empty for the other tables
  unit: Unit of value
  fips: STATE: the 2-digit state FIPS code
  state: Postal code of the state the district or county is in
  district: COUNTY and FORMER: the federal judicial district it belongs to, as a district key (the form the civil-filings, idb-civil and mdl datasets use); empty for American Samoa, which has no federal district court
  districtDivision: COUNTY: the statutory division of the district, where the statute divides it
  circuit: Federal court of appeals circuit (28 U.S.C. section 41)
  cbsa: COUNTY: the 2023 core-based statistical area code (metro or micro area); empty outside any
  cbsaTitle: COUNTY: the metro or micro area's name
  cbsaType: COUNTY: metro or micro
  region: STATE: Census region
  division: STATE: Census division
  districts: STATE: the federal judicial districts in it (the U.S. Minor Outlying Islands: the District of Hawaii, 48 U.S.C. 644a)
  territory: STATE: true for Puerto Rico, Guam, the U.S. Virgin Islands, the Northern Mariana Islands, American Samoa and the U.S. Minor Outlying Islands
  successors: FORMER: the current county FIPS codes that took the former county's area (from the Census change pages or, for Connecticut, the Census planning-region crosswalk)
  target: ALIAS: the postal code of the place the alias stands for
  kind: SPECIAL: what the code is (military mail, freely associated state, court code, unplaced)
  idbCode: DISTRICT: the Federal Judicial Center Integrated Database circuit and district code
  ecfId: DISTRICT: the district court's CM/ECF id (ecf.<id>.uscourts.gov), the id CourtListener also uses; empty if the host does not resolve
  bankruptcyEcfId: DISTRICT: the bankruptcy court's CM/ECF id; empty where the territorial district court hears bankruptcy cases
  parent: PRACTICE: the parent practice area; empty for a top-level area
  level: PRACTICE: 1 top-level, 2 sub-area
  sitePractice: PRACTICE: the practice page family on probativegrowth.com it feeds
  folioIri: PRACTICE: the FOLIO Area of Law class it maps to (folio.openlegalstandard.org; FOLIO data is CC BY 4.0)
  folioMatch: PRACTICE: exact, close, broad (FOLIO's class is wider) or narrow
  nos: PRACTICE: federal civil nature-of-suit codes whose cases belong to it
  naics: PRACTICE: the NAICS industry code of the firms that practise it
  practices: NOS and DATASET: the practice areas linked to the code or measured by the dataset
  dimensions: DATASET: what it measures: demand, supply, rules or money
  doi: DATASET: the dataset's current version DOI
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
