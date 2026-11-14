Legal market crosswalks: practice areas, federal case codes, states, federal districts and counties

Version 2.3.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24181503

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Legal market crosswalks: practice areas, federal case codes, states, federal districts and counties, version 2.3.0, https://doi.org/10.5281/zenodo.24181503, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Legal market crosswalks: practice areas, federal case codes, states, federal districts and counties (Version 2.3.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24181503

Cite as: Probative Growth, Legal market crosswalks: practice areas, federal case codes, states, federal districts and counties, 2026, https://doi.org/10.5281/zenodo.24181503

Not legal advice. This is a reference table of public codes and boundaries, kept for research and marketing planning. Which court hears a case depends on more than a county line; check the statute and the court's own rules.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/crosswalks/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code the record belongs to, or US for the national tables (practice areas, case codes, datasets, special keys)
  table: STATE, DISTRICT, COUNTY, FORMER (a county code no longer current that older sources still use), ALIAS (another code a source uses for a place that has a key here), SPECIAL (a code a source uses that is not a U.S. place), PRACTICE, NOS (federal nature-of-suit code) or DATASET
  code: The record's key in its table: a postal code, a district key (CAC, NYS), a 5-digit county FIPS code, a source's alias or special code (WQ, OTHER), a practice-area id, a 3-digit nature-of-suit code or a dataset id
  name: Name in English
  status: P read from the primary source; S secondary: a nature-of-suit code no longer on the current U.S. Courts list (kept for older cases), a Virginia independent city placed by 28 U.S.C. 127(c) using the U.S. Courts county lists, or a former county code in a multi-district state placed by the district of its successors; D Probative's own classification (practice areas and dataset links)
  text: The record in one plain-English sentence
  unit: Unit of value
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  nameEs: Name in Spanish (county names are proper names and stay as the Census Bureau writes them) (in crosswalks-values.csv, as id, column and value rows)
  value: STATE and COUNTY: residents on July 1, 2025 (Census estimate), or on April 1, 2020 (2020 Census) for Guam, the Virgin Islands, the Northern Mariana Islands and American Samoa, which have no annual estimates (the unit says which); empty for Midway, which the Census Bureau does not count; DISTRICT: residents of its counties; empty for the other tables (in crosswalks-values.csv, as id, column and value rows)
  fips: STATE: the 2-digit state FIPS code (in crosswalks-values.csv, as id, column and value rows)
  state: Postal code of the state the district or county is in (in crosswalks-values.csv, as id, column and value rows)
  district: COUNTY and FORMER: the federal judicial district it belongs to, as a district key (the form the civil-filings, idb-civil and mdl datasets use); empty for American Samoa, which has no federal district court (in crosswalks-values.csv, as id, column and value rows)
  districtDivision: COUNTY: the statutory division of the district, where the statute divides it (in crosswalks-values.csv, as id, column and value rows)
  circuit: Federal court of appeals circuit (28 U.S.C. section 41) (in crosswalks-values.csv, as id, column and value rows)
  cbsa: COUNTY: the 2023 core-based statistical area code (metro or micro area); empty outside any (in crosswalks-values.csv, as id, column and value rows)
  cbsaTitle: COUNTY: the metro or micro area's name (in crosswalks-values.csv, as id, column and value rows)
  cbsaType: COUNTY: metro or micro (in crosswalks-values.csv, as id, column and value rows)
  region: STATE: Census region (in crosswalks-values.csv, as id, column and value rows)
  division: STATE: Census division (in crosswalks-values.csv, as id, column and value rows)
  districts: STATE: the federal judicial districts in it (the U.S. Minor Outlying Islands: the District of Hawaii, 48 U.S.C. 644a) (in crosswalks-values.csv, as id, column and value rows)
  territory: STATE: true for Puerto Rico, Guam, the U.S. Virgin Islands, the Northern Mariana Islands, American Samoa and the U.S. Minor Outlying Islands (in crosswalks-values.csv, as id, column and value rows)
  successors: FORMER: the current county FIPS codes that took the former county's area (from the Census change pages or, for Connecticut, the Census planning-region crosswalk) (in crosswalks-values.csv, as id, column and value rows)
  target: ALIAS: the postal code of the place the alias stands for (in crosswalks-values.csv, as id, column and value rows)
  kind: SPECIAL: what the code is (military mail, freely associated state, court code, unplaced) (in crosswalks-values.csv, as id, column and value rows)
  idbCode: DISTRICT: the Federal Judicial Center Integrated Database circuit and district code (in crosswalks-values.csv, as id, column and value rows)
  ecfId: DISTRICT: the district court's CM/ECF id (ecf.<id>.uscourts.gov), the id CourtListener also uses; empty if the host does not resolve (in crosswalks-values.csv, as id, column and value rows)
  bankruptcyEcfId: DISTRICT: the bankruptcy court's CM/ECF id; empty where the territorial district court hears bankruptcy cases (in crosswalks-values.csv, as id, column and value rows)
  parent: PRACTICE: the parent practice area; empty for a top-level area (in crosswalks-values.csv, as id, column and value rows)
  level: PRACTICE: 1 top-level, 2 sub-area (in crosswalks-values.csv, as id, column and value rows)
  sitePractice: PRACTICE: the practice page family on probativegrowth.com it feeds (in crosswalks-values.csv, as id, column and value rows)
  folioIri: PRACTICE: the FOLIO Area of Law class it maps to (folio.openlegalstandard.org; FOLIO data is CC BY 4.0) (in crosswalks-values.csv, as id, column and value rows)
  folioMatch: PRACTICE: exact, close, broad (FOLIO's class is wider) or narrow (in crosswalks-values.csv, as id, column and value rows)
  nos: PRACTICE: federal civil nature-of-suit codes whose cases belong to it (in crosswalks-values.csv, as id, column and value rows)
  naics: PRACTICE: the NAICS industry code of the firms that practise it (in crosswalks-values.csv, as id, column and value rows)
  practices: NOS and DATASET: the practice areas linked to the code or measured by the dataset (in crosswalks-values.csv, as id, column and value rows)
  dimensions: DATASET: what it measures: demand, supply, rules or money (in crosswalks-values.csv, as id, column and value rows)
  doi: DATASET: the dataset's current version DOI (in crosswalks-values.csv, as id, column and value rows)
  note: Caveats (in crosswalks-values.csv, as id, column and value rows)
