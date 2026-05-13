# Available .CEO One-Word Domains (12,266)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C266%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ceo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,266 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,266 domains · **Median ask:** $46.27 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
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

- `ceo.csv` — public CSV extract (1,000 rows)
- `ceo.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ceo-oneword-domains/main/ceo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar     |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------- |
| lets.ceo         | available | $19.99    | —             | 77             | 39     | 4      | name.com      |
| diabetes.ceo     | resell    | —         | —             | 66             | 37     | 8      | Go Daddy, LLC |
| insight.ceo      | premium   | $499      | —             | 76             | 69     | 8      | name.com      |
| stories.ceo      | available | $19.99    | —             | 58             | 36     | 7      | name.com      |
| payments.ceo     | resell    | —         | —             | 58             | 33     | 8      | Go Daddy, LLC |
| events.ceo       | premium   | $499      | —             | 68             | 37     | 6      | name.com      |
| inspiration.ceo  | available | $19.99    | —             | 88             | 30     | 11     | name.com      |
| tickets.ceo      | premium   | $499      | —             | 64             | 34     | 7      | name.com      |
| videos.ceo       | available | $19.99    | —             | 52             | 30     | 6      | name.com      |
| Cats.ceo         | premium   | $558.88   | $558.88       | 59             | 33     | 4      | namecheap     |
| quotes.ceo       | available | $19.99    | —             | 58             | 29     | 6      | name.com      |
| rewards.ceo      | premium   | $499      | —             | 62             | 30     | 7      | name.com      |
| commonground.ceo | available | $19.99    | —             | 74             | 28     | 13     | name.com      |
| traders.ceo      | premium   | $499      | —             | 60             | 26     | 7      | name.com      |
| gods.ceo         | available | $19.99    | —             | 72             | 27     | 4      | name.com      |
| shops.ceo        | premium   | $499      | —             | 64             | 24     | 5      | name.com      |
| systems.ceo      | available | $19.99    | —             | 46             | 27     | 7      | name.com      |
| affiliates.ceo   | premium   | $499      | —             | 60             | 21     | 10     | name.com      |
| tips.ceo         | available | $19.99    | —             | 80             | 26     | 4      | name.com      |
| hightech.ceo     | premium   | $499      | —             | 83             | 16     | 9      | name.com      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,266 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ceo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ceo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=related_pricing)

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

These domains are all one-word names on the .ceo extension, which gives the set a specific executive and leadership framing. That can work well when the word is clear, positive, and easy to recall, as in kudos.ceo or phase.ceo. It can also create more risk when the word is awkward, negative, or too broad, as with shame.ceo or with.ceo. When comparing this selection, focus first on whether the word becomes stronger or weaker when paired with .ceo. Then weigh ask price, renewal expectations, memorability, spelling, and any obvious trademark exposure before narrowing to a shortlist.

- Best fits pair naturally with an executive or leadership angle
- Positive, clear words tend to carry .ceo more convincingly
- Broad or negative words can weaken trust and resale appeal
- Use ask price, renewal, and trademark signals to compare

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CEO One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CEO page](https://unique.domains/domains/tld/ceo?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ceo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
