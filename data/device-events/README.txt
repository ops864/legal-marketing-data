Medical device adverse event reports by product code and quarter (FDA MAUDE via openFDA)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23752988

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Medical device adverse event reports by product code and quarter (FDA MAUDE via openFDA), version 1.0.0, https://doi.org/10.5281/zenodo.23752988, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Medical device adverse event reports by product code and quarter (FDA MAUDE via openFDA) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23752988

Not legal advice. A report to the FDA is an allegation that a device may have caused or contributed to an event, not a finding that it did, and a count of reports is not an incidence rate or proof of a defect. Questions about an injury from a medical device are for a licensed product-liability attorney and the person's doctor.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/device-events/

Columns:
  id: Stable record id: dataset, place and period
  jurisdiction: US for every record (the data are national)
  level: product-code or us (all device product codes together)
  productCode: FDA's three-letter device product code (empty for the national record)
  deviceName: Device name for the product code from the FDA classification database
  specialty: FDA medical specialty of the product code
  deviceClass: FDA device class (1, 2, 3, or the code U/N where the FDA lists none)
  quarter: Calendar quarter of the date the FDA received the report, such as 2026Q2
  year: Calendar year of the quarter
  qtr: Quarter number 1 to 4
  periodStart: First day of the quarter
  periodEnd: Last day of the quarter
  status: P: counted from the primary source
  text: One plain sentence with the quarter's counts
  value: Same as reports
  unit: What value counts
  reports: Adverse event reports (MDRs) the FDA received in the quarter for the product code; counted once per report that lists the code
  deaths: Reports whose event type is Death
  injuries: Reports whose event type is Injury
  malfunctions: Reports whose event type is Malfunction
  other: reports less deaths, injuries and malfunctions: Other, No answer provided, and the few reports with no event type
  effectiveFrom: Same as periodStart
  effectiveTo: Same as periodEnd
  lastChecked: Date the openFDA API was last read
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
