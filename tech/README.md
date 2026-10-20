# Технологии (Technology)

1 datasets — 25 records

> Browse at [listbase.org/bg/tech/](https://listbase.org/bg/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Библиотеки в България](bg-biblioteki.json) | 25 | 12 KB | [CSV](bg-biblioteki_BG.csv) | [Excel](bg-biblioteki_BG.xlsx) | [View](https://listbase.org/bg/tech/bg-biblioteki/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/tech/bg-biblioteki.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/tech/)
