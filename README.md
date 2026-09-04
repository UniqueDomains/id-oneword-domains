# Available .ID One-Word Domains (14,782)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-14%2C782%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .id one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **14,782 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 14,782 domains · **Median ask:** $59.59 · **High-demand under $2,500:** 13

**Last updated:** 2026-09-04
**Canonical page:** `https://unique.domains/domains/tld/id`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/id?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./id.csv">CSV</a> / <a href="./id.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ID search](https://unique.domains/domains/tld/id?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ID search](https://unique.domains/domains/tld/id?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ID one-word domain catalog.

### Files

- `id.csv`, public CSV extract (1,000 rows)
- `id.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/id-oneword-domains/main/id.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                       |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------- |
| bad.id     | premium   | $1,455.02 | $20.06        | high           | medium | 3      | namesilo                        |
| great.id   | resell    | —         | —             | high           | low    | 5      | PT Jagat Informasi Solusi (int) |
| bang.id    | resell    | —         | —             | high           | low    | 4      | PT Jagat Informasi Solusi (int) |
| special.id | resell    | —         | —             | high           | low    | 7      | PT Jagat Informasi Solusi (int) |
| grey.id    | available | $14.19    | $20.75        | medium         | low    | 4      | namesilo                        |
| boy.id     | resell    | —         | —             | medium         | low    | 3      | PT Jetcoms Netindo              |
| ana.id     | premium   | $1,455.02 | $20.06        | high           | low    | 3      | namesilo                        |
| acids.id   | available | $17.99    | $20.75        | medium         | low    | 5      | namesilo                        |
| dot.id     | resell    | —         | —             | high           | medium | 3      | PANDI Registrar                 |
| are.id     | premium   | $1,560    | $22.75        | high           | low    | 3      | namecheap                       |
| aftuh.id   | available | $17.99    | $20.75        | medium         | low    | 5      | namesilo                        |
| sea.id     | resell    | —         | —             | high           | low    | 3      | PT Jetcoms Netindo              |
| alone.id   | available | $17.99    | $20.75        | high           | low    | 5      | namesilo                        |
| spf.id     | resell    | —         | —             | high           | low    | 3      | PANDI Registrar                 |
| bra.id     | premium   | $1,455.02 | $20.06        | medium         | low    | 3      | namesilo                        |
| bathe.id   | available | $17.99    | $20.75        | high           | low    | 5      | namesilo                        |
| xxi.id     | resell    | —         | —             | medium         | low    | 3      | PANDI Registrar                 |
| con.id     | premium   | $1,560    | $22.75        | high           | low    | 3      | namecheap                       |
| beads.id   | available | $17.99    | $20.75        | high           | low    | 5      | namesilo                        |
| you.id     | resell    | —         | —             | high           | medium | 3      | PT Cloud Hosting Indonesia      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 14,782 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 13 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/id?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/id?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=related_pricing)

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

This list covers 6,981 one-word and short compound .ID domain names, from everyday nouns like jewels.id and virtual.id to action-style terms like beawake.id and fitinto.id. With a median ask near $82, the set is broad enough for founders scouting a brandable, ownable name and for investors comparing entry price against demand across the .ID namespace. Because the names are common words rather than invented terms, spelling simplicity and word recognition are the main differentiators between listings.

- 6,981 one-word .ID domains in this set — broad selection across niches
- Median ask near $82 — budget-friendly for shortlisting brandable names
- Sample names mix everyday nouns and compound words (e.g., popup, virtual)
- Compare renewal cost and brandability before committing to a domain

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ID One-Word Domains*. Version 2026-09-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ID page](https://unique.domains/domains/tld/id?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
