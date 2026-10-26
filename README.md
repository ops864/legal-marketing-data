# Legal-marketing open data

Published by [Probative Growth](https://probativegrowth.com/), a marketing agency for US law firms (SEO and ads, at published monthly prices). Prices: [probativegrowth.com/pricing](https://probativegrowth.com/pricing/) · About: [probativegrowth.com/about](https://probativegrowth.com/about/)

Open, citable datasets on US law-firm marketing, maintained by [Probative Growth](https://probativegrowth.com/data/): lawyer advertising rules for all 50 states and DC, bar ad filing and fees, ethics opinions, ad-platform policies, attorney fee caps, federal MDL dockets, Spanish-language demand and California court filings by county.

Every record quotes its primary source and the date it was checked. Each dataset has a DOI on Zenodo. Not legal advice: check the source and your own counsel before you rely on a rule.

| Dataset | Files | DOI |
|---|---|---|
| [Lawyer advertising rules by state (50 states and DC)](https://probativegrowth.com/resources/lawyer-advertising-rules-by-state/) | `data/rules/` | [10.5281/zenodo.23655396](https://doi.org/10.5281/zenodo.23655396) |
| [California court filings by county: civil, criminal, family, juvenile, probate and appeals, fiscal years 2023–24 and 2024–25](https://probativegrowth.com/data/ca-courts/) | `data/ca-courts/` | [10.5281/zenodo.23658524](https://doi.org/10.5281/zenodo.23658524) |
| [Attorney fee caps and contingency-fee rules, by state and federal program](https://probativegrowth.com/research/attorney-fee-caps-by-state/) | `data/fees/` | [10.5281/zenodo.23656738](https://doi.org/10.5281/zenodo.23656738) |
| [What US state bars charge, and require, to file or review lawyer advertising](https://probativegrowth.com/research/lawyer-ad-filing-fees/) | `data/filing/` | [10.5281/zenodo.23656746](https://doi.org/10.5281/zenodo.23656746) |
| [Spanish-speaking demand vs Spanish-speaking lawyer supply, by state and metro](https://probativegrowth.com/data/language/) | `data/language/` | [10.5281/zenodo.23656758](https://doi.org/10.5281/zenodo.23656758) |
| [Mass-tort docket tracker, federal MDL pending actions by month since 2019](https://probativegrowth.com/research/mass-tort-mdl-tracker/) | `data/mdl/` | [10.5281/zenodo.23656743](https://doi.org/10.5281/zenodo.23656743) |
| [Legal-marketing ethics opinions, 2015–2026](https://probativegrowth.com/data/opinions/) | `data/opinions/` | [10.5281/zenodo.23656749](https://doi.org/10.5281/zenodo.23656749) |
| [Legal ad-platform policy tracker](https://probativegrowth.com/data/platforms/) | `data/platforms/` | [10.5281/zenodo.23656753](https://doi.org/10.5281/zenodo.23656753) |

Each folder holds the full CSV and JSON, a `README.txt` with the fields, `changes.json` (the change log), `openapi.json`, and `CITATION.cff`.

## Live API and MCP server

- JSON API: <https://probativegrowth.com/data/v1/index.json> (the same records, sharded by state, metro or topic).
- MCP server (read-only, no auth): `https://probativegrowth.com/mcp`. Listed in the official MCP Registry as `com.probativegrowth/legal-marketing-data`.
  - Claude Code: `claude mcp add --transport http probative https://probativegrowth.com/mcp`
- Docs: <https://probativegrowth.com/resources/rules-api/>

## Mirrors

- Hugging Face: <https://huggingface.co/datasets/ProbativeGrowth/legal-marketing-data> (all eight datasets, CSV and JSON, one config per dataset)
- Kaggle: <https://www.kaggle.com/datasets/probativeoperations/legal-marketing-open-data-us> (the eight CSVs)

## License

CC BY 4.0. Credit "Probative Growth" and link the dataset page. See `LICENSE`.

## Updates

This repository mirrors the published files. The site is the source of truth; each dataset's `changes.json` and its Zenodo versions record what changed and when.
