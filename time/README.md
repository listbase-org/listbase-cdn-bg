# Време и календар (Time & Calendar)

4 datasets — 1,482 records

> Browse at [listbase.org/bg/time/](https://listbase.org/bg/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Български официални и училищни празници (1991–2030)](bg-oficialni-i-uchilishchni-praznitsi.json) | 618 | 345 KB | [CSV](bg-oficialni-i-uchilishchni-praznitsi_BG.csv) | [Excel](bg-oficialni-i-uchilishchni-praznitsi_BG.xlsx) | [View](https://listbase.org/bg/time/bg-oficialni-i-uchilishchni-praznitsi/) |
| [Български празници — пълен каталог (всички категории), 3 езика (1991–2030)](bg-praznitsi-completos.json) | 618 | 313 KB | [CSV](bg-praznitsi-completos_BG.csv) | [Excel](bg-praznitsi-completos_BG.xlsx) | [View](https://listbase.org/bg/time/bg-praznitsi-completos/) |
| [Български официални празници — многоезичен (OpenHolidays editorial)](bg-praznitsi-multiezikov.json) | 175 | 92 KB | [CSV](bg-praznitsi-multiezikov_BG.csv) | [Excel](bg-praznitsi-multiezikov_BG.xlsx) | [View](https://listbase.org/bg/time/bg-praznitsi-multiezikov/) |
| [Български училищни ваканции — многоезичен (OpenHolidays editorial)](bg-uchilishchni-vakantsii.json) | 71 | 38 KB | [CSV](bg-uchilishchni-vakantsii_BG.csv) | [Excel](bg-uchilishchni-vakantsii_BG.xlsx) | [View](https://listbase.org/bg/time/bg-uchilishchni-vakantsii/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/time/bg-oficialni-i-uchilishchni-praznitsi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/time/)
