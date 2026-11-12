US law firm websites: practices, Spanish, intake, by state, county and practice area

Version 3.2.1. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24148921

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative, US law firm websites: practices, Spanish, intake, by state, county and practice area, version 3.2.1, https://doi.org/10.5281/zenodo.24148921, licensed CC BY 4.0.

Suggested citation:
Probative. (2026). US law firm websites: practices, Spanish, intake, by state, county and practice area (Version 3.2.1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24148921

Not legal advice. These are counts of facts read from law firms' own public websites and from official open registries on the dates shown, kept for research and marketing planning. Each row's coverage says how much of the market it reaches. The counts describe what websites and registries say, not the quality of any firm or lawyer. A firm can ask us to correct its row or to be left out through the data corrections page; we act within 7 days.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/firm-web-census/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code (50 states and DC)
  level: state, state-practice or county (county x practice cells nested in practiceCells)
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: Law firms found (website or registry; counties and cells of 3 or more firms)
  unit: Unit of value
  firms: Law firms found: with a website read, or from an official registry only
  firms_with_website: Of those, firms whose own website we read (the base of every share)
  firms_registry_only: Of those, firms found only in an official open registry (registry facts only)
  coverage_label: sample below coverage_cbp 0.70; at 0.70 or more, registry list when registry rows are the majority, otherwise census
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  county: 5-digit county FIPS code (county rows) (in firm-web-census-values.csv, as id, column and value rows)
  countyName: County name as the Census Bureau writes it (in firm-web-census-values.csv, as id, column and value rows)
  practice: Practice id from the shared practice taxonomy (/data/crosswalks/), for practice rows (in firm-web-census-values.csv, as id, column and value rows)
  cbp_offices: Employer law offices (NAICS 541110) in Census County Business Patterns 2023 for the state or county: the coverage base (in firm-web-census-values.csv, as id, column and value rows)
  coverage_cbp: Coverage: firms found / cbp_offices. Firms and establishments differ (a firm can have several offices; registries include solo practices without employees, which CBP leaves out), so it can pass 1 (in firm-web-census-values.csv, as id, column and value rows)
  est_firms_with_website: Estimated law firms with a website (capture-recapture between the OpenStreetMap and Common Crawl site lists; a rough figure) (in firm-web-census-values.csv, as id, column and value rows)
  coverage_web: Websites read / est_firms_with_website, a rough ratio (in firm-web-census-values.csv, as id, column and value rows)
  share_spanish: Percent of the firm websites read with Spanish-language pages (hreflang, a page read in Spanish or a link labelled Español); given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  share_intake247: Percent of the firm websites read with a 24/7 intake statement on the pages read (for example 'available 24/7'); given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  share_structured: Percent of the firm websites read whose pages carry schema.org LegalService or Attorney structured data; given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  share_free_consult: Percent of the firm websites read stating a free consultation (or free case review); given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  share_contingency: Percent of the firm websites read stating no fee unless they win, or a contingency fee; given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  share_chat: Percent of the firm websites read with a chat tool on the site; given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  share_booking: Percent of the firm websites read with an online booking tool linked or embedded; given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  share_reviews_schema: Percent of the firm websites read whose pages carry review or rating structured data (schema.org Review or AggregateRating); given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  share_llms: Percent of the firm websites read publishing an llms.txt file; given for groups of 5 or more firms (in firm-web-census-values.csv, as id, column and value rows)
  median_practice_pages: Practice rows: median number of sitemap pages about the practice per firm, among firms whose sitemap was read (in firm-web-census-values.csv, as id, column and value rows)
  firms_with_sitemap: Practice rows: firms whose sitemap could be read (the base of the median) (in firm-web-census-values.csv, as id, column and value rows)
  practiceCells: County rows: one cell per practice advertised by at least 3 firms with an office in the county: firms, the shares and median_practice_pages (cells under 3 firms are left out) (in firm-web-census-values.csv, as id, column and value rows)
  registries: State rows: the official open registries used for the state (in firm-web-census-values.csv, as id, column and value rows)
  firms_listed: State rows: candidate sites listed for the state in the open sources before reading (web-graph candidates carry no state and are not included) (in firm-web-census-values.csv, as id, column and value rows)
