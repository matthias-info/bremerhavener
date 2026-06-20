# Kaltwasser- & Abwasserkosten-Verteiler

Ein interaktiver Rechner zur **fairen Verteilung** von Wasserkosten in einem 3-Familien-Altbau (EG, OG, DG) ohne Einzelwasserzähler.

Entwickelt für den konkreten Anwendungsfall mit swb-Abrechnung (Bremen).

## Merkmale

- Faire Verteilung unter Berücksichtigung der realen **Anwesenheit** (OG-Mieter nur ca. 10 Tage/Monat)
- Automatische **Schätzung der Spüle EG** basierend auf OG- und DG-Verbrauch
- Berücksichtigung des **Grundpreises** (wird gleichmäßig durch 3 geteilt)
- Verbrauchsabhängige Kosten (Frischwasser-Rest + Abwasser) nach realem Verbrauchsanteil
- Ausgabe **monatlich** und **jährlich**
- Vollständig offline-fähig (eine einzige HTML-Datei)

## Verwendung

1. Lade die Datei [`wasser-verteiler.html`](wasser-verteiler.html) herunter
2. Öffne sie in einem beliebigen Browser (kein Server nötig)
3. Trage deine Rechnungsdaten und Verbräuche ein
4. Die Berechnung erfolgt automatisch

## Screenshots

*(Hier kannst du später Screenshots einfügen)*

## Technik

- Reine HTML + CSS + JavaScript (keine externen Abhängigkeiten)
- Mobilfreundlich
- Automatische Berechnung

## Prompt zum Wiederherstellen / Weiterentwickeln

Falls du den Rechner später neu generieren oder erweitern möchtest, kannst du folgenden Prompt verwenden:

```markdown
Du bist ein erfahrener Full-Stack-Entwickler und erstellst einen vollständigen, eigenständigen HTML + JavaScript Rechner zur fairen Verteilung von Kaltwasser- und Abwasserkosten in einem 3-Familien-Altbau (EG, OG, DG).

**Anforderungen:**

- Rechnungssummen Frischwasser und Abwasser **pro Jahr**
- Grundpreis Frischwasser **pro Jahr**
- Anwesenheitstage pro Monat (EG, OG, DG – OG standardmäßig 10 Tage)
- Verbräuche pro Monat: Haus Kaltwasser gesamt, Waschmaschinen, Waschbecken kalt/warm, Spülen kalt/warm
- Automatische Schätzung der Spüle EG (70% DG + 30% OG-Tagesdurchschnitt)
- Grundpreis wird gleichmäßig durch 3 geteilt
- Verbrauchsabhängiger Teil + Abwasser nach realem Verbrauchsanteil (inkl. Anwesenheit)
- Übersichtliche Tabellen für Verbrauch (monatlich), Kosten monatlich und jährlich
- Moderne, saubere Gestaltung

Erstelle den vollständigen, kopierbaren HTML-Code mit realistischen Voreinstellungen (ca. 187 € Frischwasser, 146 € Abwasser, 55,80 € Grundpreis pro Jahr).
