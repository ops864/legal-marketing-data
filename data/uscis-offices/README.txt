USCIS naturalization and green card applications by field office

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23753086

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, USCIS naturalization and green card applications by field office, version 1.0.0, https://doi.org/10.5281/zenodo.23753086, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). USCIS naturalization and green card applications by field office (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23753086

Not legal advice. These are counts of applications that USCIS received and decided at each office, not the outcome of any one case or a prediction of one: a pending count says how many applications are waiting, not how long yours will wait or where it will be decided. Questions about an immigration case are for a licensed immigration attorney or an accredited representative.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/uscis-offices/

Columns:
  id: Stable record id: dataset, place and period
  jurisdiction: Two-letter code of the state or territory the office sits in, or US (the nationwide record, and the two centres USCIS lists without a state)
  officeCode: USCIS's own three-letter office code (US for the nationwide record)
  officeName: Office name as USCIS prints it (the I-485 file's spelling where the two files differ)
  officeType: field-office, service-center, national-benefits-center or us
  stateName: State or territory name
  fiscalYear: Federal fiscal year (October 1 to September 30) of the quarter
  quarter: Fiscal quarter 1 to 4 (Q1 is October to December)
  periodStart: First day of the quarter
  periodEnd: Last day of the quarter
  status: P: read from the primary source
  effectiveFrom: Same as periodStart
  effectiveTo: Same as periodEnd
  text: One plain sentence with the office's counts
  value: N-400 and I-485 applications received in the quarter (the totals columns added); counts only
  unit: What value counts
  n400_gen_rec: Applications received in the quarter, Form N-400, general naturalization
  n400_gen_app: Applications approved in the quarter, Form N-400, general naturalization
  n400_gen_den: Applications denied in the quarter, Form N-400, general naturalization
  n400_gen_pen: Applications pending at the end of the quarter, Form N-400, general naturalization
  n400_mil_rec: Applications received in the quarter, Form N-400, military naturalization
  n400_mil_app: Applications approved in the quarter, Form N-400, military naturalization
  n400_mil_den: Applications denied in the quarter, Form N-400, military naturalization
  n400_mil_pen: Applications pending at the end of the quarter, Form N-400, military naturalization
  n400_tot_rec: Applications received in the quarter, Form N-400, all naturalization (general plus military)
  n400_tot_app: Applications approved in the quarter, Form N-400, all naturalization (general plus military)
  n400_tot_den: Applications denied in the quarter, Form N-400, all naturalization (general plus military)
  n400_tot_pen: Applications pending at the end of the quarter, Form N-400, all naturalization (general plus military)
  i485_fam_rec: Applications received in the quarter, Form I-485, family-based
  i485_fam_app: Applications approved in the quarter, Form I-485, family-based
  i485_fam_den: Applications denied in the quarter, Form I-485, family-based
  i485_fam_pen: Applications pending at the end of the quarter, Form I-485, family-based
  i485_emp_rec: Applications received in the quarter, Form I-485, employment-based (received at service centres)
  i485_emp_app: Applications approved in the quarter, Form I-485, employment-based (received at service centres)
  i485_emp_den: Applications denied in the quarter, Form I-485, employment-based (received at service centres)
  i485_emp_pen: Applications pending at the end of the quarter, Form I-485, employment-based (received at service centres)
  i485_hum_rec: Applications received in the quarter, Form I-485, humanitarian-based (asylee, refugee, Indochinese, Cuban)
  i485_hum_app: Applications approved in the quarter, Form I-485, humanitarian-based (asylee, refugee, Indochinese, Cuban)
  i485_hum_den: Applications denied in the quarter, Form I-485, humanitarian-based (asylee, refugee, Indochinese, Cuban)
  i485_hum_pen: Applications pending at the end of the quarter, Form I-485, humanitarian-based (asylee, refugee, Indochinese, Cuban)
  i485_oth_rec: Applications received in the quarter, Form I-485, other categories (for example crime and trafficking victims)
  i485_oth_app: Applications approved in the quarter, Form I-485, other categories (for example crime and trafficking victims)
  i485_oth_den: Applications denied in the quarter, Form I-485, other categories (for example crime and trafficking victims)
  i485_oth_pen: Applications pending at the end of the quarter, Form I-485, other categories (for example crime and trafficking victims)
  i485_tot_rec: Applications received in the quarter, Form I-485, all categories
  i485_tot_app: Applications approved in the quarter, Form I-485, all categories
  i485_tot_den: Applications denied in the quarter, Form I-485, all categories
  i485_tot_pen: Applications pending at the end of the quarter, Form I-485, all categories
  suppressedFields: Fields USCIS printed as D (disclosure standards not met), left empty here and never estimated
  lastChecked: Date the source file was last read
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
