# Installing the Probative legal-marketing data MCP server

Published by [Probative Growth](https://probativegrowth.com/), a marketing agency for US law firms (SEO and ads, at published monthly prices). Prices: [probativegrowth.com/pricing](https://probativegrowth.com/pricing/) · About: [probativegrowth.com/about](https://probativegrowth.com/about/)

This is a remote MCP server. There is nothing to download, build or configure: no API key, no account, no environment variables.

- Transport: Streamable HTTP
- URL: https://probativegrowth.com/mcp
- Auth: none (read-only)
- Registry name: com.probativegrowth/legal-marketing-data

## Steps

1. Add the server to the MCP settings of the client, with the name `probative` and the URL above. For clients that use `mcpServers` (Cursor, Claude Desktop through a remote-server setting):

```json
{ "mcpServers": { "probative": { "url": "https://probativegrowth.com/mcp" } } }
```

   Cline (`cline_mcp_settings.json`) needs the transport named, or it assumes the older SSE: `{ "mcpServers": { "probative": { "type": "streamableHttp", "url": "https://probativegrowth.com/mcp" } } }`. Windsurf: `{ "mcpServers": { "probative": { "serverUrl": "https://probativegrowth.com/mcp" } } }`. VS Code (`.vscode/mcp.json`): `{ "servers": { "probative": { "type": "http", "url": "https://probativegrowth.com/mcp" } } }`. Claude Code: `claude mcp add --transport http probative https://probativegrowth.com/mcp`. Gemini CLI: `gemini mcp add --transport http probative https://probativegrowth.com/mcp`.
2. Reload the client's MCP servers.
3. Check it works: call the tool `list_datasets` (no arguments). It returns every dataset with its version and DOI.
4. Try a lookup: `get_state_rules` with `{"state": "TX"}` returns Texas's lawyer advertising rules, each with its source.

## Smaller servers, one per dataset

- `https://probativegrowth.com/mcp/rules`: Lawyer advertising rules for all 50 states and DC, each with its source and status.
- `https://probativegrowth.com/mcp/attorneys`: Attorneys by county for OH, CA, MI, ID, AZ, WA and PA from each bar's public counts, per 10,000 residents, with status and as-of date.
- `https://probativegrowth.com/mcp/aviation-accidents`: NTSB civil aviation accidents by state and year, 2008 to 2026: accidents, deaths, injuries and type of operation.
- `https://probativegrowth.com/mcp/bankruptcy`: Bankruptcy filings by chapter, court district, state and county, quarterly from U.S. Courts tables F-5A, F-2 and F.
- `https://probativegrowth.com/mcp/bar-pipeline`: New lawyers by jurisdiction: bar exam pass rates and admissions, 2025.
- `https://probativegrowth.com/mcp/benchmarks`: Probative's law-firm marketing benchmarks, aggregated and rounded.
- `https://probativegrowth.com/mcp/boating-accidents`: USCG recreational boating incidents by state and year, 2019 to 2024: incidents, deaths, injuries and damage in dollars.
- `https://probativegrowth.com/mcp/business-applications`: Census new business applications by county, 2005-2025: latest count, change over a year and since 2019, state sums.
- `https://probativegrowth.com/mcp/ca-courts`: Cases filed in each California county's superior court, by case type.
- `https://probativegrowth.com/mcp/charge-deadlines`: Deadlines to file an employment-discrimination charge, federal and by state, with the statute and verbatim quote.
- `https://probativegrowth.com/mcp/civil-filings`: Federal civil filings by nature of suit and district since 2018.
- `https://probativegrowth.com/mcp/consumer-complaints`: CFPB complaints about debt collection, credit reporting and debt management, by state and month since 2018.
- `https://probativegrowth.com/mcp/consumer-sentinel`: FTC Consumer Sentinel reports by state: fraud, identity theft and imposter scams per 100,000 people (2024 Data Book).
- `https://probativegrowth.com/mcp/county-income`: IRS income and migration by county: returns, adjusted gross income, change per return, net moves in and out of other states.
- `https://probativegrowth.com/mcp/court-fees`: Small-claims dollar limits by state, with the statute or court page and the verbatim quote.
- `https://probativegrowth.com/mcp/crime-data`: FBI violent and property crime, DUI and drug arrests by county and state, five years, with how many agencies reported.
- `https://probativegrowth.com/mcp/criminal-filings`: Federal criminal defendants by offense and district, U.S. Courts Tables D-1 to D-3, every half-year since 2017.
- `https://probativegrowth.com/mcp/crosswalks`: Join keys for every dataset: practice areas, federal case codes, states, federal districts and counties.
- `https://probativegrowth.com/mcp/deserts`: Law offices and lawyers per resident in every US county (legal deserts).
- `https://probativegrowth.com/mcp/device-events`: FDA medical device adverse event reports by product code and quarter: reports, deaths, injuries, malfunctions (top 300 codes).
- `https://probativegrowth.com/mcp/disability-hearings`: SSA disability hearing waits, cases pending and processing times by hearing office.
- `https://probativegrowth.com/mcp/drug-events`: FDA FAERS drug adverse event reports by active ingredient and quarter: serious, deaths, top reactions, MDL tags.
- `https://probativegrowth.com/mcp/eeoc-charges`: EEOC workplace-discrimination charges by state and basis, FY2009 to FY2025.
- `https://probativegrowth.com/mcp/eviction-laws`: Eviction laws of every state, DC and five territories (Jan. 2021): notice, cure, just cause, late fees, timing, with the statute.
- `https://probativegrowth.com/mcp/evictions`: Eviction filings by county and year from LSC's Civil Court Data Initiative, with filings per 100 renter households.
- `https://probativegrowth.com/mcp/fair-housing`: HUD fair housing cases filed 2006 to June 2020 by state, county and basis (race, disability, familial status and more).
- `https://probativegrowth.com/mcp/fatal-crashes`: NHTSA fatal crashes by county since 2019: trucks, motorcycles, pedestrians and bicyclists.
- `https://probativegrowth.com/mcp/federal-filings-county`: Federal civil cases filed by plaintiff county, state, district and case type, ten years, with out-of-state totals.
- `https://probativegrowth.com/mcp/fees`: Attorney fee caps and contingency-fee limits by state and federal program, plus a fee-cap calculator.
- `https://probativegrowth.com/mcp/filing`: What each state bar charges and requires to file or review lawyer ads.
- `https://probativegrowth.com/mcp/findings`: Headline US legal-market counts, each with its denominator, limits and source dataset DOI.
- `https://probativegrowth.com/mcp/firm-web-census`: US law firms by state, county and practice: firms per practice, Spanish pages, 24/7 intake, coverage vs Census counts.
- `https://probativegrowth.com/mcp/green-cards`: New green cards (lawful permanent residents) in the top 200 counties by class of admission and country of birth, with state totals.
- `https://probativegrowth.com/mcp/hospital-safety`: CMS Care Compare hospital patient-safety (PSI 90) and infection ratings by state and county, rated against the national benchmark.
- `https://probativegrowth.com/mcp/idb-civil`: Federal civil case outcomes (FJC IDB): time to disposition, how cases end, class actions and pro se share, by district and type.
- `https://probativegrowth.com/mcp/immigration-courts`: Immigration court backlog, representation and asylum outcomes by state and court, from EOIR workload statistics and case data.
- `https://probativegrowth.com/mcp/irs-databook`: IRS Data Book by state, fiscal years 2019 to 2025: returns filed, gross collections and refunds issued.
- `https://probativegrowth.com/mcp/language`: Spanish speakers with limited English per Spanish-speaking lawyer, by state and metro.
- `https://probativegrowth.com/mcp/law-firm-economy`: Law firms by size and state (Census SUSB, Nonemployer Statistics, Economic Census): firm counts, receipts and solo practices.
- `https://probativegrowth.com/mcp/law-offices`: Law offices, jobs and pay by county, with solo-practice counts (BLS, Census).
- `https://probativegrowth.com/mcp/lawyer-wages`: Lawyer and paralegal pay by state and metro from BLS OEWS: employment, mean and median wages and percentiles.
- `https://probativegrowth.com/mcp/legal-aid-orgs`: Legal-aid, public-interest-law and civil-rights nonprofits per county, state and US, by type and revenue band (IRS EO BMF).
- `https://probativegrowth.com/mcp/legal-need`: Who may need a lawyer in every US county (Census ACS): 65+, noncitizens, LEP, divorced, veterans, renters.
- `https://probativegrowth.com/mcp/legal-prices`: Legal-services prices and jobs, monthly from BLS: the CPI and PPI legal-services indexes and legal-services employment.
- `https://probativegrowth.com/mcp/limitations`: Statutes of limitations by state for five kinds of civil claim, quoted from the code.
- `https://probativegrowth.com/mcp/mdl`: Pending actions in every federal MDL, monthly since 2019.
- `https://probativegrowth.com/mcp/mine-accidents`: MSHA mine accident, injury and illness reports by state, county and degree of injury, 2000 to 2026, coal and metal/nonmetal.
- `https://probativegrowth.com/mcp/mortgage-lending`: HMDA home-purchase and refinance applications, loans, dollars and denial rates by county, state and US.
- `https://probativegrowth.com/mcp/nursing-homes`: Nursing home fines, harm and abuse citations by county and state, from CMS, monthly.
- `https://probativegrowth.com/mcp/ny-attorneys`: New York attorneys by county of office, registration status and admission decade, per 10,000 residents, from the court registry.
- `https://probativegrowth.com/mcp/ny-workers-comp`: New York workers' compensation claims by county and accident year: attorney share, controverted, hearings, permanent disability.
- `https://probativegrowth.com/mcp/opinions`: State and ABA ethics opinions on lawyer advertising and marketing, 2015 to 2026.
- `https://probativegrowth.com/mcp/platforms`: Ad-platform policies that touch law-firm ads: Google, Microsoft, Meta, LinkedIn, YouTube, ChatGPT.
- `https://probativegrowth.com/mcp/practice-official`: Official statistics (U.S. Courts, EEOC, EOIR, NHTSA FARS) quoted on the practice x state pages, one sourced sentence per record.
- `https://probativegrowth.com/mcp/product-recalls`: CPSC consumer product recalls by year and hazard class, with the notices that report an injury or a death.
- `https://probativegrowth.com/mcp/rail-casualties`: Railroad casualties, crossing incidents and train accidents by county from FRA Forms 55a, 57 and 54, by who was hurt.
- `https://probativegrowth.com/mcp/referral`: Referral-fee and fee-splitting rules for lawyers, by state.
- `https://probativegrowth.com/mcp/robocall-complaints`: FCC complaints about unwanted calls and texts, by state and month.
- `https://probativegrowth.com/mcp/state-civil-rights`: State civil-rights agency complaint and charge counts with the source document and quote for each figure.
- `https://probativegrowth.com/mcp/state-courts`: State trial-court case filings by county and case type (TX WA MD IN WI VA PA OR WV NE ME CA), by practice area, with county FIPS.
- `https://probativegrowth.com/mcp/state-wage-claims`: State labor agency wage claim counts with the source document and quote for each figure.
- `https://probativegrowth.com/mcp/toxic-releases`: EPA TRI toxic chemical releases by county: facilities, pounds on site, carcinogens, PFAS, benzene, lead, ethylene oxide.
- `https://probativegrowth.com/mcp/truck-crashes`: FMCSA truck and bus crashes by county, state and year: fatal and injury crashes, deaths and injuries, ten years.
- `https://probativegrowth.com/mcp/tx-nonsubscribers`: Texas employers with no workers' compensation coverage (DWC Form-005 filings), counted by county, 2024 to 2026.
- `https://probativegrowth.com/mcp/unemployment`: BLS county and state unemployment rate, unemployed and labor force, annual averages and the latest month.
- `https://probativegrowth.com/mcp/uscis-offices`: USCIS naturalization (N-400) and green card (I-485) applications received, decided and pending, by field office and quarter.
- `https://probativegrowth.com/mcp/va-compensation`: VA disability compensation recipients by county and combined rating (0-20% to 100%), age, sex, FY2025 vs FY2024.
- `https://probativegrowth.com/mcp/va-spending`: VA compensation, pension and survivor benefit dollars by county, FY2025, with the year-earlier change.
- `https://probativegrowth.com/mcp/vehicle-complaints`: NHTSA vehicle safety complaints by state, make, model year and component: crashes, fires, injuries, deaths, recalls.
- `https://probativegrowth.com/mcp/veterans-representation`: VA-accredited attorneys and claims agents per veteran by state, county counts, and appeals outcomes by representation.
- `https://probativegrowth.com/mcp/wage-enforcement`: DOL wage-and-hour back wages and OSHA inspections, violations and penalties by county, state, law and industry, ten years.
- `https://probativegrowth.com/mcp/warn-layoffs`: WARN layoff and closure notices and employees by county and month for California and Texas.
- `https://probativegrowth.com/mcp/wc-benefits`: Workers' compensation maximum weekly benefit by state, with the period, the agency source and the verbatim quote.
- `https://probativegrowth.com/mcp/work-injuries`: Workplace injuries and fatal work injuries by state and industry, from BLS SOII and CFOI: rates, case counts and the riskiest sectors.

## Notes

- Every answer carries its source, version, DOI and a credit line; the data is CC BY 4.0.
- Not legal advice. Probative Growth is a marketing agency, not a law firm.
- Docs: https://probativegrowth.com/resources/rules-api/
