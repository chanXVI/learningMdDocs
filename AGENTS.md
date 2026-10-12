# Workspace purpose

This workspace contains Markdown documentation for learning networking and IT concepts.

## Writing style

- Keep explanations concise while retaining the details needed to understand the concept.
- Lead with a plain-language definition or direct answer, then explain how it works and why it matters.
- Assume a learner audience. Define acronyms and unfamiliar terms on first use.
- Prefer short paragraphs, compact lists, and concrete examples over lengthy introductions.
- Include relevant technical details, such as ports, protocols, commands, or configuration examples, when they help explain the topic.
- Avoid filler, repeated summaries, and unnecessary background. Expand when the user asks for depth.
- Aim for roughly 150-350 words for a single-concept note, excluding code and sources. This is a default, not a limit when accuracy requires more detail.
- Borrow the illustration approach for the writing: one main idea per note, one purpose per paragraph, and only the labels or details needed to understand it.

## Overview illustrations

- Use [Ian Xiaohei Illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations) as the visual reference for concept overviews. Read `docs/illustration-style.md` before creating an illustration.
- For a concept note, normally include one original overview illustration near the top, with a short caption and descriptive alt text. Skip it for trivial facts or command-only answers.
- Use a 16:9 white background, sparse black hand-drawn lines, ample whitespace, and restrained orange/red/blue accents. Make the small black character participate in the explanatory action.
- Use short English labels unless the user requests another language. Explain one concept per image; keep detailed protocol behavior in the text and Mermaid diagram.
- Generate topic-specific bitmap illustrations using the available image generation tool. Save final images under `assets/<topic-slug>-illustrations/` and embed them using relative Markdown paths. Preserve existing assets.
- The upstream skill, references, and three sample images are in `third-party/ian-xiaohei-illustrations/`. Samples calibrate style; do not present them as IT explanations or copy their compositions by default.
- Preserve upstream attribution, `LICENSE`, and `NOTICE.md`. Credit Ian's illustration approach in derived documentation.
- Inspect generated images for readable labels, conceptual accuracy, visual simplicity, and consistency with the note. If generation is unavailable, say so and use Mermaid; do not leave a broken image link or claim an image exists.

## Mermaid diagrams

- Use fenced `mermaid` diagrams to clarify relationships, architecture, traffic flow, sequences, and troubleshooting decisions.
- For each researched concept, include a diagram when it materially improves understanding. Do not force a diagram for a simple fact or command.
- Keep diagrams small, readable, and focused on one idea, with clear node labels and meaningful arrows.
- Briefly explain what the diagram shows. Ensure the diagram agrees with the accompanying explanation.

## Research and accuracy

- Prefer authoritative sources, such as official documentation and standards, when researching a topic.
- Verify current or version-specific details and provide concise source links near the claims they support.
- Distinguish established facts from assumptions, simplifications, and examples.
- Explain prerequisites and practical implications of commands. Clearly identify destructive or disruptive operations.

## Documentation organization

- Use descriptive Markdown filenames and headings.
- Follow any existing organization; avoid adding unnecessary tooling or scaffolding.
- Use `templates/concept-note.md` as a starting point: a short definition, overview illustration, key details, Mermaid diagram, and a practical example. Adapt this structure to the topic instead of padding every note.
- Before finishing an edit, check readability, technical consistency, code fences, and Mermaid syntax.
