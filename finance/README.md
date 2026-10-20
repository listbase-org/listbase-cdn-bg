# Финанси и търговия (Finance & Trade)

4 datasets — 135 records

> Browse at [listbase.org/bg/finance/](https://listbase.org/bg/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Банки в София — SWIFT/BIC кодове (Sofia bank SWIFT/BIC codes)](bg-sofiya-banki.json) | 115 | 19 KB | [CSV](bg-sofiya-banki_BG.csv) | [Excel](bg-sofiya-banki_BG.xlsx) | [View](https://listbase.org/bg/finance/bg-sofiya-banki/) |
| [Банки в Варна — SWIFT/BIC кодове (Varna bank SWIFT/BIC codes)](bg-varna-banki.json) | 9 | 4 KB | [CSV](bg-varna-banki_BG.csv) | [Excel](bg-varna-banki_BG.xlsx) | [View](https://listbase.org/bg/finance/bg-varna-banki/) |
| [Газови електроцентрали в България](bg-gazovi-elektrocentrali.json) | 6 | 7 KB | [CSV](bg-gazovi-elektrocentrali_BG.csv) | [Excel](bg-gazovi-elektrocentrali_BG.xlsx) | [View](https://listbase.org/bg/finance/bg-gazovi-elektrocentrali/) |
| [Банки в Пловдив — SWIFT/BIC кодове (Plovdiv bank SWIFT/BIC codes)](bg-plovdiv-banki.json) | 5 | 3 KB | [CSV](bg-plovdiv-banki_BG.csv) | [Excel](bg-plovdiv-banki_BG.xlsx) | [View](https://listbase.org/bg/finance/bg-plovdiv-banki/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/finance/bg-sofiya-banki.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/finance/)
