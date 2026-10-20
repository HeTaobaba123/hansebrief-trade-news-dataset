# HanseBrief China Trade News Bilingual Dataset

The largest open-source bilingual (Chinese-English) dataset of China-focused trade news, sourced from [HanseBrief](https://hansebrief.com) — the leading China-MENA trade intelligence platform.

## Versions

### v2.0.0 (Latest) — Trilingual Sample Edition
- **v1 core**: 16,996 bilingual (Chinese-English) articles (full dataset)
- **v2 addition**: 2,000 articles with **Arabic translations** (`title_ar`, `summary_ar`) — stratified sample covering 298 (category, source) buckets for maximum diversity

### v1.0.0 — Bilingual Full Edition
- 16,996 articles with `title_en`, `title_zh`, `summary_en`, `summary_zh`

## Files (v2)

- `hansebrief-news-zh-en-ar-2000.json` — 2,000 trilingual articles (ZH+EN+AR), human-reviewed Arabic
- `hansebrief-news-zh-en-ar-2000.json.gz` — gzip compressed (recommended)
- (v1 files retained on the v1.0.0 release page)

## Schema (v2 trilingual records)

| Field | Description |
|---|---|
| `id`, `guid`, `url` | Identifiers |
| `source` | News outlet (Gelonghui, Yicai, 36Kr, AlJazeera, CNBC, FT, Caixin, …) |
| `category` | market / emerging / supply_chain / metals / macro / agri / energy / policy / fx / china_policy |
| `lang` | Detected source language |
| `published_at` | ISO-8601 timestamp |
| `title_en`, `summary_en` | English |
| `title_zh`, `summary_zh` | Simplified Chinese |
| `title_ar`, `summary_ar` | **Modern Standard Arabic (MSA)** — new in v2 |
| `commodities`, `events` | Structured tags |

## Scale

- **16,996 articles** full bilingual corpus
- **2,000 articles** with Arabic (12% sample, stratified)
- **30+ sources** including Gelonghui (5,382), Yicai (2,103), 36Kr (1,290), AlJazeera (737), CNBC (369), FT (286), Caixin (339)
- **Time span**: 2024 – present

## Use Cases

- **Trilingual MT** (ZH-EN-AR) in trade/finance domain (extremely low-resource)
- **Financial NLP**: sentiment, event extraction, commodity tracking
- **China-MENA trade research** and Belt & Road studies
- **Market intelligence** and recommendation systems

## License

**CC0 1.0 Public Domain**. Use freely for research or commercial purposes.

## Source

[HanseBrief](https://hansebrief.com) — China-MENA trade intelligence platform.

GitHub: https://github.com/HeTaobaba123/hansebrief-trade-news-dataset
Kaggle: https://www.kaggle.com/datasets/hetaobaba/hansebrief-trade-news-dataset
