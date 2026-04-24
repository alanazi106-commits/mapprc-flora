# Saudi Flora Register

A web-based register of **2,760 vascular plant species** recorded across Saudi
Arabia, maintained by the **Medicinal, Aromatic and Poisonous Plant Research
Center (MAPPRC)**, College of Pharmacy, King Saud University.

> **🌐 Live site:** _After you enable GitHub Pages, paste your URL here —
> something like_ `https://YOUR-USERNAME.github.io/mapprc-flora/`

---

## About the register

The Saudi Flora Register consolidates decades of field collection, herbarium
study and systematic taxonomic revision into a single authoritative reference.
Every entry is cross-referenced against the World Checklist of Vascular Plants
and enriched with pharmacological, phytochemical and ethnobotanical data
curated by the Center's research staff.

| Metric | Count |
| --- | --- |
| **Species recorded** | 2,760 |
| **Plant families** | 157 |
| **Endemic to Saudi Arabia** | 100 |
| **With medicinal records** | 487 |
| Trees · Shrubs · Herbs | 211 · 376 · 1,720 |
| Native · Exotic · Naturalized | 2,339 · 417 · 13 |

**Top 10 families:** Poaceae · Fabaceae · Asteraceae · Amaranthaceae ·
Lamiaceae · Brassicaceae · Apocynaceae · Malvaceae · Euphorbiaceae ·
Caryophyllaceae.

---

## Features

- 🔍 Live search across scientific names, families, common names, and Arabic
  vernacular names
- 🌿 Filter by habit (tree, shrub, herb, climber, grass), use (aromatic, bee,
  forage, firewood, toxic), medicinal records, endemic species
- 📖 Full per-species detail panel with taxonomic authority, botanical
  description, and ethnomedicinal record
- 🎨 Editorial herbarium-register aesthetic with bilingual display (English
  Latin + Arabic vernacular in Amiri typeface)
- 🧬 Integrated phytochemistry reference (TLC chromatogram shown on hero)
- 📱 Works on desktop, tablet, and mobile browsers

---

## Updating the site

To update species data or make design changes:

1. **Get the latest source:** `src/App.jsx` from the project archive
2. **Ask Claude** (or any AI assistant) to make your changes — e.g. _"add a
   Families page"_, _"here's an updated Excel with new species"_
3. **Replace** `index.html` in this repo with the new build
4. The site redeploys in ~30 seconds

The raw data source is `Saudi_plants-list_FILLED.xlsx` (not included in this
public repo) — merged from three sheets: taxonomy, extracted literature, and
pharmacology studies.

---

## Technical details

- Single-file web app: one `index.html`, no build step required
- **React 18** (loaded from `unpkg.com` CDN)
- **No backend** — the 2,760-species database is embedded in the HTML
- Typography: Fraunces, DM Sans, JetBrains Mono, Amiri (Google Fonts)

File size: ~810 KB (includes embedded logos, database, and compiled app)

---

## Credits

- **Content and botanical data:** MAPPRC research team, King Saud University
- **Principal Investigator:** Prof. Abdullah R. Alanzi
- **Institution:** College of Pharmacy, King Saud University, Riyadh

---

## License

Institutional logos are property of their respective owners. Code and design
are for internal use by MAPPRC / KSU College of Pharmacy.
