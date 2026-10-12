---
name: it-overview-illustrations
description: Create or update overview illustrations for network and IT concept notes in this repository, pairing a concise explanation with a topic-specific image and Mermaid diagram. Use for concept-note authoring or requested illustration changes; skip routine Git/setup questions and command-only answers.
---

# IT overview illustrations

Produce a memorable visual overview of one network or IT concept, using the repository's English adaptation of Ian Xiaohei Illustrations.

All paths below are relative to the repository root, not the skill directory. The skill's source lives at `skills/it-overview-illustrations/`; the discovery entry can be a symlink under `.agents/skills/`.

## Workflow

1. Read the requested topic or existing note and `docs/illustration-style.md`. Identify one main takeaway. Use `templates/concept-note.md` when creating a note, adapting its sections to the topic.
2. Normally plan one overview illustration near the top of a concept note. For an existing note, reuse a suitable image and regenerate only when the concept, visual, or requested style changes. Skip images for trivial facts or command-only answers.
3. Invent a simple physical analogy for that takeaway and adapt the style guide's prompt. Use short English labels unless the user requests another language. Keep technical detail in the prose and Mermaid diagram. State a necessary analogy caveat in the caption.
4. Generate the bitmap with the available image generation tool, following its applicable instructions. For a requested edit, inspect the existing image first and use it as the edit reference. Proceed with authorized image work without an extra confirmation step.
5. Inspect the result for accurate relationships, legible labels, the character's explanatory action, and visual simplicity. Correct meaningful errors before embedding it.
6. Save the verified image under `assets/<topic-slug>-illustrations/`, normally as `01-overview.png`. Preserve existing assets; use a new filename for a revision unless replacement was requested. Embed an actual saved image using a path relative to the note, descriptive alt text, and a short caption.
7. Keep the note concise under `AGENTS.md`. Include a small Mermaid diagram when it clarifies the actual relationships or sequence. The prose, illustration, and diagram must agree; retain important facts in accessible text.
8. Check image links and code fences, then report the note and image paths briefly. If image generation is unavailable, use Mermaid, disclose the missing illustration, and omit the image link until the asset exists.

For illustration planning alone, return a brief scene proposal without generating an image or creating a note. For illustration-only requests, work on the requested asset without expanding into a new document.

## Upstream references

The pinned reference package is under `third-party/ian-xiaohei-illustrations/`. Read additional references only when needed:

- `ian-xiaohei-illustrations/references/style-dna.md` and `xiaohei-ip.md`: visual or character calibration.
- `ian-xiaohei-illustrations/references/composition-patterns.md`: help choosing an original analogy.
- `ian-xiaohei-illustrations/references/qa-checklist.md`: diagnosing a result that needs revision.
- `ian-xiaohei-illustrations/assets/examples/`: occasional visual calibration; these Chinese samples are not IT explanations or default composition templates.

Apply this repository's one-image and English-label defaults when upstream article guidance differs. Keep upstream files unchanged; record deliberate snapshot updates in `PROVENANCE.md`. Preserve `LICENSE` and `NOTICE.md`, and credit Ian's illustration approach in derived notes as shown in the template.
