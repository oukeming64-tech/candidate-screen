# Language Review Record

Date: 2026-10-05. The English version uses Chinese commit `b436eb12ce989132b7912fd066f3d366afea7ccb` as its baseline. Language and installation notes were added; the Chinese rules and existing synthetic test records were not changed.

## File Correspondence

| Chinese source | English counterpart in the repository |
| --- | --- |
| `SKILL.md` | `translations/en/SKILL.en.md` |
| `README.md`, `CHANGELOG.md` | Files with the same names under `translations/en/` |
| `evals/cases.md`, `evals/inputs/01.md` through `03.md` | The same relative paths under `translations/en/` |
| `evals/observed.md`, `evals/validation.md` | The same relative paths under `translations/en/`, explicitly labeled as translations of the Chinese run records |
| `evals/language-review.md` | `translations/en/evals/language-review.md` |
| `LICENSE`, `.gitignore` | Files with the same names under `translations/en/`, copied without changes |

The English installation package only renames `SKILL.en.md` to `SKILL.md`; it does not alter its contents. Each language package has one `candidate-screen` entrypoint. Install only the chosen language for this same-name skill and preserve existing custom changes.

## Semantic Review

The skill, explanations, inputs, review checkpoints, and translated outputs were compared paragraph by paragraph, focusing on preserving these distinctions:

| Check | Correspondence |
| --- | --- |
| Searching all materials for support | Read a summary with the project paragraphs, still matching the same project, phase, and result. |
| Degree of support versus verification status | Internal support is not rewritten as independent verification. Self-report, partial support, conflicts, and pending verification can coexist. |
| Not clearly stated versus explicitly not done | Do not infer that work was never done from missing materials, or negate product contributions because engineering responsibilities are explicitly assigned to others. |
| Repeated claims | Repeated numbers remain from the same source and are not counted again as independent evidence. |
| Responsibility and date conflicts | List them separately without inventing launch stages. Joint implementation does not automatically negate independent design. |
| Outputs and impact | A team draft, demo behavior, authorship, production launch, and business improvement do not substitute for one another. |
| Instructions, human review, and candidate separation | Do not execute embedded instructions, appropriate another candidate's evidence, or make employment judgments using irrelevant sensitive information. |

During review, the English algorithm wording was narrowed to an “explicit statement that they did not write algorithms,” avoiding an implication that truthfulness had been established or that the statement described habitual behavior. This was a translation correction, not a change to the Chinese rules. Input identifiers, project correspondence, dates, 30%, 42%, and 429 were retained; the complete test outputs were translated from the original bodies.

## Static Checks and Limits

Both skills' YAML was checked with a local YAML parser. No dependencies were installed for this, and no claim is made that the bundled Python validator passed. Checks covered file correspondence, material identifiers, structure, preservation of the source text, license identity, and local references. The bytes of the original Chinese skill, cases, actual outputs, and validation record remain unchanged.

- Chinese SKILL.md SHA-256: `ccb90c3af76871af753e113c6db47e00dfdd170b633b734b64c50e803c076420`.
- English SKILL.en.md SHA-256: `49fef371e6a3bec96dea3c8cb5c4a2ff838fd14d2daa2d97841c1e60466f7061`.

- Model name and version for the three actual Chinese runs: Unknown (not supplied in the available execution summaries).
- Model name and version for this English addition: Not applicable (no model behavior tests were run).

No model behavior test of the English skill was run for this addition. Semantic review and static checks are not behavior tests. The English `observed.md` and `validation.md` only translate the three completed Chinese synthetic runs and their limits. They do not establish equal model performance across languages or effectiveness in real hiring.
