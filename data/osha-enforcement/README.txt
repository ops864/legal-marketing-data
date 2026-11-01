OSHA inspections and penalties by state and industry (DOL enforcement data)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23850661

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, OSHA inspections and penalties by state and industry (DOL enforcement data), version 1.0.0, https://doi.org/10.5281/zenodo.23850661, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). OSHA inspections and penalties by state and industry (DOL enforcement data) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23850661

Not legal advice. These are Department of Labor enforcement counts for planning. They describe agency activity, not how safe any employer is, and name no employer.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/osha-enforcement/

Columns:
  id: Stable record id (never reused)
  jurisdiction: US or the two-letter state or territory code
  level: us, state or industry (a state or the US within one NAICS sector)
  area: US, the state code, or <state code>-<NAICS sector> such as TX-23
  areaName: Area name
  sector: NAICS two-digit sector (all for whole-state rows; unclassified when the file gave none)
  sectorName: 
  year: The latest federal fiscal year (October to September) in the file
  fiscalYears: The ten-fiscal-year window of the 10y columns
  status: P published; the latest year is marked preliminary because citations can follow inspections for up to six months
  inspections: OSHA inspections opened in the latest fiscal year (federal and state-plan)
  inspections10y: The same, summed over the ten-year window
  inspectionsWithCitations: Inspections that ended with at least one citation
  inspectionsWithCitations10y: 
  violations: Citation items issued on inspections opened in the year
  violations10y: 
  serious: Of the violations, classified serious
  serious10y: 
  willful: Of the violations, classified willful
  willful10y: 
  repeat: Of the violations, classified repeat
  repeat10y: 
  currentPenalties: Current penalties in US dollars: the amount after later contest and settlement changes, as the DOL file reports it
  currentPenalties10y: 
  text: The record in one plain-English sentence
  unit: Unit of value
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
