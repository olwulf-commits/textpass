# TextPass — Allgemeiner 7-Schritt-Ablauf (Vertragsfreie Fassung)

Diese Referenz beschreibt den vollständigen 7-Schritt-Ablauf für die allgemeine, öffentliche Nutzung von TextPass. Sie enthält keine privaten Verträge, keine persönlichen Stimmvorgaben und keine projekt- oder servergebundenen Werkzeuge.

## Schritt 1 — Auftrag, Faktenkern und Material sichten

- **Ziel:** Kläre vor dem ersten Satz, was der Text leisten soll, für wen er geschrieben ist und welche Fakten im vorliegenden Material tatsächlich belegt sind.
- **Prüfpunkte:**
  1. Was ist das konkrete Ziel des Auftrags (Neuentwurf oder gezielte Überarbeitung)?
  2. Welche Aussagen, Zahlen, Maße, Zeitangaben und Quellen liegen belastbar vor?
  3. Wo fehlen Belege oder wo widersprechen sich Angaben im Ausgangsmaterial?
- **Ergebnis:** Eine knappe Fakten- und Materiallage mit klar markierten Lücken. Unbelegte Zahlen oder Behauptungen werden nicht geraten.

## Schritt 2 — Unabhängige Leser- und Praxisfragen einholen

- **Ziel:** Bevor eine Gliederung entsteht, soll ein frischer Blick ohne Schreib-Voreingenommenheit die wichtigsten offenen Fragen aufdecken.
- **Pflichtdelegation:** Übergib dem getrennten Frage-Agenten (`textpass-fragen-agent`) ausschließlich den Auftrag und das Ausgangsmaterial (ohne eigene Entwürfe oder Zwischenfazits).
- **Ergebnis:** Eine Liste konkreter Leser-, Alltags- und Gegenfragen, die der spätere Text beantworten oder ausdrücklich offenlassen muss.

## Schritt 3 — Freie Gliederung mit eigener Dramaturgie

- **Ziel:** Baue eine klare, eigenständige Struktur auf, statt blind Standardvorlagen oder die Reihenfolge des Ausgangsmaterials zu kopieren.
- **Prüfpunkte:**
  1. Welcher Einstieg holt die Zielgruppe sofort bei einem realen Problem oder einer konkreten Beobachtung ab?
  2. In welcher Reihenfolge bauen die Abschnitte aufeinander auf, und welche Frage aus Schritt 2 beantwortet jeder Abschnitt?
  3. Welche Abschnitte können gestrichen oder zusammengelegt werden, weil sie keinen eigenen Erkenntnisgewinn bringen?
- **Ergebnis:** Eine knappe Gliederung mit Abschnittszielen und zugeordneten Belegen.

## Schritt 4 — Substanzstarke Rohfassung schreiben

- **Ziel:** Schreibe den Text aus dem Material und der Gliederung heraus sauber aus — klar, präzise und ohne Füllsätze.
- **Regeln für die Rohfassung:**
  - **Bedeutungsbindung:** Jede Tatsachenbehauptung bleibt an das geprüfte Material gebunden.
  - **Zahlen- und Maßangabenregel:** Konkrete Zahlen, Prozente, Grenzwerte, Temperaturen, Zeiten, Preise und Maßeinheiten werden nur übernommen, wenn sie ausdrücklich belegt oder vom Auftraggeber vorgegeben sind.
  - **Kein Erfinden von Quellen:** Keine erfundenen Studien, Zitate, Produktnamen oder URLs.
  - **Klare Aussage statt Nebel:** Abstrakte Begriffe durch konkrete Handlungen, Beispiele oder Wirkungen ersetzen.

## Schritt 5 — Stimme, Rhythmus und Sprachfluss schärfen

- **Ziel:** Der Text soll sich menschlich, präzise und unangestrengt lesen — passend zum jeweiligen Auftrag und Zielmedium.
- **Prüfpunkte:**
  1. Entspricht die Tonalität (sachlich, erklärend, erzählend oder praxisnah) dem Auftrag?
  2. Wechseln sich kurze und längere Sätze natürlich ab?
  3. Gibt es steife Übergänge, Nominalstil, unnötige Passivkonstruktionen oder überflüssige Einleitungen, die gestrichen werden können?

## Schritt 6 — Kalte Gegenprüfung und eigene Gegenfrage

- **Ziel:** Den Entwurf mit Abstand auf Lücken, Unschärfen und typische KI-Muster prüfen.
- **Pflichtschritte:**
  1. **Frischer Frage-Agent:** Übergib den Entwurf erneut an `textpass-fragen-agent` als unvoreingenommenen Gegenleser.
  2. **Eigene inhaltliche Gegenfrage:** Formuliere selbst mindestens eine scharfe Gegenfrage aus Sicht eines skeptischen Lesers und prüfe, ob der Text ihr standhält.
  3. **KI-Tell-Prüfung:** Suche gezielt nach typischen Schablonen (Aufzählungstriaden, hohle Zusammenfassungen am Absatzende, formelhafte Kontraste wie „nicht nur …, sondern auch“, übermäßige Gedankenstriche, leere Superlative) und schreibe betroffene Stellen konkret um.
  4. **Zahlen- und Faktenabgleich:** Prüfe jede Zahl, jede Eigenschaft und jede Aussage gegen Schritt 1.

## Schritt 7 — Endabnahme und Übergabe

- **Ziel:** Sicherstellen, dass der Endtext vollständig, sauber formatiert und ehrlich abgegrenzt übergeben wird.
- **Prüfpunkte:**
  1. Sind alle offenen Fragen aus Schritt 2 und Schritt 6 geklärt oder transparent als offen benannt?
  2. Sind keine unerwünschten Meta-Kommentare, Platzhalter oder unbelegten Zusätze im Text geblieben?
  3. Welche bewussten Kürzungen, offenen Risiken oder fehlenden Belege sollten dem Auftraggeber bei der Übergabe kurz genannt werden?
