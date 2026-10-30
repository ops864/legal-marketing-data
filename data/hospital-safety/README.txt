Hospital patient-safety ratings by state and county: PSI 90 and healthcare-associated infections (CMS Care Compare)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23792821

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Hospital patient-safety ratings by state and county: PSI 90 and healthcare-associated infections (CMS Care Compare), version 1.0.0, https://doi.org/10.5281/zenodo.23792821, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Hospital patient-safety ratings by state and county: PSI 90 and healthcare-associated infections (CMS Care Compare) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23792821

Not legal advice. These are CMS ratings of hospitals against a national benchmark, computed from claims and infection reports. They are not findings about the care any patient received, and a rating of worse than the benchmark does not mean an error occurred. Claims and deadlines for a hospital injury are for your own counsel.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/hospital-safety/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state or territory code
  level: state, county or small-counties
  stateName: 
  county: Five-digit county FIPS code
  countyName: County name
  status: P: CMS's own published figure
  text: The record in one plain-English sentence
  value: Hospitals in Care Compare (the same as hospitals)
  unit: Unit of value
  hospitals: Hospitals in the CMS Care Compare hospital file
  counties: On small-counties records: the number of counties combined
  psi90_rated: Hospitals with a PSI 90 rating against the national benchmark
  psi90_worse: Hospitals rated worse than the national benchmark on PSI 90
  psi90_same: Hospitals rated no different on PSI 90
  psi90_better: Hospitals rated better on PSI 90
  cms_psi90_worse: State records: CMS's own state count of hospitals worse on PSI 90
  cms_psi90_same: State records: CMS's state count no different
  cms_psi90_better: State records: CMS's state count better
  cms_psi90_too_few: State records: CMS's state count with too few cases
  hai_rated: Hospital infection ratings (six measures) against the national benchmark
  hai_worse: Hospital infection ratings worse than the benchmark
  hai_same: Hospital infection ratings no different
  hai_better: Hospital infection ratings better
  hai1_sir: State standardized infection ratio, central line bloodstream infections (1.0 is the national benchmark)
  hai1_lower: Lower 95% confidence limit of the ratio (hai2 to hai6 likewise)
  hai1_upper: Upper 95% confidence limit of the ratio (hai2 to hai6 likewise)
  hai2_sir: State ratio, catheter-associated urinary tract infections
  hai2_lower: 
  hai2_upper: 
  hai3_sir: State ratio, colon surgery site infections
  hai3_lower: 
  hai3_upper: 
  hai4_sir: State ratio, abdominal hysterectomy site infections
  hai4_lower: 
  hai4_upper: 
  hai5_sir: State ratio, MRSA bloodstream infections
  hai5_lower: 
  hai5_upper: 
  hai6_sir: State ratio, C. difficile infections
  hai6_lower: 
  hai6_upper: 
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  effectiveTo: When it stopped applying; empty while current
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
