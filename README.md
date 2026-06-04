# Available .BAR One-Word Domains (12,282)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C282%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .bar one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,282 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,282 domains · **Median ask:** $171.96 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
**Canonical page:** `https://unique.domains/domains/tld/bar`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/bar?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./bar.csv">CSV</a> / <a href="./bar.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BAR search](https://unique.domains/domains/tld/bar?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BAR search](https://unique.domains/domains/tld/bar?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BAR one-word domain catalog.

### Files

- `bar.csv` — public CSV extract (1,000 rows)
- `bar.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/bar-oneword-domains/main/bar.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar     |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------- |
| screen.bar     | available | $39.99    | —             | 72             | 30     | 6      | name.com      |
| apple.bar      | resell    | —         | —             | 98             | 89     | 5      | GoDaddy       |
| polo.bar       | premium   | $787.50   | —             | 76             | 79     | 4      | name.com      |
| realtime.bar   | available | $3.49     | $54.99        | 72             | 28     | 9      | namesilo      |
| identity.bar   | resell    | —         | —             | 80             | 65     | 8      | GoDaddy       |
| own.bar        | premium   | $3.49     | $54.99        | 122            | 70     | 3      | namesilo      |
| ahead.bar      | available | $3.49     | $54.99        | 76             | 27     | 5      | namesilo      |
| icon.bar       | resell    | —         | —             | 89             | 46     | 4      | Dynadot, LLC  |
| guess.bar      | premium   | $787.50   | —             | 100            | 70     | 5      | name.com      |
| commit.bar     | available | $3.49     | $54.99        | 96             | 26     | 6      | namesilo      |
| print.bar      | resell    | —         | —             | 114            | 45     | 5      | Sea Wasp, LLC |
| square.bar     | premium   | $157.50   | —             | 72             | 66     | 6      | name.com      |
| ondemand.bar   | available | $39.99    | —             | 68             | 26     | 9      | name.com      |
| blink.bar      | resell    | —         | —             | 80             | 42     | 5      | Dynadot, LLC  |
| sex.bar        | premium   | $7,875    | —             | 98             | 59     | 3      | name.com      |
| grin.bar       | available | $39.99    | —             | 102            | 25     | 4      | name.com      |
| gather.bar     | resell    | —         | —             | 96             | 39     | 6      | GoDaddy       |
| athletics.bar  | premium   | $117      | $234          | 69             | 52     | 9      | namecheap     |
| integrated.bar | available | $3.49     | $54.99        | 72             | 25     | 10     | namesilo      |
| cosmos.bar     | resell    | —         | —             | 74             | 39     | 6      | GoDaddy       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,282 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/bar?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/bar?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=related_pricing)

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

This selection is made up of one-word .bar domains. The names range from short generics such as use.bar, hear.bar, and home.bar to longer dictionary terms like arithmetic.bar and attention.bar. For founders, the main question is whether the word is easy to remember and whether .bar fits the brand or venue clearly. For investors, the key issue is buyer fit: a strong word can still be niche if the extension limits demand. With a median ask of 127.71, pricing is accessible, but the best choices still depend on word quality, commercial intent, and how naturally the term pairs with .bar.

- Short words like use.bar and hear.bar are easier to recall
- Match the word to .bar so the full name reads naturally
- Median ask is 127.71, so compare quality at similar prices
- Check for trademark overlap on broad commercial terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BAR One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BAR page](https://unique.domains/domains/tld/bar?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bar_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
