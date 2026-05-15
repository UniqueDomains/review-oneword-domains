# Available .REVIEW One-Word Domains (12,694)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C694%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .review one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,694 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,694 domains · **Median ask:** $797.63 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-15  
**Canonical page:** `https://unique.domains/domains/tld/review`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/review?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./review.csv">CSV</a> / <a href="./review.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .REVIEW search](https://unique.domains/domains/tld/review?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .REVIEW search](https://unique.domains/domains/tld/review?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .REVIEW one-word domain catalog.

### Files

- `review.csv` — public CSV extract (1,000 rows)
- `review.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/review-oneword-domains/main/review.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| barup.review       | available | $15.73    | —             | 82             | 2      | 6      | namecheap       |
| geton.review       | available | $15.73    | —             | 82             | 10     | 6      | namecheap       |
| rumcake.review     | available | $15.73    | —             | 81             | 3      | 8      | namecheap       |
| chaitea.review     | available | $15.73    | —             | 86             | 3      | 8      | namecheap       |
| WhatsApp.review    | premium   | —         | —             | 90             | 84     | 8      | —               |
| dogstail.review    | available | $15.73    | —             | 94             | 1      | 8      | namecheap       |
| cuddleup.review    | available | $15.73    | —             | 89             | 4      | 9      | namecheap       |
| makewhole.review   | available | $15.73    | —             | 80             | 2      | 10     | namecheap       |
| happier.review     | available | $15.73    | —             | 62             | 16     | 7      | namecheap       |
| webcontent.review  | resell    | —         | —             | 78             | 5      | 11     | NameCheap, Inc. |
| insight.review     | premium   | $125      | —             | 76             | 69     | 8      | name.com        |
| holdings.review    | available | $15.73    | —             | 52             | 14     | 8      | namecheap       |
| donuts.review      | premium   | $1,250    | —             | 54             | 62     | 6      | name.com        |
| counselling.review | available | $15.73    | —             | 82             | 13     | 11     | namecheap       |
| RedSox.review      | premium   | $490      | $70           | 72             | 60     | 7      | namecheap       |
| letus.review       | available | $15.73    | —             | 79             | 13     | 6      | namecheap       |
| regions.review     | premium   | $3,125    | —             | 64             | 59     | 7      | name.com        |
| niggers.review     | available | $15.73    | —             | 37             | 13     | 7      | namecheap       |
| agents.review      | premium   | $6,250    | —             | 56             | 50     | 6      | name.com        |
| runs.review        | available | $15.73    | —             | 68             | 12     | 4      | namecheap       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,694 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/review?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/review?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of .review domains, which makes extension fit the first filter. Names such as Acup.review, getlife.review, pierogi.review, and rumcake.review read like topical review brands, while others feel more awkward or less commercially clear. When comparing these domains, check whether the word before .review is easy to pronounce, specific enough to support a review-led brand, and broad enough to stay useful over time. Price discipline matters here: the median ask is $798, so stronger names should justify that level with better memorability, cleaner spelling, and clearer intent.

- All names in this selection use the .review extension
- Median ask across this set is $798
- Favor words that pair naturally with review intent
- Watch for awkward phrasing and weak commercial clarity

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REVIEW One-Word Domains*. Version 2026-05-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REVIEW page](https://unique.domains/domains/tld/review?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_review_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
