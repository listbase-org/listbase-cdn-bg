# Храна (Food & Nutrition)

1 datasets — 502 records

> Browse at [listbase.org/bg/food/](https://listbase.org/bg/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Пекарни в България](bg-pekarni.json) | 502 | 54 KB | [CSV](bg-pekarni_BG.csv) | [Excel](bg-pekarni_BG.xlsx) | [View](https://listbase.org/bg/food/bg-pekarni/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/food/bg-pekarni.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/food/)
