# Infographic Mode

Use this mode for typologies, “N visual states,” scientific explainers, specimen grids, categorized series, and editorial research posters.

## Editorial hierarchy

For a “50 visual states” poster, default to:

- Top 52–58%: title, short information blocks, and one large hero subject that transitions from whole form to section, line drawing, grid, halftone, particles, or pixels.
- Middle/bottom 34–40%: a strict 5-row × 10-column matrix with specimens 01–50.
- Bottom 6–10%: 4–6 material/color sample panels and a compact legend.

Keep the style from `style-source.png` and `infographic-example.png`; use outside references only for hierarchy and layout logic.

## Information architecture

Divide 50 states into five meaningful groups of ten. Adapt labels to the topic, but a useful default is:

1. 01–10 FORM / 形态
2. 11–20 STRUCTURE / 结构
3. 21–30 SURFACE / 表面
4. 31–40 PROCESS or GROWTH / 过程或生长
5. 41–50 SYMBOL / 符号

For other totals, derive a grid that preserves the exact count and allows readable numbering. Do not fake precision: if the generator cannot sustain dense prose, reduce text length while keeping titles, category labels, numbering, and core facts accurate.

## Text strategy

- Use one exact main title, one short bilingual subtitle, five category labels, consecutive specimen numbers, and short keyword clusters.
- Quote every required text string in the image prompt.
- Prefer uppercase English for tiny labels because it survives raster generation better; use Chinese for the main title and category names when requested.
- Do not insert invented organizations, dates, issue numbers, or brand marks from a layout reference.

## Subject integrity

- Each specimen must relate clearly to the subject, even when abstracted.
- For botanical or scientific topics, preserve correct sectional anatomy and lifecycle order.
- Abstract states may use line, grid, halftone, collage, negative space, or geometry, but must not resemble a different object category.
- Check the exact object count, grid dimensions, number continuity, duplicates, omissions, and category boundaries.

## Prompt scaffold

```text
Use case: infographic-diagram
Asset type: portrait editorial visualization
Primary request: exact topic and total number of states
Input images: style reference and layout reference with separate roles
Overall layout: percentage split for hero, matrix, and material strip
Hero visual: controlled deconstruction sequence
Main title: exact quoted bilingual copy
Information text: short approved keyword blocks only
Matrix: exact rows × columns, numbering order, category definitions
Category labels: exact quoted text
Style/medium: weathered mural + rational editorial grid
Texture hierarchy: quiet text fields, stronger subject texture, restrained border distress
Scientific/semantic constraints: anatomy, lifecycle, and recognizable states
Avoid: reference brands, random text, wrong counts, unrelated objects, glossy/3D/vector drift
```

## Validation and repair

Inspect the image before delivery. If only a few cells are semantically wrong, perform a targeted edit naming the exact cell numbers and preserve the rest of the matrix. If numbering or the whole grid is wrong, regenerate rather than layering further noise.

