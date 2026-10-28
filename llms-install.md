# Installing the Probative legal-marketing data MCP server

Published by [Probative Growth](https://probativegrowth.com/), a marketing agency for US law firms (SEO and ads, at published monthly prices). Prices: [probativegrowth.com/pricing](https://probativegrowth.com/pricing/) · About: [probativegrowth.com/about](https://probativegrowth.com/about/)

This is a remote MCP server. There is nothing to download, build or configure: no API key, no account, no environment variables.

- Transport: Streamable HTTP
- URL: https://probativegrowth.com/mcp
- Auth: none (read-only)
- Registry name: com.probativegrowth/legal-marketing-data

## Steps

1. Add the server to the MCP settings of the client, with the name `probative` and the URL above. For clients that use `mcpServers` (Cline, Cursor, Windsurf, Claude Desktop through a remote-server setting):

```json
{ "mcpServers": { "probative": { "url": "https://probativegrowth.com/mcp" } } }
```

   VS Code (`.vscode/mcp.json`): `{ "servers": { "probative": { "type": "http", "url": "https://probativegrowth.com/mcp" } } }`. Claude Code: `claude mcp add --transport http probative https://probativegrowth.com/mcp`.
2. Reload the client's MCP servers.
3. Check it works: call the tool `list_datasets` (no arguments). It returns every dataset with its version and DOI.
4. Try a lookup: `get_state_rules` with `{"state": "TX"}` returns Texas's lawyer advertising rules, each with its source.

## Smaller servers, one per dataset

- `https://probativegrowth.com/mcp/rules`: Lawyer advertising rules for all 50 states and DC, each with its source and status.
- `https://probativegrowth.com/mcp/bar-pipeline`: New lawyers by jurisdiction: bar exam pass rates and admissions, 2025.
- `https://probativegrowth.com/mcp/benchmarks`: Probative's law-firm marketing benchmarks, aggregated and rounded.
- `https://probativegrowth.com/mcp/ca-courts`: Cases filed in each California county's superior court, by case type.
- `https://probativegrowth.com/mcp/civil-filings`: Federal civil filings by nature of suit and district since 2018.
- `https://probativegrowth.com/mcp/consumer-complaints`: CFPB complaints about debt collection, credit reporting and debt management, by state and month since 2018.
- `https://probativegrowth.com/mcp/deserts`: Law offices and lawyers per resident in every US county (legal deserts).
- `https://probativegrowth.com/mcp/eeoc-charges`: EEOC workplace-discrimination charges by state and basis, FY2009 to FY2025.
- `https://probativegrowth.com/mcp/fatal-crashes`: NHTSA fatal crashes by county since 2019: trucks, motorcycles, pedestrians and bicyclists.
- `https://probativegrowth.com/mcp/fees`: Attorney fee caps and contingency-fee limits by state and federal program, plus a fee-cap calculator.
- `https://probativegrowth.com/mcp/filing`: What each state bar charges and requires to file or review lawyer ads.
- `https://probativegrowth.com/mcp/language`: Spanish speakers with limited English per Spanish-speaking lawyer, by state and metro.
- `https://probativegrowth.com/mcp/law-offices`: Law offices, jobs and pay by county, with solo-practice counts (BLS, Census).
- `https://probativegrowth.com/mcp/lawyer-wages`: Lawyer and paralegal pay by state and metro from BLS OEWS: employment, mean and median wages and percentiles.
- `https://probativegrowth.com/mcp/legal-prices`: Legal-services prices and jobs, monthly from BLS: the CPI and PPI legal-services indexes and legal-services employment.
- `https://probativegrowth.com/mcp/limitations`: Statutes of limitations by state for five kinds of civil claim, quoted from the code.
- `https://probativegrowth.com/mcp/mdl`: Pending actions in every federal MDL, monthly since 2019.
- `https://probativegrowth.com/mcp/opinions`: State and ABA ethics opinions on lawyer advertising and marketing, 2015 to 2026.
- `https://probativegrowth.com/mcp/platforms`: Ad-platform policies that touch law-firm ads: Google, Microsoft, Meta, LinkedIn, YouTube, ChatGPT.
- `https://probativegrowth.com/mcp/referral`: Referral-fee and fee-splitting rules for lawyers, by state.
- `https://probativegrowth.com/mcp/robocall-complaints`: FCC complaints about unwanted calls and texts, by state and month.
- `https://probativegrowth.com/mcp/state-courts`: Texas trial-court caseloads by court level, county and case type.

## Notes

- Every answer carries its source, version, DOI and a credit line; the data is CC BY 4.0.
- Not legal advice. Probative Growth is a marketing agency, not a law firm.
- Docs: https://probativegrowth.com/resources/rules-api/
