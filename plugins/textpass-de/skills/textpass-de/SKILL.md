---
name: textpass-de
description: Gestalte deutsche Artikel und vorhandene Texte in sieben klaren Schritten mit unabhängigen Fragen, freiem Aufbau, Bedeutungsbindung und Prüfung auf KI-Floskeln.
license: CC-BY-SA-4.0
---

# TextPass (Öffentliche, vertragsfreie Fassung)

TextPass ist ein 7-Schritt-Verfahren zum Schreiben und gezielten Überarbeiten deutscher Texte. Diese öffentliche Fassung ist bewusst **vertragsfrei** und enthält keine persönlichen Stimmvorgaben oder internen Projektregeln.

## Verbindliche Referenzen

- **Vollständiger 7-Schritt-Ablauf:** [schritte-7-ablauf.md](../../references/schritte-7-ablauf.md)
- **Unabhängiger Frage-Agent:** `textpass-fragen-agent` (`agents/textpass-fragen-agent.md`)

Lies vor Beginn eines Durchlaufs `references/schritte-7-ablauf.md` vollständig.

## Verbindliche Grundregeln

1. **Bedeutungsbindung & Anspruchsgrenze:** Jede Tatsachenbehauptung bleibt an geprüftes Material gebunden. Was nicht belegt ist, wird gestrichen, präzise abgeschwächt oder offen als Lücke markiert.
2. **Zahlen- und Maßangabenregel:** Konkrete Zahlen, Prozente, Grenzwerte, Temperaturen, Zeiten, Preise und Maßeinheiten werden nur übernommen, wenn sie ausdrücklich belegt oder vorgegeben sind — niemals geraten.
3. **Pflichtdelegation an den Frage-Agenten:** Delegiere in Schritt 2 (vor der Gliederung) und in Schritt 6 (als frischer Gegenleser) unabhängig an den Subagenten `textpass-fragen-agent`. Falls eine Plattform keine Subagenten unterstützt, simuliere die Rolle strikt getrennt nur auf Basis des übergebenen Materials.
4. **Eigene inhaltliche Gegenfrage:** Stelle dir vor Abschluss von Schritt 6 selbst eine scharfe Gegenfrage aus Lesersicht und prüfe, ob der Text sie sauber beantwortet.
5. **KI-Floskel- und Rhythmusprüfung:** Entferne typische KI-Muster (Aufzählungstriaden, formelhafte Übergänge, hohle Absatz-Fazits, Nominalstil, übermäßige Gedankenstriche) und prüfe den Sprachfluss.
6. **Keine erfundenen Quellen:** Erfinde niemals URLs, Studien, Zitate oder Eigenschaftszusagen.

## Die 7 Schritte im Überblick

1. **Auftrag & Material sichten:** Ziel, Zielgruppe, Faktenkern und Lücken festhalten.
2. **Frage-Agent vor der Gliederung:** `textpass-fragen-agent` unabhängig nach offenen Leser- und Praxisfragen fragen.
3. **Freie Gliederung:** Eigene Dramaturgie mit klaren Abschnittszielen festlegen.
4. **Rohfassung:** Substanzstark, konkret und belegtreu schreiben.
5. **Stimme & Sprachfluss:** Tonalität am Auftrag ausrichten, Satzrhythmus variieren, Ballast streichen.
6. **Gegenprüfung:** Frischen `textpass-fragen-agent` nutzen, eigene Gegenfrage prüfen, KI-Floskeln und Zahlen bereinigen.
7. **Endabnahme:** Vollständigkeit, verbleibende Risiken und saubere Übergabe prüfen.

---

Lizenz: [CC BY-SA 4.0](../../LICENSE.md) — Olaf Wulf.
