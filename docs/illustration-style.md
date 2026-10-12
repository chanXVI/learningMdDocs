# Overview illustration style

Inspired by [Ian Xiaohei Illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations), created by [Ian](https://github.com/helloianneo). Upstream license and attribution are preserved in [the local reference package](../third-party/ian-xiaohei-illustrations/PROVENANCE.md).

## Purpose

Give the reader a memorable mental model before the technical detail. Each image explains one idea; each note develops that idea briefly. Use Mermaid for precise relationships and sequences.

## Local adaptation

- One overview image per concept note by default, rather than the upstream multi-image article workflow.
- Short English labels by default, rather than Chinese annotations.
- 16:9, pure white background, sparse black pen lines, and generous whitespace.
- Orange for movement, red for a problem, blue for a secondary note. Use only the colors needed.
- A small solid-black character with white dot eyes and thin limbs performs the main action.
- Prefer a simple physical analogy; explain its limits when it could mislead.
- Keep paragraphs brief, use 3-5 key points, and include one concrete example. Avoid repeating everything shown in the visuals.

## Workflow

1. Write the concept's main takeaway in one sentence.
2. Choose one action or relationship the overview should explain.
3. Read the relevant upstream references under `third-party/ian-xiaohei-illustrations/ian-xiaohei-illustrations/references/`.
4. Generate one original image using the prompt below, adapted to the topic. Sample images are for style calibration.
5. Inspect the result for accuracy and readable labels; edit or regenerate if needed.
6. Save it as `assets/<topic-slug>-illustrations/01-overview.png`; embed it with meaningful alt text and a one-sentence caption.

## Prompt starting point

```text
Generate one standalone 16:9 overview illustration for an English network/IT learning note.

Topic: {topic}
Main takeaway: {one sentence}
Physical analogy and action: {simple scene that explains the takeaway}
Labels: {2-5 short English labels, preferably 1-3 words each}

Use a pure white background, thin slightly irregular black hand-drawn lines,
and ample whitespace. The main scene occupies around half the canvas.
Use orange for the main movement, red only for a problem, and blue only
for a secondary annotation, where needed.

A small solid-black character with white dot eyes, thin limbs, and a calm,
serious expression performs the central explanatory action. Invent an
original scene for this topic. Keep the visual focused on one idea with
accurate relationships. Avoid dense text, decorative characters, complex
architecture, gradients, shadows, paper texture, and slide-like layouts.
```

## Finish check

The reader should recognize the main idea quickly. Check label spelling, arrows, and the analogy against the technical explanation. Keep important facts accessible in the text, not only in the image. Add any necessary analogy caveat to the caption.
