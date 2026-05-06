# Available .MOE One-Word Domains (11,793)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C793%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .moe one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,793 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,793 domains · **Median ask:** $40.81 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/moe`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/moe?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./moe.csv">CSV</a> / <a href="./moe.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .MOE search](https://unique.domains/domains/tld/moe?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .MOE search](https://unique.domains/domains/tld/moe?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MOE one-word domain catalog.

### Files

- `moe.csv` — public CSV extract (1,000 rows)
- `moe.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/moe-oneword-domains/main/moe.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Trex.moe          | available | $17.88    | —             | 80             | 24     | 5      | namecheap |
| WiFi.moe          | available | $17.88    | —             | 83             | 37     | 5      | namecheap |
| finals.moe        | available | $13.99    | $13.99        | 80             | 7      | 6      | namesilo  |
| jewels.moe        | available | $17.88    | —             | 80             | 15     | 6      | namecheap |
| ladies.moe        | available | $17.88    | —             | 80             | 17     | 6      | namecheap |
| getup.moe         | available | $17.88    | —             | 82             | 14     | 6      | namecheap |
| Apples.moe        | available | $17.88    | —             | 90             | 16     | 6      | namecheap |
| useit.moe         | available | $17.88    | —             | 94             | 7      | 6      | namecheap |
| dogsit.moe        | available | $17.88    | —             | 96             | 2      | 6      | namecheap |
| edamame.moe       | available | $13.99    | $13.99        | 80             | 9      | 7      | namesilo  |
| playin.moe        | available | $17.88    | —             | 80             | 10     | 7      | namecheap |
| QandA.moe         | available | $17.88    | —             | 80             | 10     | 7      | namecheap |
| getlife.moe       | available | $17.88    | —             | 80             | 5      | 8      | namecheap |
| makers.moe        | available | $13.99    | $13.99        | 62             | 67     | 6      | namesilo  |
| jobs.moe          | premium   | $100      | —             | 79             | 42     | 4      | name.com  |
| regions.moe       | available | $17.88    | —             | 64             | 59     | 7      | namecheap |
| stories.moe       | premium   | $100      | —             | 58             | 36     | 7      | name.com  |
| keepthechange.moe | available | $17.88    | —             | 46             | 59     | 15     | namecheap |
| homes.moe         | premium   | $100      | —             | 86             | 34     | 5      | name.com  |
| shortcuts.moe     | available | $17.88    | —             | 48             | 41     | 10     | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,793 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/moe?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/moe?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is narrowly focused on one-word .moe domains, which makes comparison straightforward. The extension is distinctive, so the main decision is not only the word itself but whether the name feels ownable, memorable, and commercially usable with .moe attached. Generic words such as finals.moe, jewels.moe, ladies.moe, and forces.moe are easier to assess on brandability than names that echo well-known brands or products like Chanel.moe, Shrek.moe, or WiFi.moe. With a median ask of 40.81, price is accessible, but low ask alone does not reduce naming or trademark risk. When comparing these domains, prioritize clean generic language, clear spelling, and fit between the word and the .moe extension.

- Generic words usually carry cleaner brandability than branded terms
- Median ask is 40.81 across this .moe selection
- Short, clear words are easier to remember and evaluate
- Watch trademark exposure in names like Chanel.moe or Shrek.moe

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MOE One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MOE page](https://unique.domains/domains/tld/moe?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
