# TextPass

[TextPass & QuellPass — Olaf Wulf](https://olwulf-commits.github.io/)

[Deutsch](README.md) · English

**TextPass is developed specifically for German texts.** This English README explains the German-language skill; it does not introduce an English-language edition.

TextPass helps create explicitly requested new drafts and revise existing German texts. It starts with open questions, allows the structure to change, and keeps editorial choices tied to meaning. During revision, a second pass checks meaning, emphasis, and voice against the original. It does not add recommendations, examples, or conclusions of its own. In a commissioned new draft, ideas may emerge and develop as the writing proceeds; the assignment, supplied material, and limits of the evidence provide the reference points. The skill does not replace research or human approval.

My goal is to make texts more readable, enjoyable, and better overall using relatively simple methods. TextPass develops the article from an ordinary preliminary search; [QuellPass](https://github.com/olwulf-commits/quellpass) then checks its claims against original sources. Unsupported passages are corrected before a final review of language and structure. People can follow, question, and correct both processes. How well they work in practice has to be demonstrated through actual texts.

I see evaluation as working with what is already there: identifying what holds up, where a text could improve, and using those findings to guide revision. “Evaluate” means to assess; the word comes through French from Latin [*valere*](https://www.etymonline.com/word/evaluation), meaning “to be worth.” In formative evaluation, findings inform improvements. TextPass follows that approach: strong passages stay; weaker ones receive focused attention.

This public repository contains the general edition by Olaf Wulf. The private edition and personal voice guidelines are not included. This public edition is version 1.0.17. The preceding 1.0.16 edition was installed locally in Codex, Cursor, Claude Code, and Grok Build and checked against the source files; a practical model run of 1.0.17 is still pending. This edition includes eight internally documented review steps, a separate question agent, an original substantive counterquestion by the writing assistant, and a mandatory check for generic AI phrasing. An official provider-directory listing will only be claimed after confirmed acceptance.

This is the **official TextPass edition**. Modified editions from other providers are not endorsed by Olaf Wulf unless explicitly stated.

## Installation

The skill is at [plugins/textpass-de/skills/textpass-de/SKILL.md](plugins/textpass-de/skills/textpass-de/SKILL.md). Catalog files for Codex, Claude Code, Grok Build, and Cursor are included. In Claude Code, add the catalog with `claude plugin marketplace add olwulf-commits/textpass`, then install with `claude plugin install textpass-de@textpass`. The local Claude Code installation has been checked; a practical model run of this edition is still pending.

For Grok Build, `.grok-plugin/marketplace.json` is prepared. The preceding public 1.0.16 edition was installed locally in Grok Build; importing it directly from GitHub has not been tested. The repository can be added as a separate marketplace. Inclusion in the official [xAI catalog](https://github.com/xai-org/plugin-marketplace) also requires a pull request there pinned to a commit. Grok Build is separate from chat on grok.com.

For Cursor, `.cursor-plugin/marketplace.json` and the plugin manifest are prepared. Submit the repository at [Cursor Marketplace Publish](https://cursor.com/marketplace/publish) for review. The “Publish” button under Customize → Skills shares a personal skill with a team marketplace. No Cursor submission or host behavior test has been completed.

Hermes Agent can read the cloned repository as an external skill source: Set `skills.external_dirs` in `~/.hermes/config.yaml` to the absolute path of `plugins/textpass-de/skills` inside the clone. This keeps TextPass and `haltung-im-text` together; start a new Hermes session to load the change. A local skill with the same name takes precedence in Hermes, so check which edition was actually loaded. Hermes also supports [Grok as a model provider](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/integrations/providers.md). This is separate from Grok Build. The public edition has not yet been tested in Hermes; the locally installed private edition is a different release. See the [Hermes external skills guide](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/features/skills.md#external-skill-directories).

The plugin also includes [`haltung-im-text`](plugins/textpass-de/skills/haltung-im-text/SKILL.md). It examines editorial choices when a stance or voice is commissioned or a comment such as “too smooth” calls for a design review. Its questions and decisions belong in step 5, its passage comparisons in step 7, and its evidence check in step 8. A comment about smoothness alone does not authorize a new stance, first-person voice, or invented experience. When installing individual skill files, install both skills.

## License

The skill text and README documentation are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Use and adaptation require attribution, identification of changes, and distribution of adaptations under the same license. Technical package files use the MIT License. See [LICENSE.md](LICENSE.md) for the allocation and license texts. Using TextPass does not place users’ own texts under the TextPass license.

## Contribute — including other languages

Tests and specific improvement suggestions are welcome through a [GitHub test report](https://github.com/olwulf-commits/textpass/issues/new/choose). Please include the tool, version, example, and observed result. Successful tests are useful too. I review the feedback and decide which changes enter the official edition.

I also welcome help developing an English-language edition and editions in other EU languages. These should be adapted to each language’s idiom, rhythm, grammar, and editorial conventions, rather than simply translating the German instructions. Translation, language-specific editing, and practical testing are all welcome. German remains the developed edition; other language editions are an invitation to collaborate, not a claim of existing support.

## Origins

I appreciate Martin Möller’s work on [humanizer-de](https://github.com/marmbiz/humanizer-de) and his [KI-Text-Eisberg](https://martin-moeller.biz/lab/ki-text-eisberg); it helped inspire TextPass. I had already developed some similar editorial steps independently. TextPass is my own project, with no official affiliation to Martin Möller or humanizer-de. Neither the Humanizer’s code nor its pattern catalog is part of this repository.

## Status and limitations

The general edition is publicly available with Olaf’s approval. Matching package and installation files does not guarantee that every model will follow the instructions. Practical writing tests and feedback guide further verification. An official directory listing will only be claimed once acceptance is confirmed.
