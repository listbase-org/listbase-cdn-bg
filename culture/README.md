# Култура и религия (Culture & Religion)

11 datasets — 729 records

> Browse at [listbase.org/bg/culture/](https://listbase.org/bg/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Национални туристически обекти на България (100 НТО, разширен списък)](bg-natsionalni-turisticheski-obekti.json) | 217 | 103 KB | [CSV](bg-natsionalni-turisticheski-obekti_BG.csv) | [Excel](bg-natsionalni-turisticheski-obekti_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-natsionalni-turisticheski-obekti/) |
| [Манастири в България](bg-manastiri.json) | 137 | 51 KB | [CSV](bg-manastiri_BG.csv) | [Excel](bg-manastiri_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-manastiri/) |
| [Музеи в България (Museums in Bulgaria)](bg-muzei.json) | 117 | 29 KB | [CSV](bg-muzei_BG.csv) | [Excel](bg-muzei_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-muzei/) |
| [Крепости в България](bg-kreposti.json) | 105 | 36 KB | [CSV](bg-kreposti_BG.csv) | [Excel](bg-kreposti_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-kreposti/) |
| [Театри в България](bg-teatri.json) | 40 | 17 KB | [CSV](bg-teatri_BG.csv) | [Excel](bg-teatri_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-teatri/) |
| [Гробища в България](bg-grobishta.json) | 31 | 13 KB | [CSV](bg-grobishta_BG.csv) | [Excel](bg-grobishta_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-grobishta/) |
| [Джамии в България](bg-dzhamii.json) | 30 | 12 KB | [CSV](bg-dzhamii_BG.csv) | [Excel](bg-dzhamii_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-dzhamii/) |
| [Кина в България](bg-kina.json) | 18 | 8 KB | [CSV](bg-kina_BG.csv) | [Excel](bg-kina_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-kina/) |
| [Синагоги в България](bg-sinagogi.json) | 14 | 7 KB | [CSV](bg-sinagogi_BG.csv) | [Excel](bg-sinagogi_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-sinagogi/) |
| [Фарове в България](bg-farove.json) | 10 | 5 KB | [CSV](bg-farove_BG.csv) | [Excel](bg-farove_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-farove/) |
| [Обекти на световното наследство на ЮНЕСКО в България](bg-obekti-na-svetovnoto-nasledstvo-unesco.json) | 10 | 12 KB | [CSV](bg-obekti-na-svetovnoto-nasledstvo-unesco_BG.csv) | [Excel](bg-obekti-na-svetovnoto-nasledstvo-unesco_BG.xlsx) | [View](https://listbase.org/bg/culture/bg-obekti-na-svetovnoto-nasledstvo-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/culture/bg-natsionalni-turisticheski-obekti.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/culture/)
