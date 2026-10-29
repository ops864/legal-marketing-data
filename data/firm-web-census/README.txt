US law firm websites: practices, Spanish, intake, by state, county and practice area

Version 2.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.23750638

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, US law firm websites: practices, Spanish, intake, by state, county and practice area, version 2.0.0, https://doi.org/10.5281/zenodo.23750638, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). US law firm websites: practices, Spanish, intake, by state, county and practice area (Version 2.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23750638

Not legal advice. These are counts of facts read from law firms' own public websites and from official open registries on the dates shown, kept for research and marketing planning. Each row's two coverage measures say how much of the market it reaches. The counts describe what websites and registries say, not the quality of any firm or lawyer. A firm can ask us to correct its row or to be left out through the data corrections page; we act within 7 days.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/firm-web-census/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code (50 states and DC)
  level: state, state-practice or county (county x practice cells nested in practiceCells)
  county: 5-digit county FIPS code (county rows)
  countyName: County name as the Census Bureau writes it
  practice: Practice id from the shared practice taxonomy (/data/crosswalks/), for practice rows
  status: P primary source, S secondary source, D default (no specific rule found), U open question or withheld
  text: The record in one plain-English sentence
  value: Law firms found (website or registry; small groups suppressed)
  unit: Unit of value
  firms: Law firms found: with a website read, or from an official registry only
  firms_with_website: Of those, firms whose own website we read (the base of every share)
  firms_registry_only: Of those, firms found only in an official open registry (no website read)
  cbp_offices: Employer law offices (NAICS 541110) in Census County Business Patterns 2023 for the state or county: the coverage base
  coverage_cbp: Coverage (b): firms found / cbp_offices. Firms and establishments differ (a firm can have several offices; registries include solo practices without employees, which CBP leaves out), so it can pass 1
  est_firms_with_website: Estimated law firms with a website (capture-recapture between the OpenStreetMap and Common Crawl site lists; provisional until the first full pass ends)
  coverage_web: Coverage (a): firms with a website read / est_firms_with_website
  coverage_label: sample, or census once coverage_cbp is 0.70 or more
  share_spanish: Percent of the firm websites read with Spanish-language pages (hreflang, a page read in Spanish or a link labelled Español); withheld under 5 firms
  share_intake247: Percent of the firm websites read with a 24/7 intake statement on the pages read (for example 'available 24/7'); withheld under 5 firms
  share_structured: Percent of the firm websites read whose pages carry schema.org LegalService or Attorney structured data; withheld under 5 firms
  share_free_consult: Percent of the firm websites read stating a free consultation (or free case review); withheld under 5 firms
  share_contingency: Percent of the firm websites read stating no fee unless they win, or a contingency fee; withheld under 5 firms
  share_chat: Percent of the firm websites read with a chat tool on the site; withheld under 5 firms
  share_booking: Percent of the firm websites read with an online booking tool linked or embedded; withheld under 5 firms
  share_reviews_schema: Percent of the firm websites read whose pages carry review or rating structured data (schema.org Review or AggregateRating); withheld under 5 firms
  share_llms: Percent of the firm websites read publishing an llms.txt file; withheld under 5 firms
  median_practice_pages: Practice rows: median number of sitemap pages about the practice per firm, among firms whose sitemap was read
  firms_with_sitemap: Practice rows: firms whose sitemap could be read (the base of the median)
  practiceCells: County rows: one cell per practice advertised by at least 3 firms with an office in the county: firms, the shares and median_practice_pages (cells under 3 firms are left out)
  registries: State rows: the official open registries used for the state
  firms_listed: State rows: candidate sites listed for the state in the open sources before reading (web-graph candidates carry no state and are not included)
  new_entrants_week: Aggregate rows: firms first seen in the latest weekly run (filled once two runs exist)
  exits_week: Aggregate rows: firms not readable in the latest run that were read the week before (filled once two runs exist)
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
