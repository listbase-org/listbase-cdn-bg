# Туризъм (Tourism)

3 datasets — 4,695 records

> Browse at [listbase.org/bg/tourism/](https://listbase.org/bg/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Хотели в България](bg-hoteli.json) | 3,049 | 322 KB | [CSV](bg-hoteli_BG.csv) | [Excel](bg-hoteli_BG.xlsx) | [View](https://listbase.org/bg/tourism/bg-hoteli/) |
| [Туристически атракции в България](bg-turisticheski-atraktsii.json) | 830 | 96 KB | [CSV](bg-turisticheski-atraktsii_BG.csv) | [Excel](bg-turisticheski-atraktsii_BG.xlsx) | [View](https://listbase.org/bg/tourism/bg-turisticheski-atraktsii/) |
| [Къщи за гости в България](bg-kashti-za-gosti.json) | 816 | 90 KB | [CSV](bg-kashti-za-gosti_BG.csv) | [Excel](bg-kashti-za-gosti_BG.xlsx) | [View](https://listbase.org/bg/tourism/bg-kashti-za-gosti/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/tourism/bg-hoteli.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/tourism/)
