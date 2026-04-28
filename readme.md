# Nobleo PDF Tools

Een lichtgewicht, browser-gebaseerde toolsuite voor Nobleo Bouw en Infra. Alle verwerking vindt volledig plaats in de browser — uw documenten worden nooit geüpload naar een server.

## 🌐 Live Applicatie

https://joelvanherwaarden.github.io/PDFVersionMerger/

---

## 🧰 Tools

### ↔️ Document Vergelijker
Vergelijk twee PDF-versies interactief zij-aan-zij met een versleepbare slider. Navigeer per pagina, toggle naar volledige schermbreedte en download de volledige vergelijking als landscape PDF.

### 📎 PDF Samenvoegen
Upload meerdere PDF-bestanden, orden ze via drag-and-drop en voeg ze samen tot één document. Toont miniaturen en paginaaantallen per bestand. Originele paginaformaten blijven behouden.

### 📐 Hoek & Helling Berekening
Bereken hoeken en hellingspercentage van een rechthoekige driehoek via een verhouding (bijv. 1:50) of een helling (%). Inclusief interactieve SVG-visualisatie en berekeningsstappen.

---

## 🚀 Kenmerken

- **100% Privacy** — Alle verwerking vindt client-side plaats. Geen uploads, geen tracking.
- **Dark Mode** — Schakel eenvoudig tussen licht en donker thema.
- **Zonder installatie** — Werkt direct in de browser, offline beschikbaar nadat de pagina is geladen.
- **Dynamische schaling** — Houdt rekening met verschillende paginalengtes tussen documenten.

---

## 🛠️ Technologie

| Bibliotheek | Gebruik |
|---|---|
| [pdf-lib](https://pdf-lib.js.org/) | PDF genereren en samenvoegen |
| [PDF.js](https://mozilla.github.io/pdf.js/) | PDF-pagina's renderen als canvas |
| Vanilla JavaScript | Alle logica en UI-interacties |
| CSS Custom Properties | Dynamisch themasysteem (licht/donker) |
| SVG | Interactieve driehoeksvisualisatie |

---

## 📖 Hoe het werkt

### Document Vergelijker
1. Selecteer een **Referentie Document** (verschijnt links).
2. Selecteer een **Wijziging / Variant** (verschijnt rechts).
3. Klik op **Genereer Vergelijking** en gebruik de slider om pagina's te vergelijken.
4. Optioneel: download de volledige vergelijking als landscape PDF.

### PDF Samenvoegen
1. Upload meerdere PDF-bestanden via klikken of drag-and-drop.
2. Herschik de volgorde via drag-and-drop.
3. Klik op **Samenvoegen & Downloaden**.

### Hoek & Helling Berekening
1. Kies invoermodus: **Verhouding (1:n)** of **Helling (%)**.
2. Vul de waarde(n) in — resultaten verschijnen direct.
3. Bekijk de interactieve driehoeksvisualisatie en de berekeningsstappen.

---

## 🔒 Beveiliging & Privacy

- Vertrouwelijke bedrijfsgegevens blijven lokaal op uw machine.
- Geen internetverbinding nodig nadat de pagina is geladen.
- Geen cookies of tracking-scripts voor documentgegevens.

---

## 👨‍💻 Ontwikkeling

Vibe-coded 🤖

© 2026 Nobleo Bouw en Infra — [www.nobleo-infra.nl](https://www.nobleo-infra.nl)
