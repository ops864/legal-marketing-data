US law-firm websites and AI crawlers: crawler-file rules, text before JavaScript, snippet limits and Spanish pages, by state and market

Version 1.0.0. CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). DOI https://doi.org/10.5281/zenodo.24015038

Credit line (CC BY 4.0 asks for credit and a link):
Source: Probative Growth, US law-firm websites and AI crawlers: crawler-file rules, text before JavaScript, snippet limits and Spanish pages, by state and market, version 1.0.0, https://doi.org/10.5281/zenodo.24015038, licensed CC BY 4.0.

Suggested citation:
Probative Growth. (2026). US law-firm websites and AI crawlers: crawler-file rules, text before JavaScript, snippet limits and Spanish pages, by state and market (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24015038

Cite as: Probative Growth, US law-firm websites and AI crawlers: crawler-file rules, text before JavaScript, snippet limits and Spanish pages, by state and market, 2026, https://doi.org/10.5281/zenodo.24015038

Not legal advice. These are counts of what law-firm websites' crawler files and raw pages said when read. A rule in such a file is what the file says; it does not show what any AI tool does, and nothing here measures whether a firm appears in AI answers. The counts describe no firm's quality.
Probative is a marketing firm, not a law firm; not legal advice.

Human page: https://probativegrowth.com/data/law-firm-ai-readiness/

Columns:
  id: Stable record id (never reused)
  jurisdiction: Two-letter state code, or US; a market row carries its state's code
  level: us, state or metro (a market on this site, by its core counties)
  areaName: The place the row covers
  status: P primary source, S secondary source
  text: The record in one plain-English sentence
  value: The headline share: % of websites blocking the home page for at least one of the eight AI crawlers and controls
  unit: What value measures
  websites: US law-firm websites read in the group (N); every state and market has at least 100
  robots_read: Websites whose crawler file answer was read: the base of the crawler-file shares
  share_robots_file: % of those with a crawler file holding text
  share_block_any: % blocking the home page for at least one of the eight crawlers
  share_block_gptbot: % whose crawler file blocks the home page for GPTBot (its own group, else the group for all crawlers; longest match wins, an allow wins a tie)
  share_block_oai_searchbot: % whose crawler file blocks the home page for OAI-SearchBot (its own group, else the group for all crawlers; longest match wins, an allow wins a tie)
  share_block_chatgpt_user: % whose crawler file blocks the home page for ChatGPT-User (its own group, else the group for all crawlers; longest match wins, an allow wins a tie)
  share_block_claudebot: % whose crawler file blocks the home page for ClaudeBot (its own group, else the group for all crawlers; longest match wins, an allow wins a tie)
  share_block_claude_user: % whose crawler file blocks the home page for Claude-User (its own group, else the group for all crawlers; longest match wins, an allow wins a tie)
  share_block_perplexitybot: % whose crawler file blocks the home page for PerplexityBot (its own group, else the group for all crawlers; longest match wins, an allow wins a tie)
  share_block_google_extended: % whose crawler file blocks the home page for Google-Extended (its own group, else the group for all crawlers; longest match wins, an allow wins a tie)
  share_block_meta_webindexer: % whose crawler file blocks the home page for meta-webindexer (its own group, else the group for all crawlers; longest match wins, an allow wins a tie)
  share_named_gptbot: % whose crawler file names GPTBot in a User-agent line
  share_named_oai_searchbot: % whose crawler file names OAI-SearchBot in a User-agent line
  share_named_chatgpt_user: % whose crawler file names ChatGPT-User in a User-agent line
  share_named_claudebot: % whose crawler file names ClaudeBot in a User-agent line
  share_named_claude_user: % whose crawler file names Claude-User in a User-agent line
  share_named_perplexitybot: % whose crawler file names PerplexityBot in a User-agent line
  share_named_google_extended: % whose crawler file names Google-Extended in a User-agent line
  share_named_meta_webindexer: % whose crawler file names meta-webindexer in a User-agent line
  apex_read: Websites with an apex and a www host name asked: the base of the host shares
  share_apex_same: % where the other host name redirects to the site's host
  share_apex_split: % where the other host name answers its own page (200, no redirect)
  share_apex_other: % where the other host name gives any other answer (an error status, or a redirect elsewhere)
  share_apex_none: % where the other host name gives no answer (no DNS, no connection or a certificate that fails)
  share_static_under_200: % of websites whose home page shows under 200 characters of visible text in the raw HTML, before JavaScript runs
  median_static_chars: Median characters of visible text on the home page before JavaScript runs
  share_faq_schema: % with FAQPage structured data on the pages read
  share_org_schema: % with Organization, LocalBusiness, LegalService, Attorney or a close type on the pages read
  share_snippet_limit: % with a search meta tag saying nosnippet or max-snippet of 0 or more on the pages read
  share_snippet_unlimited: % with max-snippet:-1 (no limit) on the pages read
  spanish_read: Websites whose Spanish status could be classed from the pages read: the base of the Spanish shares
  share_spanish_own: % with a page read in Spanish whose HTML names no translation service
  share_spanish_machine: % with a page read in Spanish whose HTML names a translation service
  share_spanish_widget: % with a translation widget on the home page and no Spanish page
  share_spanish_none: % with no Spanish page, link or translation widget
  static_threshold_chars: The threshold, in characters of visible text, behind share_static_under_200
  period: First and last read date
  lastChecked: The day it was last confirmed (YYYY-MM-DD)
  sourceLabels: Sources, separated by " | "
  sourceUrls: Source URLs, in the same order
  confidence: high, medium or low: computed from status, a second check, age against the refresh cadence and sampling error (rule: /data/#confidence)
  confidenceBasis: The reasons for the confidence level, in a short phrase
  market: The market's page on this site (market rows) (in law-firm-ai-readiness-values.csv, as id, column and value rows)
