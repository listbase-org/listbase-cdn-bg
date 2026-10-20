# Здраве (Health)

2 datasets — 1,043 records

> Browse at [listbase.org/bg/health/](https://listbase.org/bg/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Зъболекари в България](bg-zabolekari.json) | 556 | 62 KB | [CSV](bg-zabolekari_BG.csv) | [Excel](bg-zabolekari_BG.xlsx) | [View](https://listbase.org/bg/health/bg-zabolekari/) |
| [Болници в България](bg-bolnitsi.json) | 487 | 64 KB | [CSV](bg-bolnitsi_BG.csv) | [Excel](bg-bolnitsi_BG.xlsx) | [View](https://listbase.org/bg/health/bg-bolnitsi/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/health/bg-zabolekari.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/health/)
