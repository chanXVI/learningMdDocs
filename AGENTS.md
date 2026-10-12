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

- When creating a network/IT concept note or creating or updating its overview illustration, use `$it-overview-illustrations`. If it is not listed as a discovered skill, read and follow `skills/it-overview-illustrations/SKILL.md` directly.
- The skill handles the illustration workflow; `docs/illustration-style.md` holds the English visual conventions and prompt. Read upstream references only as needed.
- Keep the pinned upstream package under `third-party/ian-xiaohei-illustrations/` unchanged during ordinary note work. Preserve its license, attribution, and provenance.

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
