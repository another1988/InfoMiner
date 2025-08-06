# InfoMiner

**InfoMiner** je platforma pro **automatizovaný sběr, analýzu a monetizaci dat o firmách, trzích a ESG aktivitách**.

Projekt je navržen jako modulární systém, který propojuje pokročilé crawlování, NLP analýzu, skórování ESG faktorů a následný prodej či sdílení dat prostřednictvím decentralizovaného datového tržiště.

---

## 🎯 Cíle projektu

- 📊 Automatizovaný sběr dat z veřejných i neveřejných zdrojů
- ♻️ Výpočet ESG skóre a environmentálních metrik
- 🧠 NLP analýza dokumentů a tiskových zpráv
- 🧩 Budování veřejného datového tržiště pro přístup k těmto informacím
- 🔁 Možnost rozšíření i na jiné typy dat (např. stavební, investiční, politické)

---

## 🧱 Moduly projektu

| Název složky        | Popis                                                             |
|---------------------|--------------------------------------------------------------------|
| `crawler-esg/`      | Crawler na weby a zdroje s ESG obsahem (tiskové zprávy, registry) |
| `esg-scorer/`       | Výpočet ESG skóre na základě vstupních dat                        |
| `nlp-analyzer/`     | NLP rozbor dokumentů a klasifikace témat                          |
| `data-marketplace/` | Marketplace s přístupem ke staženým a vypočteným datům           |
| `integrations/`     | Napojení na externí API, firmy, databáze                          |

---

## 🛠️ Technologie

- Python (crawler, NLP, scoring)
- FastAPI (API backend)
- PostgreSQL / Supabase (DB, export dat)
- React / Next.js (front-end + marketplace)
- GitHub + Sweep / Claude (AI-asistovaný vývoj)

---

## 📌 Licence

TBD – pravděpodobně dual (komerční + open dataset výstupy).

---
