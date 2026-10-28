Federal criminal cases by offense and district (U.S. Courts Tables D-1, D-2 and D-3)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23744206

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Federal criminal cases by offense and district (U.S. Courts Tables D-1, D-2 and D-3), version 1.0.0, https://doi.org/10.5281/zenodo.23744206, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Federal criminal cases by offense and district (U.S. Courts Tables D-1, D-2 and D-3) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23744206

Not legal advice. These are counts of defendants in federal criminal cases, kept for research and marketing planning. A defendant counted here is charged, not convicted, and the counts say nothing about any person or case. Questions about a charge are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/criminal-filings/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter code of the state or territory the district sits in, or US
  level: district (one federal judicial district), state (the sum of a state's districts; only states with more than one) or us (all 94 districts)
  district: Federal district key from the Probative crosswalks (TXS = Southern District of Texas); empty for state and US rows
  districtName: The district's name
  circuit: The court of appeals circuit of the district
  stateName: State or territory name
  periodStart: First day of the 12-month period
  periodEnd: Last day of the 12-month period (June 30 or December 31)
  latest: true for the newest period the Courts have published
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Criminal defendants commenced in the period (same as defendants)
  unit: Unit of value
  defendants: Criminal defendants whose cases were opened in the district in the period, excluding defendants transferred in from another district (Table D-3 Total). One person charged in two cases counts twice.
  prior_year_defendants: The same count for the 12 months ending a year earlier; empty where the Courts did not publish that period (December 2024)
  change_pct: Percent change from prior_year_defendants, one decimal
  drug: Drug offenses (marijuana and all other drugs)
  immigration: Immigration offenses (illegal reentry and all other)
  firearms_explosives: Firearms and explosives offenses
  fraud: Fraud (tax, securities, health care, wire, mail, identity documents and other federal fraud)
  sex_offenses: Sex offenses (sexual abuse, sexually explicit material, sex-offender registry and others)
  traffic: Traffic offenses, including drunk driving, on federal land and roads
  other_offenses: Everything else: violent offenses, property offenses other than fraud, justice-system, general and regulatory offenses
  group_violent: The Courts' offense group: violent offenses (homicide, robbery, assault, kidnapping, carjacking and others); the ten groups add up to defendants
  group_property: The Courts' offense group: property offenses (theft, embezzlement, fraud, forgery and others); the ten groups add up to defendants
  group_drug: The Courts' offense group: drug offenses; the ten groups add up to defendants
  group_firearms_explosives: The Courts' offense group: firearms and explosives offenses; the ten groups add up to defendants
  group_sex_offenses: The Courts' offense group: sex offenses; the ten groups add up to defendants
  group_justice_system: The Courts' offense group: justice-system offenses (obstruction, escape, failure to appear and others); the ten groups add up to defendants
  group_immigration: The Courts' offense group: immigration offenses; the ten groups add up to defendants
  group_general: The Courts' offense group: general offenses (money laundering, bribery, racketeering, extortion and others); the ten groups add up to defendants
  group_regulatory: The Courts' offense group: regulatory offenses (customs, national defense, game and conservation and others); the ten groups add up to defendants
  group_traffic: The Courts' offense group: traffic offenses; the ten groups add up to defendants
  d3_homicide: Table D-3 column 'homicide' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_robbery: Table D-3 column 'robbery' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_assault: Table D-3 column 'assault' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_other_violent: Table D-3 column 'other violent offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_burglary_larceny_theft: Table D-3 column 'burglary, larceny, and theft' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_embezzlement: Table D-3 column 'embezzlement' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_fraud: Table D-3 column 'fraud' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_forgery_counterfeiting: Table D-3 column 'forgery and counterfeiting' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_other_property: Table D-3 column 'other property offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_marijuana: Table D-3 column 'marijuana' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_other_drugs: Table D-3 column 'all other drugs' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_firearms_explosives: Table D-3 column 'firearms and explosives offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_sex_offenses: Table D-3 column 'sex offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_justice_system: Table D-3 column 'justice system offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_illegal_reentry: Table D-3 column 'improper reentry by alien' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_other_immigration: Table D-3 column 'other immigration offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_general: Table D-3 column 'general offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_regulatory: Table D-3 column 'regulatory offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  d3_traffic: Table D-3 column 'traffic offenses' as printed (a dash, meaning none, is 0); the nineteen columns add up to defendants
  felony: Of original proceedings (Table D-1), defendants charged with a felony
  class_a_misdemeanor: Of original proceedings (Table D-1), defendants charged with a Class A misdemeanor
  petty_offense: Of original proceedings (Table D-1), petty-offense defendants assigned to a district judge (most petty offenses go to magistrate judges and are not counted)
  reopens: Reopened cases (Table D-1); defendants = felony + class_a_misdemeanor + petty_offense + reopens
  dui: US rows only: defendants charged with drunk driving (Table D-2, part of traffic)
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
