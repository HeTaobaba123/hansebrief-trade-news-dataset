# HanseBrief China-Arab Trade News Dataset

The **largest open-source bilingual (Chinese-English) dataset of China-focused trade news** — 16,996 curated articles from [HanseBrief](https://hansebrief.com), the leading China-MENA trade intelligence platform. Each article has both **Chinese and English titles + summaries**, plus rich metadata including category, source, commodities, and publication date.

An **Arabic translation sample (2,000 articles)** is included as a preview of the full Arabic edition (coming Q1 2027).

## Files

| File | Records | Description |
|---|---|---|
| `hansebrief-news-zh-en.json` | 16,996 | Full bilingual (Chinese-English) news dataset |
| `hansebrief-news-sample-2000-ar.json` | 2,000 | Stratified sample with Arabic translations (title + summary) |

**Total size**: ~26 MB | **License**: CC0 1.0

## Schema

```json
{
  "id": 17054,
  "guid": "c014dd106112b88b9e50144f2038e2d79dfb2ada",
  "title_en": "Hydrogen projects take slice of €3.4bn EU Innovation Fund round",
  "title_zh": "氢能项目获欧盟34亿欧元创新基金",
  "title_ar": "مشاريع الهيدروجين تحصل على حصة من صندوق الابتكار الأوروبي بقيمة 3.4 مليار يورو",
  "summary_en": "Hydrogen projects take slice of €3.4bn EU Innovation Fund...",
  "summary_zh": "欧盟创新基金本轮共拨款34亿欧元，氢能项目获得部分资金...",
  "summary_ar": "حصلت مشاريع الهيدروجين على جزء من جولة صندوق الابتكار الأوروبي...",
  "url": "https://...",
  "source": "gasworld",
  "category": "emerging",
  "lang": "en",
  "published_at": "2026-10-19T14:26:09+00:00",
  "commodities": ["hydrogen"],
  "events": []
}
```

## Coverage

### Categories (TOP 10)
| Category | Articles | Description |
|---|---|---|
| `market` | 10,601 | General market news |
| `emerging` | 1,911 | Emerging sectors (hydrogen, EV, AI) |
| `supply_chain` | 867 | Logistics, ports, shipping |
| `metals` | 860 | Steel, copper, aluminum |
| `macro` | 573 | Macroeconomy, GDP, trade data |
| `agri` | 571 | Agriculture, food, grains |
| `energy` | 497 | Oil, gas, renewables |
| `policy` | 469 | Government policy, regulations |
| `fx` | 180 | Currency, RMB, exchange rates |
| `china_policy` | 162 | China-specific policies |

### Sources (TOP 10)
| Source | Articles | Type |
|---|---|---|
| Gelonghui | 5,382 | Chinese financial news |
| Yicai | 2,103 | Chinese business media |
| 36Kr | 1,290 | Chinese tech/startup |
| AlJazeera | 737 | Arabic international |
| WallstreetCN | 546 | Chinese Wall Street |
| CNBC | 369 | US business |
| Caixin | 339 | Chinese premium |
| FT | 286 | Financial Times |
| GN-gasoline | 288 | Commodity tracker |
| GN-diesel | 266 | Commodity tracker |

### Language Distribution
- **Chinese (zh)**: 9,660 articles (57%)
- **English (en)**: 7,329 articles (43%)
- **Portuguese (pt)**: 7 articles

## Unique Features

### 1. Scale & Recency
- **16,996 articles** — largest China-trade bilingual news dataset
- **Daily updates** from 30+ sources (Chinese + English + Arabic)
- **Time span**: continuous from 2024 to present

### 2. True Bilingual
- Every article has both **Chinese and English** titles + summaries
- Professionally machine-translated with human curation
- Preserves business terminology and numerical accuracy

### 3. Trade-Focused
- **Commodity tracking**: each article tagged with relevant commodities (hydrogen, steel, soybeans, oil, etc.)
- **Category classification**: market/emerging/supply_chain/metals/macro/agri/energy/policy/fx/china_policy
- **Source diversity**: Chinese financial media + international wires + Arabic outlets

### 4. Arabic Edition (Preview)
- 2,000-article sample with **Arabic translations** (title + summary)
- Stratified sampling preserves category/source diversity
- Full Arabic edition planned Q1 2027

## Use Cases

- **Machine translation** — Chinese-English-Arabic trade/finance domain
- **Financial NLP** — sentiment analysis, event extraction, commodity tracking
- **Trade intelligence** — China-MENA trade research
- **Market analysis** — commodity price drivers, policy impact
- **Recommendation systems** — multilingual news ranking
- **Academic research** — Chinese economic discourse, Belt and Road studies
- **Chatbots** — trade/finance Arabic AI assistants

## Methodology

- **Source**: HanseBrief (https://hansebrief.com) production database
- **Crawling**: 30+ RSS/API sources (Chinese + English + Arabic)
- **Translation**: DeepSeek-V3 with trade/finance domain prompts
- **Arabic**: Formal Modern Standard Arabic (فصحى) with business register
- **Quality**: Verified pipeline, numerical accuracy checked

## License

**CC0 1.0 Public Domain** — free for any use, commercial or non-commercial.

## Citation

```bibtex
@dataset{hansebrief_china_trade_news_2026,
  title={HanseBrief China-Arab Trade News Dataset},
  author={HanseBrief},
  year={2026},
  publisher={Kaggle},
  url={https://github.com/HeTaobaba123/hansebrief-trade-news-dataset},
  note={16,996 bilingual articles + 2,000 Arabic sample, CC0 1.0}
}
```

## Sister Datasets

- [Arabic-Chinese Web Novel Metadata](https://github.com/HeTaobaba123/arabic-chinese-novels-dataset) — 7,476 novels
- [TCM Arabic-Chinese Bilingual Dataset](https://github.com/HeTaobaba123/tcm-arabic-dataset-) — Traditional Chinese Medicine
- [DaoPath Taoist Metaphysics](https://github.com/HeTaobaba123/daopath-terms-dataset) — I Ching, BaZi
- [ToolCraftX Arabic AI Prompts](https://github.com/HeTaobaba123/toolcraftx-arabic-prompts) — 11 prompt templates

## Roadmap

- **v1 (this release)**: 16,996 bilingual (ZH-EN) articles + 2,000 Arabic sample
- **v2 (Q1 2027)**: Full Arabic edition (all 16,996 articles)
- **v3 (Q2 2027)**: Real-time daily updates via API
- **v4 (Q3 2027)**: Weekly report dataset (Chinese-English-Arabic summaries)

## Contact

- Website: https://hansebrief.com
- Issues: [GitHub Issues](https://github.com/HeTaobaba123/hansebrief-trade-news-dataset/issues)
