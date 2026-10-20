# ListBase CDN — Български (bg)

Open dataset collection for **Български** (Bulgarian).
409 datasets across 16 categories with 188,203 total records.

> Browse and download at [https://listbase.org/bg/](https://listbase.org/bg/)

## Categories

| Category | Datasets |
|----------|----------|
| [Култура и религия (Culture & Religion)](culture/) | 11 |
| [Образование (Education)](education/) | 30 |
| [Околна среда (Environment)](environment/) | 9 |
| [Финанси и търговия (Finance & Trade)](finance/) | 4 |
| [Храна (Food & Nutrition)](food/) | 1 |
| [География (Geography)](geography/) | 72 |
| [Здраве (Health)](health/) | 2 |
| [История (History)](history/) | 1 |
| [Език (Language)](language/) | 1 |
| [Справочник (Reference)](reference/) | 174 |
| [Спорт (Sports)](sports/) | 1 |
| [Технологии (Technology)](tech/) | 1 |
| [Време и календар (Time & Calendar)](time/) | 4 |
| [Туризъм (Tourism)](tourism/) | 3 |
| [Транспорт (Transport)](transport/) | 74 |
| [Мерни единици (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/bg/](https://listbase.org/bg/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.bg.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.bg.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.bg.listbase.org/geography/th-central-provinces_BG.xlsx
curl -O https://cdn.bg.listbase.org/geography/th-central-provinces_BG.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.bg.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.bg.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_BG.csv   # CSV download
│   └── {dataset}_BG.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
