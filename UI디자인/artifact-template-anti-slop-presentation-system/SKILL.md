---
name: artifact-template-anti-slop-presentation-system
description: "Create a presentation using the Anti-Slop Presentation System template and its retained reference file. Use when the user selects this template, selects this personal skill, or names Anti-Slop Presentation System. Create clear, human-designed presentation/PDF decks with restrained editorial layouts, strong hierarchy, evidence-first storytelling, sky-blue OpenAI-like soft gradients, 60-30-10 color balance, Korean-first bilingual captions, render-first QA, and explicit avoidance of AI-slop patterns."
---

# Anti-Slop Presentation System

Create a presentation from this template. Keep the reference file unchanged.

## Workflow

1. Read `artifact-template.json` and resolve its paths relative to this skill directory.
2. Identify the prompt-advertised preinstalled presentation or slides capability. Use the available resource or filesystem tool to open its advertised resource, plugin, skill, or file target, then follow its reference/template workflow with the retained file. If no such capability can be identified and read, say it is unavailable and stop; do not recreate or install it.
3. Treat the user's prompt and available sources as the content input. Do not invent facts merely to fill a template slot.
4. Clone or import the reference instead of replacing its visual system with generic defaults.
5. Render and verify the finished presentation, then return the final artifact.

## Fidelity

Preserve source slides, layouts, masters, typography, geometry, images, charts, tables, and recurring slide chrome.

User instructions control requested content and explicit deviations. The retained reference controls layout and formatting where the user has not requested a change.

## Detailed Design System

Before creating or editing any presentation with this template, read `assets/DESIGN_GUIDE.md` in full and treat it as the default design and QA system.

The reference PPTX is a visual grammar, not a content template. Adapt layout to the information type rather than cloning one slide pattern repeatedly. Preserve the system's core principles: Korean-first readability, direct factual headlines, 60/30/10 white-sky-accent balance, sky/cyan/lilac soft gradients only where useful, no deep blue or cream-toned base, no AI-slop UI motifs, evidence-adjacent citations, content-specific layouts, collision-safe typography, vertical rhythm, footer safe zones, and PDF render-first visual QA.

When the user's content conflicts with the reference deck's literal text, replace the text completely while preserving the design system. Never carry Visual Travel Guide facts into unrelated presentations.

For final QA, render every slide, inspect the montage, and specifically check: text-to-text collisions, line-to-text collisions, unnatural line breaks, punctuation stranded at line boundaries, footer/divider overlap, bilingual hierarchy, numeric visualization clarity, and whether each slide has one immediately understandable message.
