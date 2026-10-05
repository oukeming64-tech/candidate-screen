# Changelog

## 2026-10-05 — English Counterpart

- Added an English counterpart to the Chinese version at `b436eb12ce989132b7912fd066f3d366afea7ccb`, covering the skill, README, changelog, three synthetic inputs, review checkpoints, actual outputs, and validation explanations.
- The English repository source uses `SKILL.en.md`; the standalone English package renames it to `SKILL.md`. Each language package has one skill entrypoint. The Chinese rules remain unchanged.
- The English actual-output and baseline-validation files are explicitly labeled as translations of the Chinese runs, not results from executing the English skill. Separate language-review notes record this addition's checks and limits.
- The MIT license text and copyright notice remain unchanged.

## 2026-10-05

- Retained “a résumé is fundamentally a narrative” and cross-checked key claims against the complete set of materials.
- Incorporated contribution attribution, sources, partial support, and verification boundaries from the earlier concise draft; distinguished unclear wording from an explicit statement that something was not done.
- Removed rules that equated specific numbers or plain style with truthfulness, triggered rejection from missing materials, or applied universal scoring to every role.
- Usually focus on 2–4 claims per set of materials and list sources and verification status separately; avoid counting repeated statements as independent evidence.
- Added boundaries for embedded instructions, separation between candidates, and human review, along with three synthetic regression inputs and a validation record.
- Updated from public repository commit `9e56c78433bf70a160750df307ba4b4023d745e4`, preserving the MIT license text.
