# Available .GIVING One-Word Domains (15,557)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C557%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .giving one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,557 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,557 domains · **Median ask:** $9.62 · **High-demand under $2,500:** 15

**Last updated:** 2026-08-14
**Canonical page:** `https://unique.domains/domains/tld/giving`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/giving?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./giving.csv">CSV</a> / <a href="./giving.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GIVING search](https://unique.domains/domains/tld/giving?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GIVING search](https://unique.domains/domains/tld/giving?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GIVING one-word domain catalog.

### Files

- `giving.csv`, public CSV extract (1,000 rows)
- `giving.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/giving-oneword-domains/main/giving.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| just.giving  | available | —         | —             | high           | medium | 4      | —         |
| bad.giving   | available | $5.99     | —             | high           | medium | 3      | name.com  |
| gay.giving   | premium   | $82.50    | —             | high           | medium | 3      | name.com  |
| BBC.giving   | available | $5.99     | —             | high           | medium | 3      | name.com  |
| job.giving   | premium   | $82.50    | —             | high           | low    | 3      | name.com  |
| bob.giving   | available | $5.99     | —             | high           | medium | 3      | name.com  |
| tax.giving   | premium   | $82.50    | —             | high           | medium | 3      | name.com  |
| btw.giving   | available | $5.99     | —             | high           | low    | 3      | name.com  |
| top.giving   | premium   | $82.50    | —             | high           | medium | 3      | name.com  |
| egg.giving   | available | $5.99     | —             | high           | low    | 3      | name.com  |
| toy.giving   | premium   | $82.50    | —             | high           | low    | 3      | name.com  |
| Eid.giving   | available | $5.99     | —             | high           | low    | 3      | name.com  |
| usa.giving   | premium   | $1,250    | —             | high           | medium | 3      | name.com  |
| fly.giving   | available | $5.99     | —             | high           | low    | 3      | name.com  |
| xxx.giving   | premium   | $123.75   | $123.75       | low            | medium | 3      | name.com  |
| had.giving   | available | $5.99     | —             | high           | low    | 3      | name.com  |
| save.giving  | premium   | $82.50    | —             | high           | low    | 4      | name.com  |
| ice.giving   | available | $5.99     | —             | medium         | medium | 3      | name.com  |
| black.giving | premium   | $82.50    | —             | high           | medium | 5      | name.com  |
| lol.giving   | available | $5.99     | —             | high           | low    | 3      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,557 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 15 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/giving?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/giving?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

The .giving TLD signals purpose-driven intent, making it a natural fit for nonprofits, foundations, and social-impact ventures. This list includes 12,676 one-word .giving domain names, from action-oriented names like makehappen.giving and headout.giving to simple, ownable options like half.giving and just.giving. With a median asking price near $11, the extension offers an accessible entry point for founders building cause-based brands and for investors watching a still-emerging namespace.

- 12,676 one-word .giving domain names in this selection
- Median asking price near $11 across the set
- Includes short, brandable names like half.giving and just.giving
- Ideal for nonprofits, causes, and mission-driven brands

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GIVING One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GIVING page](https://unique.domains/domains/tld/giving?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_giving_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
