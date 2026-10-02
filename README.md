# Available .YACHTS One-Word Domains (31,685)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-31%2C685%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .yachts one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **31,685 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 31,685 domains · **Median ask:** $95.89 · **High-demand under $2,500:** 111

**Last updated:** 2026-10-02
**Canonical page:** `https://unique.domains/domains/tld/yachts`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/yachts?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./yachts.csv">CSV</a> / <a href="./yachts.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .YACHTS search](https://unique.domains/domains/tld/yachts?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .YACHTS search](https://unique.domains/domains/tld/yachts?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .YACHTS one-word domain catalog.

### Files

- `yachts.csv`, public CSV extract (1,000 rows)
- `yachts.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/yachts-oneword-domains/main/yachts.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar            |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------- |
| alb.yachts       | available | $1.99     | $17.29        | high           | low    | 3      | namesilo             |
| try.yachts       | resell    | —         | —             | high           | low    | 3      | NameCheap, Inc.      |
| boat.yachts      | premium   | $11,040   | $11,040       | high           | low    | 4      | namesilo             |
| ang.yachts       | available | $1.99     | $20.99        | high           | low    | 3      | name.com             |
| land.yachts      | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC     |
| cake.yachts      | premium   | $2,070.20 | $2,070.20     | high           | low    | 4      | spaceship            |
| ard.yachts       | available | $1.24     | $13.97        | medium         | low    | 3      | spaceship            |
| panel.yachts     | resell    | —         | —             | high           | low    | 5      | Dynadot Inc          |
| chat.yachts      | premium   | $2,660    | $2,660        | high           | medium | 4      | namesilo             |
| asc.yachts       | available | $1.80     | $21.98        | high           | low    | 3      | namecheap            |
| share.yachts     | resell    | —         | —             | high           | medium | 5      | UM Domains Pte. Ltd. |
| gong.yachts      | premium   | $672.95   | $672.95       | high           | high   | 4      | spaceship            |
| atv.yachts       | available | $1.80     | $21.98        | high           | low    | 3      | namecheap            |
| exceed.yachts    | resell    | —         | —             | high           | low    | 6      | GoDaddy.com, LLC     |
| jack.yachts      | premium   | $2,660    | $2,660        | high           | medium | 4      | namesilo             |
| bok.yachts       | available | $1.54     | $14.21        | high           | low    | 3      | porkbun              |
| fraser.yachts    | resell    | —         | —             | high           | medium | 6      | —                    |
| pray.yachts      | premium   | $2,070.20 | $2,070.20     | high           | low    | 4      | spaceship            |
| bom.yachts       | available | $1.99     | $17.29        | high           | medium | 3      | namesilo             |
| paperwork.yachts | resell    | —         | —             | high           | low    | 9      | —                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 31,685 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 111 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/yachts?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/yachts?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of .yachts domains features one-word names spanning everyday verbs, nouns, and short phrases combined into single strings — from investment.yachts to chaitea.yachts. With a median asking price around $166 across 12,441 names, the .yachts extension offers an affordable way to secure a distinctive domain for yacht charters, marinas, brokerages, or lifestyle brands. Because pricing and renewal terms vary by registrar and seller, compare each name's total cost of ownership before committing.

- 12,441 one-word .yachts domain names in this selection
- Median asking price near $166 across the set
- Short, brandable strings like chaitea.yachts and QandA.yachts
- Compare renewal costs and registrar fees before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .YACHTS One-Word Domains*. Version 2026-10-02. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .YACHTS page](https://unique.domains/domains/tld/yachts?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_yachts_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
