Hospital patient-safety ratings by state and county: PSI 90 and healthcare-associated infections (CMS Care Compare)

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23963670

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, Hospital patient-safety ratings by state and county: PSI 90 and healthcare-associated infections (CMS Care Compare), version 2.0.0, https://doi.org/10.5281/zenodo.23963670, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). Hospital patient-safety ratings by state and county: PSI 90 and healthcare-associated infections (CMS Care Compare) (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23963670

Cite as: Probative Growth, Hospital patient-safety ratings by state and county: PSI 90 and healthcare-associated infections (CMS Care Compare), 2026, https://doi.org/10.5281/zenodo.23963670

Not legal advice. These are CMS ratings of hospitals against a national benchmark, computed from claims and infection reports. They are not findings about the care any patient received, and a rating of worse than the benchmark does not mean an error occurred. Claims and deadlines for a hospital injury are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/hospital-safety/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code
  level: state, county or small-counties
  stateName: 
  status: P: CMS's own published figure
  text: The record in one plain-English sentence
  value: Hospitals in Care Compare (the same as hospitals)
  unit: Unit of value
  hospitals: Hospitals in the CMS Care Compare hospital file
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  county: Five-digit county FIPS code (in hospital-safety-values.csv, as id, column and value rows)
  countyName: County name (in hospital-safety-values.csv, as id, column and value rows)
  counties: On small-counties records: the number of counties combined (in hospital-safety-values.csv, as id, column and value rows)
  psi90_rated: Hospitals with a PSI 90 rating against the national benchmark (in hospital-safety-values.csv, as id, column and value rows)
  psi90_worse: Hospitals rated worse than the national benchmark on PSI 90 (in hospital-safety-values.csv, as id, column and value rows)
  psi90_same: Hospitals rated no different on PSI 90 (in hospital-safety-values.csv, as id, column and value rows)
  psi90_better: Hospitals rated better on PSI 90 (in hospital-safety-values.csv, as id, column and value rows)
  cms_psi90_worse: State records: CMS's own state count of hospitals worse on PSI 90 (in hospital-safety-values.csv, as id, column and value rows)
  cms_psi90_same: State records: CMS's state count no different (in hospital-safety-values.csv, as id, column and value rows)
  cms_psi90_better: State records: CMS's state count better (in hospital-safety-values.csv, as id, column and value rows)
  cms_psi90_too_few: State records: CMS's state count with too few cases (in hospital-safety-values.csv, as id, column and value rows)
  hai_rated: Hospital infection ratings (six measures) against the national benchmark (in hospital-safety-values.csv, as id, column and value rows)
  hai_worse: Hospital infection ratings worse than the benchmark (in hospital-safety-values.csv, as id, column and value rows)
  hai_same: Hospital infection ratings no different (in hospital-safety-values.csv, as id, column and value rows)
  hai_better: Hospital infection ratings better (in hospital-safety-values.csv, as id, column and value rows)
  hai1_sir: State standardized infection ratio, central line bloodstream infections (1.0 is the national benchmark) (in hospital-safety-values.csv, as id, column and value rows)
  hai1_lower: Lower 95% confidence limit of the ratio (hai2 to hai6 likewise) (in hospital-safety-values.csv, as id, column and value rows)
  hai1_upper: Upper 95% confidence limit of the ratio (hai2 to hai6 likewise) (in hospital-safety-values.csv, as id, column and value rows)
  hai2_sir: State ratio, catheter-associated urinary tract infections (in hospital-safety-values.csv, as id, column and value rows)
  hai2_lower:  (in hospital-safety-values.csv, as id, column and value rows)
  hai2_upper:  (in hospital-safety-values.csv, as id, column and value rows)
  hai3_sir: State ratio, colon surgery site infections (in hospital-safety-values.csv, as id, column and value rows)
  hai3_lower:  (in hospital-safety-values.csv, as id, column and value rows)
  hai3_upper:  (in hospital-safety-values.csv, as id, column and value rows)
  hai4_sir: State ratio, abdominal hysterectomy site infections (in hospital-safety-values.csv, as id, column and value rows)
  hai4_lower:  (in hospital-safety-values.csv, as id, column and value rows)
  hai4_upper:  (in hospital-safety-values.csv, as id, column and value rows)
  hai5_sir: State ratio, MRSA bloodstream infections (in hospital-safety-values.csv, as id, column and value rows)
  hai5_lower:  (in hospital-safety-values.csv, as id, column and value rows)
  hai5_upper:  (in hospital-safety-values.csv, as id, column and value rows)
  hai6_sir: State ratio, C. difficile infections (in hospital-safety-values.csv, as id, column and value rows)
  hai6_lower:  (in hospital-safety-values.csv, as id, column and value rows)
  hai6_upper:  (in hospital-safety-values.csv, as id, column and value rows)
