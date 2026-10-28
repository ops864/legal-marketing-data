Mass-tort docket tracker, federal MDL pending actions by month since 2019

Version 1.1.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23720737

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Mass-tort docket tracker, federal MDL pending actions by month since 2019, version 1.1.0, https://doi.org/10.5281/zenodo.23720737, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Mass-tort docket tracker, federal MDL pending actions by month since 2019 (Version 1.1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23720737

Not legal advice. These are counts from the court's published statistics, kept for marketing planning. Counts change monthly; check the Judicial Panel on Multidistrict Litigation's current report.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/research/mass-tort-mdl-tracker/

Columns:
  id: Stable record id (never reused)
  mdl: The MDL docket number, e.g. MDL-2738
  title: The docket title as the court prints it
  district: The transferee district (two-letter state code of the district court)
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  value: The machine value (see unit)
  unit: Unit of value
  totalActions: Every action ever part of the MDL
  change365d: Change in pending actions against the report about a year earlier
  compareDate365d: The date of that earlier report (YYYY-MM-DD)
  docketType: The court's docket type (for example Products Liability, Antitrust); blank for MDLs not in the 2026-10-01 Docket Type Summary
  dateClosed: The date the court closed the MDL (YYYY-MM-DD); blank while the MDL is pending
  peakPending: The highest pending count in the monthly reports since February 2019 (value, for a closed MDL)
  effectiveFrom: When the fact took effect (YYYY-MM-DD), if known
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
