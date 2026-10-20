# Околна среда (Environment)

9 datasets — 839 records

> Browse at [listbase.org/bg/environment/](https://listbase.org/bg/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Електроцентрали в България](bg-elektrocentrali.json) | 414 | 212 KB | [CSV](bg-elektrocentrali_BG.csv) | [Excel](bg-elektrocentrali_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-elektrocentrali/) |
| [Слънчеви електроцентрали в България](bg-slanchevi-elektrocentrali.json) | 336 | 170 KB | [CSV](bg-slanchevi-elektrocentrali_BG.csv) | [Excel](bg-slanchevi-elektrocentrali_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-slanchevi-elektrocentrali/) |
| [Водноелектрически централи в България](bg-vodni-elektrocentrali.json) | 30 | 20 KB | [CSV](bg-vodni-elektrocentrali_BG.csv) | [Excel](bg-vodni-elektrocentrali_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-vodni-elektrocentrali/) |
| [Вятърни електроцентрали в България](bg-vyatarni-elektrocentrali.json) | 17 | 12 KB | [CSV](bg-vyatarni-elektrocentrali_BG.csv) | [Excel](bg-vyatarni-elektrocentrali_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-vyatarni-elektrocentrali/) |
| [Мерни единици: energy (14)](bg-merni-edinitsi-energy.json) | 14 | 6 KB | [CSV](bg-merni-edinitsi-energy_BG.csv) | [Excel](bg-merni-edinitsi-energy_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-merni-edinitsi-energy/) |
| [Лигнитни електроцентрали в България](bg-lignitni-elektrocentrali.json) | 9 | 9 KB | [CSV](bg-lignitni-elektrocentrali_BG.csv) | [Excel](bg-lignitni-elektrocentrali_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-lignitni-elektrocentrali/) |
| [Ядрени централи в България](bg-yadreni-tsentrali.json) | 8 | 6 KB | [CSV](bg-yadreni-tsentrali_BG.csv) | [Excel](bg-yadreni-tsentrali_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-yadreni-tsentrali/) |
| [Каменовъглени електроцентрали в България](bg-kamenovagleni-elektrocentrali.json) | 6 | 7 KB | [CSV](bg-kamenovagleni-elektrocentrali_BG.csv) | [Excel](bg-kamenovagleni-elektrocentrali_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-kamenovagleni-elektrocentrali/) |
| [Мерни единици: temperature (5)](bg-merni-edinitsi-temperature.json) | 5 | 3 KB | [CSV](bg-merni-edinitsi-temperature_BG.csv) | [Excel](bg-merni-edinitsi-temperature_BG.xlsx) | [View](https://listbase.org/bg/environment/bg-merni-edinitsi-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/environment/bg-elektrocentrali.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/environment/)
