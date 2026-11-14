Attorneys registered with the New York courts, by county, status and year of admission (NYS Office of Court Administration)

Version 2.0.1. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24116050

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Attorneys registered with the New York courts, by county, status and year of admission (NYS Office of Court Administration), version 2.0.1, https://doi.org/10.5281/zenodo.24116050, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Attorneys registered with the New York courts, by county, status and year of admission (NYS Office of Court Administration) (Version 2.0.1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24116050

Cite as: Probative Growth, Attorneys registered with the New York courts, by county, status and year of admission (NYS Office of Court Administration), 2026, https://doi.org/10.5281/zenodo.24116050

Not legal advice. These are counts of attorney registrations from the New York court system's public registration file, kept for research and marketing planning. A registration status is the court's record, not a judgment of any lawyer's skill or standing beyond that record, and a county is the county of the office address the lawyer gave, not where the lawyer practises or where clients live. Rights and deadlines in a matter are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/ny-attorneys/

Columns:
  id: Stable record id (never reused)
  jurisdiction: NY: every record is a New York registration
  level: county (office address in that New York county), county-not-given (an office in New York with no county in the file), address-outside-ny (one per state, territory or military code of an office outside New York), address-not-published (no office address in the public file), department (judicial department of admission) or state (all registrations)
  stateName: New York
  year: Year the court file was last updated
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: Attorneys currently registered in the record's group
  unit: Unit of value
  registered: Registration status Currently registered
  due_to_reregister: Status Due to reregister within 30 days of birthday: still registered, in the window to renew
  active: Currently registered plus those in the 30-day reregistration window
  delinquent: Status Delinquent: registration lapsed
  resigned: Status Resigned (not for disciplinary reasons)
  deceased: Status Deceased
  incapacitated: Status Incapacitated; published from 5 up
  total: All registrations in the record's group, any status
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  county: 5-digit county FIPS code (vintage 2025); empty for other levels (in ny-attorneys-values.csv, as id, column and value rows)
  countyName: County name as the Census Bureau writes it; for department records the department's name (in ny-attorneys-values.csv, as id, column and value rows)
  addressState: Two-letter code of the state, territory or military post office of the office address; NY for county records; empty where no address is published (in ny-attorneys-values.csv, as id, column and value rows)
  addressPlace: Name of that place, address-outside-ny records (in ny-attorneys-values.csv, as id, column and value rows)
  department: Department records: 1, 2, 3 or 4 (the Appellate Division department of admission, not the office location) (in ny-attorneys-values.csv, as id, column and value rows)
  discipline_related: Disbarred, resigned from the bar for a disciplinary reason, or suspended (currently registered, delinquent or due to reregister); published from 5 up (in ny-attorneys-values.csv, as id, column and value rows)
  population: County residents, Census estimate of July 1, 2025 (county records) (in ny-attorneys-values.csv, as id, column and value rows)
  active_per_10k: Active attorneys per 10,000 county residents, one decimal (in ny-attorneys-values.csv, as id, column and value rows)
  admitted_pre1970: Active attorneys admitted to the New York bar before 1970 (published from 5 up); the other admitted_ columns are the decades 1970s to 2020s (in ny-attorneys-values.csv, as id, column and value rows)
  admitted_1970s:  (in ny-attorneys-values.csv, as id, column and value rows)
  admitted_1980s:  (in ny-attorneys-values.csv, as id, column and value rows)
  admitted_1990s:  (in ny-attorneys-values.csv, as id, column and value rows)
  admitted_2000s:  (in ny-attorneys-values.csv, as id, column and value rows)
  admitted_2010s:  (in ny-attorneys-values.csv, as id, column and value rows)
  admitted_2020s:  (in ny-attorneys-values.csv, as id, column and value rows)
  median_admission_year: Median year of admission of the active attorneys (empty below 20 active) (in ny-attorneys-values.csv, as id, column and value rows)
  active_ny_county: State record: active attorneys with an office in a New York county (in ny-attorneys-values.csv, as id, column and value rows)
  active_outside_ny: State record: active attorneys with an office outside New York (in ny-attorneys-values.csv, as id, column and value rows)
  active_address_not_published: State record: active attorneys with no office address in the public file (in ny-attorneys-values.csv, as id, column and value rows)
  note: Caveats (in ny-attorneys-values.csv, as id, column and value rows)
