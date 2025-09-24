# SteadyD3sk Hub

Offline-first tools for **Engineers, SMEs, and Creatives** — built to be lightweight, accessible, and fully functional without internet.

---

## 🚀 Vision
SteadyD3sk is a growing collection of **standalone HTML tools** and **PWA-ready apps** designed for:
- Engineers (structural, civil, geotech) needing quick calculators aligned with SANS / Eurocodes.
- SMEs looking for practical utilities like invoice generators, stock trackers, and converters.
- Creatives and students who benefit from simple but powerful offline-first tools.

Our guiding principle: **Don’t let the stress enjoy itself.**

---

## 📂 Repository Structure
```
steadyd3sk/
│
├─ index.html            # Hub page (reworked)
├─ assets/               # Shared logos, fonts, icons, images
│   ├─ logo.svg
│   └─ styles.css (optional global)
├─ tools/                # All standalone tools
│   ├─ invoice-generator.html
│   ├─ currency-tax.html
│   ├─ inventory-counter.html
│   ├─ unit-converter.html
│   ├─ steel-sections.html
│   ├─ daily-log.html
│   ├─ graphing-calc.html
│   └─ csv-roulette.html
└─ README.md             # This file
```

---

## 🛠 Coding Rules
SteadyD3sk follows strict internal rules for all tools:

- **Offline-first priority**: No external CDNs. All fonts, icons, and assets must be local.
- **Self-contained tools**: Each tool is a complete `.html` file with embedded CSS + JS.
- **No placeholders**: Every feature must be functional — no dummy content.
- **Fail-safe**: Tools must always render; critical UI must never be blank.
- **Comments required**: Functions, loops, and calculations must have inline explanations.
- **Accessibility**: Semantic HTML, high contrast, and mobile-friendly layouts.

---

## 📌 Current Tools
### SME Toolkit
- **Invoice Generator** – Create and export invoices as PDF/CSV.
- **Currency & Tax Calculator** – Manual conversions + VAT/Tax calculations.
- **Inventory Counter** – Track stock levels, add/remove items, export CSV.

### Engineering Toolkit
- **Unit Converter** – Length, area, volume, weight, pressure.
- **Steel Sections** – Browse SANS/Eurocode profiles, calculate properties.
- **Daily Log** – Offline project log with JSON/CSV export.

### Showcase
- **Graphing Calculator** – Visualize functions in 2D/3D.
- **CSV Roulette** – Upload/paste CSV and pick random entries.

---

## 🔮 Roadmap
- **v1.0** – Hub reworked + 3 SME tools.
- **v1.1** – More engineering calculators (RC beam/slab, BOQ estimator).
- **v2.0** – PWA support (installable tools, offline caching).
- **Future** – JSON-based code toggle (SANS ↔ Eurocode), African PWA Store integration.

---

## 📝 License
All tools are **free to use** under a donation-supported model. Donations help fund development and access to standards.

---

## 💡 Credits
Built by **SteadyD3sk** — AI-assisted, but always human-directed.
