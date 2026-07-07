# Available .MOE One-Word Domains (11,797)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C797%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .moe one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,797 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,797 domains · **Median ask:** $50.17 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `moe.csv`, public CSV extract (1,000 rows)
- `moe.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/moe-oneword-domains/main/moe.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| atp.moe  | available | $13.99    | $13.99        | medium         | low    | 3      | namesilo    |
| most.moe | resell    | —         | —             | high           | low    | 4      | Dynadot Inc |
| aaa.moe  | premium   | $325      | $15.60        | high           | medium | 3      | namecheap   |
| bid.moe  | available | $13.99    | $13.99        | high           | low    | 3      | namesilo    |
| bro.moe  | premium   | $96       | $14.16        | medium         | low    | 3      | namesilo    |
| BJP.moe  | available | $17.88    | —             | medium         | low    | 3      | namecheap   |
| day.moe  | premium   | $625      | —             | high           | low    | 3      | name.com    |
| DJI.moe  | available | $13.99    | $13.99        | high           | low    | 3      | namesilo    |
| hot.moe  | premium   | $625      | —             | high           | low    | 3      | name.com    |
| Eid.moe  | available | $13.99    | $13.99        | high           | low    | 3      | namesilo    |
| pad.moe  | premium   | $302.50   | $14.16        | medium         | low    | 3      | namesilo    |
| feb.moe  | available | $13.99    | $13.99        | high           | low    | 3      | namesilo    |
| sky.moe  | premium   | $1,500    | —             | high           | medium | 3      | name.com    |
| gee.moe  | available | $13.99    | $13.99        | medium         | low    | 3      | namesilo    |
| was.moe  | premium   | $96       | $14.16        | low            | low    | 3      | namesilo    |
| hic.moe  | available | $13.99    | $13.99        | high           | low    | 3      | namesilo    |
| club.moe | premium   | $302.50   | $14.16        | high           | low    | 4      | namesilo    |
| oak.moe  | available | $13.99    | $13.99        | medium         | low    | 3      | namesilo    |
| date.moe | premium   | $100      | —             | high           | low    | 4      | name.com    |
| ole.moe  | available | $13.99    | $13.99        | high           | low    | 3      | namesilo    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,797 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/moe?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/moe?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=related_pricing)

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

This list covers one-word domains registered under the .moe extension, drawn from everyday English vocabulary rather than invented terms. Names like "dogstail," "bonvoyage," "finals," and "chaitea" show the range—short, pronounceable words that work across community, lifestyle, and niche branding use cases. With 11,797 domains in this set and a median asking price near $50, most listings sit in an accessible price range for early-stage projects or opportunistic acquisition. Because .moe is a less mainstream extension, one-word availability remains higher than on .com, though buyers should still weigh renewal cost, spelling ease, and potential trademark conflicts before committing.

- 11,797 one-word .moe domains available now
- Median asking price near $50 per domain
- Short, brandable English words across many themes
- Updated daily for current pricing and availability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MOE One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MOE page](https://unique.domains/domains/tld/moe?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moe_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
