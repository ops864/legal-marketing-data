Legal ad-platform policy tracker

Version 1.0.1. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23716831

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, Legal ad-platform policy tracker, version 1.0.1, https://doi.org/10.5281/zenodo.23716831, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). Legal ad-platform policy tracker (Version 1.0.1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23716831

Not legal advice. This is a plain-English summary of the platforms' public policy pages, kept for marketing planning, and platforms change their rules often. Check the platform's live page, your state bar's rules and your own counsel before you run an ad.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/platforms/

Columns:
  id: Stable record id (never reused)
  platform: Ad platform key
  policyName: The policy’s name
  policyArea: eligibility, restricted-category, creative, targeting, measurement and the other policy areas
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  ruleState: in-force or testing
  text: The record in one plain-English sentence
  whatToDo: What a law firm should do about it, in one sentence
  appliesTo: The practice areas or uses it applies to, separated by "; " (all = every one)
  effectiveDate: The day the rule took effect (YYYY-MM-DD, or the month), if the platform states it
  lastChanged: The day the platform last changed the rule, if known
  regions: Where it applies, separated by "; "
  sourceUrl: The platform’s policy page
  quote: A short exact quote from the source (25 words or fewer)
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  note: Caveats
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
