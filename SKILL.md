---
name: mural-poster-infographics
description: Create or edit art posters and editorial infographics in either a weathered mineral-pigment mural style or an airy pastel-impasto pastoral style. Use for matching poster series, structured visual-state diagrams, or when either established visual language is requested.
---

# Mural and Pastel-Impasto Posters and Infographics

Create polished raster artwork in one of the user's two established visual systems. Use the built-in image generator for generation and edits. Preserve exact user text, requested subject matter, aspect ratio, and any supplied layout reference.

## Choose a visual branch

Ask only when the desired branch is genuinely unclear. Otherwise select one and state it in the production prompt.

1. **Branch A — weathered mineral mural**: the original branch. Use for aged lime plaster, restrained brick red and ochre, constructivist collage, dry-brush wear, old letterpress, or mural-like editorial work. Keep all original reference files and instructions in effect.
2. **Branch B — pastel impasto pastoral**: the added branch. Use for airy pastel skies, thick palette-knife paint, broad layered color fields, restrained pastoral atmosphere, poetic poster typography, or a clean but handmade visual-state chart. Read [references/pastel-impasto-branch.md](references/pastel-impasto-branch.md).

Do not blend the branches by default. In particular, Branch B must not inherit Branch A's chipped ink, crumbling plaster, brick-red dominance, or distressed letterpress.

## Route the request

1. For Branch A, read [references/style-system.md](references/style-system.md). For Branch B, read [references/pastel-impasto-branch.md](references/pastel-impasto-branch.md).
2. For a Branch A title-led art poster, also read [references/poster-mode.md](references/poster-mode.md). For a Branch A diagram, typology, matrix, or data-heavy editorial layout, also read [references/infographic-mode.md](references/infographic-mode.md).
3. For Branch B, use the poster or infographic route in `pastel-impasto-branch.md`; it includes both modes.
4. Use visual assets only as references. Branch A assets:
   - `assets/style-source.png`: primary material, palette, and mural-texture reference.
   - `assets/poster-example.png`: approved poster balance, typography, and restrained lower field.
   - `assets/infographic-example.png`: approved editorial hierarchy and 50-state matrix.
   Branch B asset:
   - `assets/branch-b-reference.jpg`: the single approved style and material reference for every Branch B poster and infographic. Use it for palette, paint handling, atmosphere, and layered spatial rhythm; do not treat its shepherd or sheep as required subject matter.

## Essential workflow

- Identify the deliverable mode, aspect ratio, exact text, focal subject, and whether an existing image is an edit target or only a style/layout reference.
- Build one production-ready prompt that assigns each input image a role. Never let a layout reference override the mural style reference.
- Default to a restrained, asymmetric composition when using Branch A. For Branch B, follow the gentler poster or diagram balance in its branch reference.
- Quote exact display copy in the generation prompt. Keep generated body copy short; prefer numbered specimens, compact labels, and brief bilingual headings over paragraphs.
- Generate the image, inspect subject integrity, typography, hierarchy, counts, and unwanted artifacts, then make one targeted edit at a time.
- For dense matrices, verify the requested row/column count, continuous numbering, category boundaries, and that each specimen remains semantically recognizable.
- If the user asks for a prompt or needs coursework submission text, also provide a fluent Chinese prompt of at least 200 Chinese characters matching the final image.
- Save final project deliverables in the current workspace `outputs/` directory with descriptive filenames. Report the saved path and the final prompt.

## Branch A quality checks

Apply these only to the original weathered mineral mural branch.

- Keep the palette low-saturation: brick red, terracotta, ochre, aged cream, sand gray, muted blue-gray, olive, charcoal, and dark brown.
- Preserve hand-made mineral pigment, lime-plaster cracks, dry brush, scraping, faded overprint, and old-letterpress character without turning the whole image into noisy debris.
- Use fewer, larger color fields in quiet areas. The lowest 15–25% of a poster should normally be calmer than the focal region.
- Typography must be legible and intentional. Reject misspelled titles, random characters, accidental dates, brands, interface chrome, or watermark-like marks.
- Avoid glossy 3D rendering, neon gradients, smooth vectors, stock-photo polish, cute cartoons, generic “Chinese style,” and unrequested political or propaganda symbolism.
- Preserve user-approved elements during edits; state invariants explicitly in the edit prompt.
