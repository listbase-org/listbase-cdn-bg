# Спорт (Sports)

1 datasets — 1,997 records

> Browse at [listbase.org/bg/sports/](https://listbase.org/bg/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Шампионска лига на УЕФА — всички мачове от основната фаза 2011/12–2025/26 (1997)](bg-shampionska-liga-na-uefa-machove.json) | 1,997 | 1149 KB | [CSV](bg-shampionska-liga-na-uefa-machove_BG.csv) | [Excel](bg-shampionska-liga-na-uefa-machove_BG.xlsx) | [View](https://listbase.org/bg/sports/bg-shampionska-liga-na-uefa-machove/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.bg.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.bg.listbase.org/sports/bg-shampionska-liga-na-uefa-machove.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/bg/sports/)
