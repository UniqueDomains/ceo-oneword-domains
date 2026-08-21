# Available .CEO One-Word Domains (17,525)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C525%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ceo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,525 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,525 domains · **Median ask:** $31.63 · **High-demand under $2,500:** 41

**Last updated:** 2026-08-21
**Canonical page:** `https://unique.domains/domains/tld/ceo`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/ceo?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./ceo.csv">CSV</a> / <a href="./ceo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CEO search](https://unique.domains/domains/tld/ceo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CEO search](https://unique.domains/domains/tld/ceo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CEO one-word domain catalog.

### Files

- `ceo.csv`, public CSV extract (1,000 rows)
- `ceo.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ceo-oneword-domains/main/ceo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| ane.ceo     | available | $9.99     | $124.98       | low            | low    | 3      | namecheap       |
| people.ceo  | resell    | —         | —             | high           | medium | 6      | Spaceship, Inc. |
| aaa.ceo     | premium   | $518.96   | $518.96       | high           | medium | 3      | namecheap       |
| atp.ceo     | available | $10.19    | $109.99       | medium         | low    | 3      | namesilo        |
| wisdom.ceo  | resell    | —         | —             | high           | low    | 6      | Porkbun, LLC    |
| ask.ceo     | premium   | $499      | —             | high           | medium | 3      | name.com        |
| bar.ceo     | available | $10.19    | $109.99       | high           | low    | 3      | namesilo        |
| wedding.ceo | resell    | —         | —             | high           | low    | 7      | Porkbun, LLC    |
| day.ceo     | premium   | $499      | —             | high           | low    | 3      | name.com        |
| bid.ceo     | available | $10.19    | $109.99       | high           | low    | 3      | namesilo        |
| DJI.ceo     | premium   | $499      | —             | high           | low    | 3      | name.com        |
| BJP.ceo     | available | $19.99    | —             | medium         | low    | 3      | name.com        |
| bill.ceo    | premium   | $248.75   | —             | high           | low    | 4      | name.com        |
| bro.ceo     | available | $19.99    | —             | medium         | low    | 3      | name.com        |
| club.ceo    | premium   | $499      | —             | high           | low    | 4      | name.com        |
| but.ceo     | available | $10.19    | $109.99       | high           | low    | 3      | namesilo        |
| date.ceo    | premium   | $499      | —             | high           | low    | 4      | name.com        |
| Eid.ceo     | available | $10.19    | $109.99       | high           | low    | 3      | namesilo        |
| fast.ceo    | premium   | $499      | $499          | high           | medium | 4      | name.com        |
| eve.ceo     | available | $19.99    | —             | high           | medium | 3      | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,525 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 41 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ceo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ceo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=related_pricing)

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

This selection includes 12,268 one-word .CEO domain names spanning simple, memorable strings such as butterflies.ceo, getup.ceo, weddingcake.ceo, tips.ceo, and makesense.ceo. The median ask across the set is roughly $45, positioning most of these domains within reach for founders building a brand and investors testing acquisition volume. Because .CEO is a newer, less mainstream TLD, renewal costs and long-term demand should be checked domain-by-domain before committing. Comparing price against memorability and pronounceability is the fastest way to separate strong picks from filler names in this list.

- 12,268 one-word .CEO domain names in this selection
- Median ask near $45 across the set
- Mix of short, brandable, and descriptive names
- Updated daily to reflect current listings

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CEO One-Word Domains*. Version 2026-08-21. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CEO page](https://unique.domains/domains/tld/ceo?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
