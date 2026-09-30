# TextPass

[Deutsch](README.md) · English

**TextPass is developed specifically for German texts.** This English README explains the German-language skill; it does not introduce an English-language edition.

TextPass helps create explicitly requested new drafts and revise existing German texts. It starts with open questions, allows the structure to change, and keeps editorial choices tied to meaning. During revision, a second pass checks meaning, emphasis, and voice against the original. It does not add recommendations, examples, or conclusions of its own. In a commissioned new draft, ideas may emerge and develop as the writing proceeds; the assignment, supplied material, and limits of the evidence provide the reference points. The skill does not replace research or human approval.

My goal is to make texts more readable, enjoyable, and better overall using relatively simple methods. [QuellPass](https://github.com/olwulf-commits/quellpass) makes claims and sources open to verification; TextPass then works on language and reading flow. People can follow, question, and correct both processes. How well they work in practice has to be demonstrated through actual texts.

I see evaluation as working with what is already there: identifying what holds up, where a text could improve, and using those findings to guide revision. “Evaluate” means to assess; the word comes through French from Latin [*valere*](https://www.etymonline.com/word/evaluation), meaning “to be worth.” In formative evaluation, findings inform improvements. TextPass follows that approach: strong passages stay; weaker ones receive focused attention.

This public repository contains the general edition by Olaf Wulf. The private edition and personal voice guidelines are not included. Version 1.0.10 has been installed locally from this repository in Codex and checked against the source files. That is not an official directory listing.

This is the **official TextPass edition**. Modified editions from other providers are not endorsed by Olaf Wulf unless explicitly stated.

## Installation

The skill is at [plugins/textpass-de/skills/textpass-de/SKILL.md](plugins/textpass-de/skills/textpass-de/SKILL.md). Catalog files for Codex and Claude are included. In Claude Code, add the catalog with `claude plugin marketplace add olwulf-commits/textpass`, then install with `claude plugin install textpass-de@textpass`. This Claude installation route is prepared but has not been tested here.

## License

The skill text and README documentation are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Use and adaptation require attribution, identification of changes, and distribution of adaptations under the same license. Technical package files use the MIT License. See [LICENSE.md](LICENSE.md) for the allocation and license texts. Using TextPass does not place users’ own texts under the TextPass license.

## Contribute — including other languages

Tests and specific improvement suggestions are welcome through a [GitHub test report](https://github.com/olwulf-commits/textpass/issues/new/choose). Please include the tool, version, example, and observed result. Successful tests are useful too. I review the feedback and decide which changes enter the official edition.

I also welcome help developing an English-language edition and editions in other EU languages. These should be adapted to each language’s idiom, rhythm, grammar, and editorial conventions, rather than simply translating the German instructions. Translation, language-specific editing, and practical testing are all welcome. German remains the developed edition; other language editions are an invitation to collaborate, not a claim of existing support.

## Origins

I appreciate Martin Möller’s work on [humanizer-de](https://github.com/marmbiz/humanizer-de) and his [KI-Text-Eisberg](https://martin-moeller.biz/lab/ki-text-eisberg); it helped inspire TextPass. I had already developed some similar editorial steps independently. TextPass is my own project, with no official affiliation to Martin Möller or humanizer-de. Neither the Humanizer’s code nor its pattern catalog is part of this repository.

## Status and limitations

The general edition is publicly available with Olaf’s approval. Matching package and installation files does not guarantee that every model will follow the instructions. Practical writing tests and feedback guide further verification. An official directory listing will only be claimed once acceptance is confirmed.
