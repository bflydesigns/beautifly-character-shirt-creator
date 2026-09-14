---
name: beautifly-character-shirt-skill
description: Create premium, layered, print-ready 7:8 T-shirt artwork prompts and image variations inspired by movies, television, sitcoms, cartoons, pop-culture moments, memorable personalities, original entertainment concepts, or uploaded character reference photos. Use for movie- or TV-inspired T-shirt designs, apparel graphics, reference-photo-to-caricature conversions, character-and-quote compositions, entertainment fan art, parody-inspired shirt art, five design variations, or Beautifly-style commercial apparel illustrations. Do not use for stickers, mugs, tumblers, posters, social graphics, or other products.
---

# Beautifly Character Shirt Skill

Create only isolated T-shirt artwork in a vertical **7:8 aspect ratio**. Never create product mockups unless the user separately asks for one.

## Load references

- Read `references/art-direction.md` for every request.
- Read `references/options.md` when guiding the user, interpreting selections, or using Random/Surprise Me behavior.
- Read `references/prompt-framework.md` before composing prompts or generating artwork.

## Workflow

1. Determine whether the user wants prompts, finished artwork, or both. Infer from clear wording; do not ask unnecessarily.
2. Accept a completed brief in any format. If incomplete, ask only for choices that materially affect the result: inspiration/title, character concept, wording, and overall style. Offer beginner-friendly options.
3. Treat unspecified optional categories as `None`. Do not force a quote; character-only artwork is valid.
4. Combine multiple compatible selections intelligently. Resolve conflicts in favor of print quality, legibility, and explicit user direction.
5. When reference photos are uploaded, apply the Reference Photo Conversion Protocol in `references/art-direction.md`. Preserve recognizable identity markers while fully redrawing the subject in one unified illustrated caricature treatment. Never let facial preservation turn the result photorealistic.
6. Apply the rights-safe branch before drafting:
   - For personal/fan art, follow the selected reference subject to platform rules.
   - For commercial products, resale, or rights-safe mode, avoid exact protected actor likenesses, trademarked character designs, logos, and lengthy dialogue. Create an original archetype, parody-inspired situation, or transformed concept that captures the era, humor, attitude, or premise without copying protected expression. Briefly identify material substitutions.
7. Build one cohesive master brief plus **five meaningfully different variation prompts**. Each variation must stand alone and preserve the selected concept, exact wording, 7:8 ratio, layered composition, and print constraints.
8. When asked to generate images, use the image-generation tool. Generate each requested variation as its own image/canvas; never ask one image to contain five designs. If tool limits prevent all five in one turn, generate sequentially and label progress.
9. When individual elements or layers are requested, provide isolated outputs one at a time while preserving the approved design. Do not change the face, pose, clothing, colors, typography, or accessories unless requested.

## Five-variation rule

Make variations differ in at least three areas: pose/expression, crop, typography construction, typography placement, supporting elements, color distribution, composition, scale, perspective, or background treatment. Do not duplicate the same art five times.

Never produce a collage, grid, contact sheet, mood board, presentation board, or composite sheet. “Five variations” means five separate finished canvases or five separate generation-ready prompts.

## Exact text

When Exact Text Lock is enabled or wording is supplied in quotation marks, include:

> Render the supplied wording exactly as written. Do not change spelling, remove words, add words, duplicate letters, paraphrase the text, or invent additional typography.

Check spelling before delivery. Never add “Beautifly Designs” to the artwork unless explicitly requested as visible branding.

## Output behavior

For prompt-only requests, present:

1. A compact concept summary.
2. The structured master brief.
3. Five separately labeled prompts: `Variation 1` through `Variation 5`.
4. A shared negative prompt/quality-control block.

For image-generation requests, keep prose short and generate the artwork. Preserve all foreground subjects, avoid cropped hands/arms/props, and use a clean white background unless true transparency is explicitly requested.
