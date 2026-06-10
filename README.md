# ResonanceLens — Website

**EN** | [DE](#deutsch)

The public website for **ResonanceLens** — a structural early-warning framework for complex networked systems, oriented toward EU financial infrastructure and DORA operational resilience.

🌐 **Live:** [resonancelens.de](https://resonancelens.de)
🧪 **Interactive demo:** [resonancelens.streamlit.app](https://resonancelens.streamlit.app/)
💻 **Showcase code:** [github.com/huesnue/resonancelens-showcase](https://github.com/huesnue/resonancelens-showcase)

---

## What this repository is

This repository contains the static website served at `resonancelens.de` via GitHub Pages. It is the public front door to the project — not the model itself.

It hosts three things:

- **Landing page** — what ResonanceLens is, in one read.
- **Documentation** — how the showcase works: the four structural quantities, the four-state logic, and the eight scenarios.
- **Whitepaper series** — papers on structural early-warning and operational resilience.

The site demonstrates **emergent system behaviour only**. The underlying model mechanics remain proprietary and are not part of this repository.

## Structure

```
.
├── index.html              # Landing page
├── docs/
│   ├── index.html          # Documentation
│   └── whitepaper.html     # Whitepaper series
└── assets/                 # Styles, logo, favicons, whitepaper PDFs
```

## Local development

No build step and no dependencies — it is plain HTML, CSS and SVG. Open `index.html` in a browser, or serve the folder for correct relative paths:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

Pushing to `main` publishes automatically via GitHub Pages. The custom domain is configured through the `CNAME` file and DNS records; HTTPS is enforced.

## Language

Interface text is English-first with a German toggle. The whitepapers are currently in German; English versions are planned.

---

<a name="deutsch"></a>

# ResonanceLens — Website

[EN](#resonancelens--website) | **DE**

Die öffentliche Website für **ResonanceLens** — ein strukturelles Frühwarn-Framework für komplexe vernetzte Systeme, ausgerichtet auf EU-Finanzinfrastruktur und operative Resilienz nach DORA.

🌐 **Live:** [resonancelens.de](https://resonancelens.de)
🧪 **Interaktive Demo:** [resonancelens.streamlit.app](https://resonancelens.streamlit.app/)
💻 **Showcase-Code:** [github.com/huesnue/resonancelens-showcase](https://github.com/huesnue/resonancelens-showcase)

---

## Was dieses Repository ist

Dieses Repository enthält die statische Website, die unter `resonancelens.de` über GitHub Pages ausgeliefert wird. Sie ist der öffentliche Eingang zum Projekt — nicht das Modell selbst.

Sie beherbergt drei Dinge:

- **Landing Page** — was ResonanceLens ist, in einem Durchgang.
- **Dokumentation** — wie das Showcase funktioniert: die vier strukturellen Größen, die vierstufige Zustandslogik und die acht Szenarien.
- **Whitepaper-Serie** — Beiträge zu struktureller Frühwarnung und operativer Resilienz.

Die Website zeigt **ausschließlich emergentes Systemverhalten**. Die zugrunde liegende Modellmechanik bleibt proprietär und ist nicht Teil dieses Repositories.

## Struktur

```
.
├── index.html              # Landing Page
├── docs/
│   ├── index.html          # Dokumentation
│   └── whitepaper.html     # Whitepaper-Serie
└── assets/                 # Styles, Logo, Favicons, Whitepaper-PDFs
```

## Lokale Entwicklung

Kein Build-Schritt, keine Abhängigkeiten — reines HTML, CSS und SVG. Öffne `index.html` im Browser oder serviere den Ordner für korrekte relative Pfade:

```bash
python3 -m http.server 8000
# dann http://localhost:8000 öffnen
```

## Deployment

Ein Push auf `main` veröffentlicht automatisch über GitHub Pages. Die eigene Domain ist über die `CNAME`-Datei und DNS-Einträge konfiguriert; HTTPS ist erzwungen.

## Sprache

Der Oberflächentext ist Englisch-zuerst mit einem Deutsch-Umschalter. Die Whitepaper sind derzeit auf Deutsch; englische Fassungen sind geplant.

---

© Hüsnü Turkaç · ResonanceLens™ — DPMA, Nizza-Kl. 9 / 41 / 42