Vehicle safety complaints by state, make and model year (NHTSA complaint file)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23744214

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Vehicle safety complaints by state, make and model year (NHTSA complaint file), version 1.0.0, https://doi.org/10.5281/zenodo.23744214, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Vehicle safety complaints by state, make and model year (NHTSA complaint file) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23744214

Not legal advice. These are counts of unverified complaints that vehicle owners filed with NHTSA, kept for research and marketing planning. A complaint is not a finding that a vehicle is defective, and a count says nothing about whether any owner has a lemon-law or injury claim. Rights and deadlines are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/vehicle-complaints/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the complainant's state or territory, or US (national records and complaints with no U.S. state)
  level: us, state, state-not-given (complaints whose state is blank, military mail or outside the states and territories), make (one make in one state) or us-make (one make nationally)
  stateName: State or territory name
  make: Vehicle make as NHTSA writes it (FORD, HONDA, TESLA ...); empty on state and US totals
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Complaints (same as complaints)
  unit: Unit of value
  complaints: Vehicle safety complaints about the model years in the window, counted once per ODI number however many components they name
  crash: Complaints that report a crash
  fire: Complaints that report a fire
  injury: Complaints that report at least one person injured
  death: Complaints that report at least one death
  injured: People reported injured in those complaints (a value of 99, the field's maximum, is treated as unknown and left out)
  died: People reported killed in those complaints (99 treated as unknown, as for injured)
  recalled: Complaints about a make, model and model year that has at least one NHTSA vehicle recall campaign
  recalled_component: Complaints about a make, model and model year with a recall campaign for one of the component groups the complaint names
  last_12m: Complaints NHTSA received in the twelve months before the file date
  modelYearsFrom: First model year in the window
  modelYearsTo: Last model year in the window (next year's models, on sale from the autumn)
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
