# TextPass

[TextPass & QuellPass — Olaf Wulf](https://olwulf-commits.github.io/)

Deutsch · [English](README.en.md)

**TextPass ist speziell für deutsche Texte ausgearbeitet.** Die englische README erläutert diese Fassung; sie ist keine englischsprachige Skill-Version.

TextPass gestaltet ausdrücklich beauftragte Neuentwürfe und überarbeitet vorhandene deutsche Texte mit offenen Fragen, freiem Aufbau und Bedeutungsbindung. Bei der Überarbeitung prüft der zweite Durchlauf Bedeutung, Gewichtung und Stimme gegen die Vorlage; eigene Empfehlungen, Beispiele oder Schlussfolgerungen werden dabei nicht ergänzt. Bei Neuentwürfen dürfen Gedanken im beauftragten Schreibprozess entstehen und sich entwickeln; der Abgleich folgt Auftrag, Material und Beleggrenzen. Der Skill ersetzt keine Recherche oder menschliche Freigabe.

Mein Ziel ist, Texte mit vergleichsweise einfachen Mitteln lesbarer, angenehmer und insgesamt hochwertiger zu machen. TextPass entwickelt aus einer gewöhnlichen Recherche den Artikel; [QuellPass](https://github.com/olwulf-commits/quellpass) prüft danach dessen Aussagen und Originalquellen. Unbelegte Stellen werden korrigiert, bevor der ganze Artikel noch einmal auf Sprache und Aufbau geprüft wird. Beides bleibt für Menschen nachvollziehbar und korrigierbar. Wie gut das im Alltag gelingt, müssen konkrete Texte zeigen.

Mein Ansatz versteht Evaluation als Arbeit am Vorhandenen: Ich prüfe, was bereits trägt und wo ein Text besser werden kann, und nutze diese Erkenntnisse für die Überarbeitung. „Evaluieren“ heißt [bewerten](https://www.duden.de/rechtschreibung/evaluieren); das Wort führt über das Französische auf lateinisch [*valere*](https://www.etymonline.com/word/evaluation) („wert sein“) zurück. Bei der formativen Evaluation dienen Befunde dazu, mögliche Verbesserungen abzuleiten. TextPass folgt diesem Gedanken: Gute Stellen bleiben, schwächere werden gezielt überarbeitet.

Dieses öffentliche Repository enthält die **allgemeine** Fassung von Olaf Wulf. Die private Fassung und persönliche Stimmvorgaben gehören nicht dazu. Diese öffentliche Fassung trägt Version 1.0.17. Der vorherige Stand 1.0.16 war lokal in Codex, Cursor, Claude Code und Grok Build installiert und mit den Quellen abgeglichen; ein praktischer Modelllauf von 1.0.17 steht noch aus. Die acht intern dokumentierten Prüfschritte, die Pflichtdelegation an einen getrennten Frage-Agenten, eine eigene inhaltliche Gegenfrage und die verbindliche Prüfung auf KI-Floskeln sind Teil dieser Fassung. Eine Aufnahme in ein Anbieter-Verzeichnis wird erst nach bestätigter Annahme behauptet.

Dies ist die **offizielle TextPass-Fassung**. Bearbeitete Fassungen anderer Anbieter sind nicht von Olaf Wulf freigegeben, sofern dies nicht ausdrücklich angegeben ist.

Der Skill liegt unter [`plugins/textpass-de/skills/textpass-de/SKILL.md`](plugins/textpass-de/skills/textpass-de/SKILL.md). Katalogdateien für Codex, Claude Code, Grok Build und Cursor liegen im Repository. In Claude Code kann der Katalog mit `claude plugin marketplace add olwulf-commits/textpass` hinzugefügt und das Plugin mit `claude plugin install textpass-de@textpass` installiert werden. Die lokale Installation in Claude Code ist geprüft; ein praktischer Modelllauf dieser Fassung steht noch aus.

Für Grok Build ist `.grok-plugin/marketplace.json` vorbereitet. Die vorherige öffentliche Fassung 1.0.16 wurde lokal in Grok Build installiert; ein Import direkt von GitHub wurde noch nicht geprüft. Das Repository kann als eigener Katalog hinzugefügt werden; eine Aufnahme in den offiziellen [xAI-Katalog](https://github.com/xai-org/plugin-marketplace) braucht zusätzlich einen dortigen Pull Request mit festgelegtem Commit. Grok Build und der Chat auf grok.com sind unterschiedliche Produkte.

Für Cursor sind `.cursor-plugin/marketplace.json` und das Plugin-Manifest vorbereitet. Die öffentliche Einreichung erfolgt über [Cursor Marketplace Publish](https://cursor.com/marketplace/publish) und wird von Cursor geprüft. Der Knopf „Publish“ unter Customize → Skills betrifft dagegen persönliche Skills für einen Team-Marketplace. Eine Cursor-Einreichung oder praktische Hostprüfung ist noch nicht erfolgt.

Für Hermes Agent kann das geklonte Repository als externe Skillquelle eingebunden werden: In `~/.hermes/config.yaml` verweist `skills.external_dirs` auf den absoluten Pfad `plugins/textpass-de/skills` innerhalb des Klons. Dadurch bleiben TextPass und `haltung-im-text` zusammen; eine neue Hermes-Sitzung lädt die Änderung. Ein gleichnamiger lokaler Skill hat in Hermes Vorrang; prüfe deshalb, welche Fassung tatsächlich geladen wurde. Hermes unterstützt auch [Grok als Modellanbieter](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/integrations/providers.md). Das ist ein anderer Weg als Grok Build. Die öffentliche Fassung ist in Hermes noch nicht praktisch getestet; die lokal installierte private Fassung ist ein anderer Stand. Siehe die [Hermes-Anleitung für externe Skills](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/features/skills.md#external-skill-directories).

Das Plugin enthält zusätzlich [`haltung-im-text`](plugins/textpass-de/skills/haltung-im-text/SKILL.md). Bei beauftragter Haltung oder Stimme und bei Hinweisen wie „zu glatt“ prüft dieser Skill die Gestaltung. Seine Fragen und Entscheidungen gehören in Schritt 5, seine Textstellenvergleiche in Schritt 7 und die Nachweisprüfung in Schritt 8. Ein Glätte-Hinweis allein erlaubt keine neue Haltung, Ich-Stimme oder erfundene Erfahrung. Bei einer Installation als einzelne Skilldateien werden beide Skills benötigt.

## Lizenz

Der Skilltext und dieses README stehen unter [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/): Nutzung und Bearbeitung sind mit Namensnennung, Kennzeichnung von Änderungen und Weitergabe bearbeiteter Fassungen unter derselben Lizenz erlaubt. Die technischen Paketdateien stehen unter der MIT License. Die genaue Zuordnung und die Lizenztexte stehen in [LICENSE.md](LICENSE.md). Bearbeitete Texte von Nutzern erhalten dadurch keine TextPass-Lizenz.

## Mithelfen

Tests und konkrete Verbesserungsvorschläge sind willkommen. Wer Zugriff auf das Repository hat, kann dafür einen [Testbericht auf GitHub](https://github.com/olwulf-commits/textpass/issues/new/choose) anlegen. Die Vorlage fragt nach Werkzeug, Version, Beispiel und beobachtetem Ergebnis. Auch ein gelungener Test hilft mir. Ich prüfe die Rückmeldungen und entscheide, was an der offiziellen Fassung geändert wird.

Unterstützung für eine englischsprachige Fassung und weitere EU-Sprachen ist willkommen: bei Übersetzung, sprachspezifischer Ausarbeitung und praktischen Texttests. Dabei sollen Idiomatik, Rhythmus, Grammatik und redaktionelle Konventionen der jeweiligen Sprache berücksichtigt werden, statt nur die deutschen Anweisungen zu übersetzen. Bislang ist die deutsche Fassung ausgearbeitet; die Einladung ist keine Zusage bereits vorhandener Sprachunterstützung.

## Herkunft

Ich schätze Martin Möllers Arbeit an [humanizer-de](https://github.com/marmbiz/humanizer-de) und seinem [KI-Text-Eisberg](https://martin-moeller.biz/lab/ki-text-eisberg); sie hat mich bei TextPass angeregt. Einige ähnliche redaktionelle Schritte hatte ich unabhängig davon bereits entwickelt. TextPass ist mein eigenständiges Projekt. Es besteht keine offizielle Verbindung zu Martin Möller oder humanizer-de. Weder Programmcode noch der Musterkatalog des Humanizers sind Bestandteil dieses Repositories.

## Stand und Grenzen

Die allgemeine Fassung wird auf Olafs Freigabe öffentlich bereitgestellt. Paket- und Installationsabgleich sind keine Garantie für die Befolgung durch jedes Modell. Praktische Textversuche und Rückmeldungen dienen der weiteren Prüfung; eine offizielle Verzeichnisaufnahme wird erst nach bestätigter Annahme behauptet.
