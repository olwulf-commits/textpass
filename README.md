# TextPass

Deutsch · [English](README.en.md)

**TextPass ist speziell für deutsche Texte ausgearbeitet.** Die englische README erläutert diese Fassung; sie ist keine englischsprachige Skill-Version.

TextPass gestaltet ausdrücklich beauftragte Neuentwürfe und überarbeitet vorhandene deutsche Texte mit offenen Fragen, freiem Aufbau und Bedeutungsbindung. Bei der Überarbeitung prüft der zweite Durchlauf Bedeutung, Gewichtung und Stimme gegen die Vorlage; eigene Empfehlungen, Beispiele oder Schlussfolgerungen werden dabei nicht ergänzt. Bei Neuentwürfen dürfen Gedanken im beauftragten Schreibprozess entstehen und sich entwickeln; der Abgleich folgt Auftrag, Material und Beleggrenzen. Der Skill ersetzt keine Recherche oder menschliche Freigabe.

Mein Ziel ist, Texte mit vergleichsweise einfachen Mitteln lesbarer, angenehmer und insgesamt hochwertiger zu machen. [QuellPass](https://github.com/olwulf-commits/quellpass) macht Aussagen und Quellen prüfbar; TextPass arbeitet anschließend an Sprache und Lesefluss. Beides bleibt für Menschen nachvollziehbar und korrigierbar. Wie gut das im Alltag gelingt, müssen konkrete Texte zeigen.

Mein Ansatz versteht Evaluation als Arbeit am Vorhandenen: Ich prüfe, was bereits trägt und wo ein Text besser werden kann, und nutze diese Erkenntnisse für die Überarbeitung. „Evaluieren“ heißt [bewerten](https://www.duden.de/rechtschreibung/evaluieren); das Wort führt über das Französische auf lateinisch [*valere*](https://www.etymonline.com/word/evaluation) („wert sein“) zurück. Bei der formativen Evaluation dienen Befunde dazu, mögliche Verbesserungen abzuleiten. TextPass folgt diesem Gedanken: Gute Stellen bleiben, schwächere werden gezielt überarbeitet.

Dieses öffentliche Repository enthält die **allgemeine** Fassung von Olaf Wulf. Die private Fassung und persönliche Stimmvorgaben gehören nicht dazu. Version 1.0.10 ist lokal aus diesem Repository in Codex installiert und mit ihren Quellen abgeglichen; eine Aufnahme in ein offizielles Anbieter-Verzeichnis ist damit nicht verbunden.

Dies ist die **offizielle TextPass-Fassung**. Bearbeitete Fassungen anderer Anbieter sind nicht von Olaf Wulf freigegeben, sofern dies nicht ausdrücklich angegeben ist.

Der Skill liegt unter [`plugins/textpass-de/skills/textpass-de/SKILL.md`](plugins/textpass-de/skills/textpass-de/SKILL.md). Die Katalogdateien für Codex und Claude sind enthalten. In Claude Code kann der Katalog mit `claude plugin marketplace add olwulf-commits/textpass` hinzugefügt und das Plugin mit `claude plugin install textpass-de@textpass` installiert werden. Dieser Claude-Installationsweg ist vorbereitet, aber hier nicht praktisch geprüft.

## Lizenz

Der Skilltext und dieses README stehen unter [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/): Nutzung und Bearbeitung sind mit Namensnennung, Kennzeichnung von Änderungen und Weitergabe bearbeiteter Fassungen unter derselben Lizenz erlaubt. Die technischen Paketdateien stehen unter der MIT License. Die genaue Zuordnung und die Lizenztexte stehen in [LICENSE.md](LICENSE.md). Bearbeitete Texte von Nutzern erhalten dadurch keine TextPass-Lizenz.

## Mithelfen

Tests und konkrete Verbesserungsvorschläge sind willkommen. Wer Zugriff auf das Repository hat, kann dafür einen [Testbericht auf GitHub](https://github.com/olwulf-commits/textpass/issues/new/choose) anlegen. Die Vorlage fragt nach Werkzeug, Version, Beispiel und beobachtetem Ergebnis. Auch ein gelungener Test hilft mir. Ich prüfe die Rückmeldungen und entscheide, was an der offiziellen Fassung geändert wird.

Unterstützung für eine englischsprachige Fassung und weitere EU-Sprachen ist willkommen: bei Übersetzung, sprachspezifischer Ausarbeitung und praktischen Texttests. Dabei sollen Idiomatik, Rhythmus, Grammatik und redaktionelle Konventionen der jeweiligen Sprache berücksichtigt werden, statt nur die deutschen Anweisungen zu übersetzen. Bislang ist die deutsche Fassung ausgearbeitet; die Einladung ist keine Zusage bereits vorhandener Sprachunterstützung.

## Herkunft

Ich schätze Martin Möllers Arbeit an [humanizer-de](https://github.com/marmbiz/humanizer-de) und seinem [KI-Text-Eisberg](https://martin-moeller.biz/lab/ki-text-eisberg); sie hat mich bei TextPass angeregt. Einige ähnliche redaktionelle Schritte hatte ich unabhängig davon bereits entwickelt. TextPass ist mein eigenständiges Projekt. Es besteht keine offizielle Verbindung zu Martin Möller oder humanizer-de. Weder Programmcode noch der Musterkatalog des Humanizers sind Bestandteil dieses Repositories.

## Stand und Grenzen

Die allgemeine Fassung wird auf Olafs Freigabe öffentlich bereitgestellt. Paket- und Installationsabgleich sind keine Garantie für die Befolgung durch jedes Modell. Praktische Textversuche und Rückmeldungen dienen der weiteren Prüfung; eine offizielle Verzeichnisaufnahme wird erst nach bestätigter Annahme behauptet.
