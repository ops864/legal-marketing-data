Consumer product recalls by year and hazard (CPSC recall notices)

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23779145

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Consumer product recalls by year and hazard (CPSC recall notices), version 1.0.0, https://doi.org/10.5281/zenodo.23779145, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Consumer product recalls by year and hazard (CPSC recall notices) (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23779145

Not legal advice. These are counts of recall notices published by the Consumer Product Safety Commission, kept for research and market sizing. A recall is not a finding that a product caused any harm to any person, and it says nothing about whether anyone has a claim; deadlines for injury claims differ by state. Questions about an injury are for a licensed attorney.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/product-recalls/

Columns:
  id: Stable record id (never reused)
  jurisdiction: US (every record is national)
  level: us (the whole period), year (one recall year) or hazard (one hazard class)
  year: Recall year, on year records
  hazard: Hazard class key, on hazard records
  hazardLabel: Hazard class name, on hazard records
  yearsFrom: First recall year kept
  yearsTo: Last recall year kept (the current year is partial)
  dataThrough: Date of the latest recall announcement read
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Same as recalls
  unit: What the value counts
  recalls: Recalls CPSC announced (one per recall notice)
  injury_recalls: Recalls whose notice reports at least one injury (parsed from the notice's incident text; a lower bound, because a notice may describe harm in words the parser does not read as an injury)
  death_recalls: Recalls whose notice reports at least one death (parsed from the notice's incident text)
  units_parsed: Units the notices give, summed over the recalls that state a number (parsed; the notices usually round them)
  units_recalls: Recalls that state a unit count
  hazard_fire_burn: Recalls whose notice names this hazard: Fire, burn and overheating
  hazard_fall_tipover: Recalls whose notice names this hazard: Falls and tip-overs
  hazard_laceration: Recalls whose notice names this hazard: Laceration, cut and amputation
  hazard_choking_suffocation: Recalls whose notice names this hazard: Choking, suffocation and strangulation
  hazard_ingestion: Recalls whose notice names this hazard: Ingestion (magnets, batteries, small parts)
  hazard_entrapment_crush: Recalls whose notice names this hazard: Entrapment, entanglement and pinch injuries
  hazard_electric_shock: Recalls whose notice names this hazard: Electric shock and electrocution
  hazard_poisoning_chemical: Recalls whose notice names this hazard: Poisoning, lead and chemical exposure
  hazard_crash_collision: Recalls whose notice names this hazard: Crash, collision and loss of control
  hazard_drowning: Recalls whose notice names this hazard: Drowning
  hazard_other_hazard: Recalls whose hazard text matches none of the named classes
  recalls_2010: Recalls announced in 2010
  recalls_2011: Recalls announced in 2011
  recalls_2012: Recalls announced in 2012
  recalls_2013: Recalls announced in 2013
  recalls_2014: Recalls announced in 2014
  recalls_2015: Recalls announced in 2015
  recalls_2016: Recalls announced in 2016
  recalls_2017: Recalls announced in 2017
  recalls_2018: Recalls announced in 2018
  recalls_2019: Recalls announced in 2019
  recalls_2020: Recalls announced in 2020
  recalls_2021: Recalls announced in 2021
  recalls_2022: Recalls announced in 2022
  recalls_2023: Recalls announced in 2023
  recalls_2024: Recalls announced in 2024
  recalls_2025: Recalls announced in 2025
  recalls_2026: Recalls announced in 2026 (partial year)
  effectiveFrom: First day of the first recall year kept
  effectiveTo: Date of the latest recall announcement read
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
