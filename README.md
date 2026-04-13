# Available .ID One-Word Domains (4,511)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-4%2C512%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-4%2C511%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .id one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 4,512 rows · **Live catalog:** 4,511 domains

**Last updated:** 2026-04-13  
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

- `id.csv` — public CSV extract (4,512 rows)
- `id.json` — public JSON extract (4,512 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/id-oneword-domains/main/id.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                       |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------- |
| seventeen.id | available | $25.98    | —             | 84             | 62     | 9      | namecheap                       |
| boss.id      | resell    | —         | —             | 76             | 99     | 4      | PT Jagat Informasi Solusi (int) |
| aaa.id       | premium   | $1,560    | $22.75        | 70             | 42     | 3      | namecheap                       |
| wonder.id    | available | $25.98    | —             | 86             | 47     | 6      | namecheap                       |
| prank.id     | resell    | —         | —             | 106            | 98     | 5      | PT Registrasi Nama Domain       |
| goon.id      | premium   | $221      | $22.75        | 80             | 35     | 5      | namecheap                       |
| death.id     | available | $25.98    | —             | 62             | 28     | 5      | namecheap                       |
| blink.id     | resell    | —         | —             | 80             | 98     | 5      | PT Digital Registra Indonesia   |
| odd.id       | premium   | $1,560    | $22.75        | 72             | 32     | 3      | namecheap                       |
| feelgood.id  | available | $25.98    | —             | 82             | 27     | 9      | namecheap                       |
| brave.id     | resell    | —         | —             | 76             | 98     | 5      | PT Digital Registra Indonesia   |
| ten.id       | premium   | $1,560    | $22.75        | 88             | 31     | 3      | namecheap                       |
| outlaw.id    | available | $25.98    | —             | 62             | 24     | 6      | namecheap                       |
| can.id       | resell    | —         | —             | 68             | 98     | 3      | PT Jetcoms Netindo              |
| sad.id       | premium   | $1,560    | $22.75        | 72             | 27     | 3      | namecheap                       |
| silly.id     | available | $25.98    | —             | 82             | 23     | 5      | namecheap                       |
| palestine.id | resell    | —         | —             | 59             | 93     | 9      | PT Registrasi Nama Domain       |
| sum.id       | premium   | $1,560    | $22.75        | 66             | 26     | 3      | namecheap                       |
| diligent.id  | available | $25.98    | —             | 68             | 20     | 8      | namecheap                       |
| authentic.id | resell    | —         | —             | 76             | 83     | 9      | PT Jagat Informasi Solusi (int) |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 4,512-row public sample | 4,511 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/id?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/id?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ID One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ID page](https://unique.domains/domains/tld/id?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
