# Available .ID One-Word Domains (6,946)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-6%2C946%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .id one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **6,946 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 6,946 domains · **Median ask:** $46.63 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `id.csv` — public CSV extract (1,000 rows)
- `id.json` — public JSON extract (1,000 rows)
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

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                     |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------- |
| would.id      | available | $17.99    | $20.75        | 86             | 9      | 5      | namesilo                      |
| jewels.id     | available | $25.98    | —             | 80             | 15     | 6      | namecheap                     |
| barup.id      | available | $25.98    | —             | 82             | 2      | 6      | namecheap                     |
| except.id     | available | $17.99    | $20.75        | 82             | 6      | 6      | namesilo                      |
| edamame.id    | available | $17.99    | $20.75        | 80             | 9      | 7      | namesilo                      |
| hangon.id     | available | $25.98    | —             | 82             | 6      | 7      | namecheap                     |
| pierogi.id    | available | $25.98    | —             | 82             | 7      | 7      | namecheap                     |
| Snickers.id   | available | $25.98    | —             | 80             | 10     | 8      | namecheap                     |
| rumcake.id    | available | $25.98    | —             | 81             | 3      | 8      | namecheap                     |
| FabFour.id    | available | $17.99    | $20.75        | 82             | 3      | 8      | namesilo                      |
| headout.id    | available | $25.98    | —             | 82             | 6      | 8      | namecheap                     |
| dogstail.id   | available | $25.98    | —             | 94             | 1      | 8      | namecheap                     |
| RedSox.id     | available | $25.98    | —             | 72             | 60     | 7      | namecheap                     |
| NewZealand.id | resell    | —         | —             | 78             | 94     | 11     | PT Registrasi Nama Domain     |
| task.id       | premium   | $216.32   | $20.06        | 78             | 37     | 4      | namesilo                      |
| echoes.id     | available | $17.99    | $20.75        | 56             | 24     | 6      | namesilo                      |
| virtual.id    | resell    | —         | —             | 80             | 42     | 7      | PT Digital Registra Indonesia |
| cams.id       | premium   | $216.32   | $20.06        | 52             | 29     | 4      | namesilo                      |
| veterans.id   | available | $25.98    | —             | 56             | 23     | 8      | namecheap                     |
| solutions.id  | resell    | —         | —             | 56             | 31     | 9      | PT Registrasi Nama Domain     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 6,946 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This set is defined by a single constraint: one-word domains on .id. That makes the comparison cleaner. The main differences are the underlying words themselves. Some are broad dictionary terms such as finals.id, jewels.id, and suppose.id. Others are more niche or quirky, like dogsit.id, edamame.id, and pierogi.id. With a median ask of 43.9, the key question is not category fit alone. It is whether the word is easy to say, easy to spell, and distinctive enough to hold value or support a brand. When comparing these domains, give extra weight to clarity, recall, and obvious trademark overlap in common commercial classes.

- Prioritize words that are easy to say and spell
- Generic words can be broad, but less differentiated
- Niche words may feel sharper, but narrower in appeal
- Check trademark overlap before paying even a low ask

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ID One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ID page](https://unique.domains/domains/tld/id?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_id_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
