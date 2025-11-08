# social-apptastisch-site

Eine einfache Jekyll-Website für GitHub Pages mit Amazon Affiliate Links.

## Funktionen

- Schlichte Jekyll-Seite optimiert für GitHub Pages
- Zentrale Verwaltung von Affiliate Links in einer Datendatei
- Responsive Design mit modernem Look
- Automatische Anzeige aller Links als Liste

## Struktur

- `_config.yml` - Jekyll Konfiguration
- `_data/affiliate_links.yml` - Datendatei für Affiliate Links
- `_layouts/default.html` - Standard-Layout mit Styling
- `index.md` - Startseite mit Link-Liste

## Affiliate Links hinzufügen

Bearbeite die Datei `_data/affiliate_links.yml` und füge neue Links hinzu:

```yaml
- title: "Dein Produkttitel"
  url: "https://www.amazon.de/dp/PRODUKTID?tag=deinaffid-21"
```

## Lokale Entwicklung

```bash
# Jekyll installieren (falls nicht vorhanden)
gem install bundler jekyll

# Site lokal starten
jekyll serve

# Im Browser öffnen: http://localhost:4000
```

## GitHub Pages Deployment

Die Website wird automatisch von GitHub Pages gebaut und veröffentlicht, wenn sie in den Main-Branch gepusht wird. Aktiviere GitHub Pages in den Repository-Einstellungen.