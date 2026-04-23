---
name: Thesis proposal repository overview
description: Two-document LaTeX repo — active draft is an ICONTEC anteproyecto; root main.tex is the full thesis template now being adapted for the FLP prototype project
type: project
---

This repo has two distinct LaTeX documents:

1. **`draft/`** — Anteproyecto (ICONTEC format). Topic: web prototype for teaching Fundamentals of Interpretation and Compilation of Programming Languages (FLP) via syntax-directed languages. Authors: Jota Emilio López Ramírez (2259394) & Esmeralda Rivas Guzmán (2259580). Director: Carlos Andrés Delgado Saavedra. Universidad del Valle, Tuluá, 2026.

2. **Root `main.tex`** — Full thesis template (Capitulo_0 through Capitulo_6), previously about a hypermedia OVA but now being rewritten to match the FLP prototype thesis.

**Migration status (as of 2026-04-22, updated same day):**
- `Capitulo_0/1_Portada.tex` — Updated (new title, authors, director)
- `Capitulo_0/3_Agradecimientos.tex` — Updated (FLP context)
- `Capitulo_0/4_Resumen.tex` — Updated (FLP abstract)
- `Capitulo_1/1_PlanteamientoProblema.tex` — Rewritten (FLP problem description + research question)
- `Capitulo_1/2_Objetivos.tex` — Updated (FLP objectives table)
- `Capitulo_1/3_Alcance.tex` — Rewritten (FLP scope, deliverables, constraints)
- `Capitulo_1/4_Estructura.tex` — Rewritten (new 6-chapter structure description)
- `Bibliografia.bib` — Replaced with `draft/references.bib` sources
- `main.tex` — Updated pdfauthor/pdftitle in hyperref, updated cap3 title
- `Capitulo_3/1_Encuesta.tex` — Rewritten (student survey n=27, teacher survey n=3 estimated, 5 priority concepts identified, implications for prototype)
- `CapituloAAnexos/1_EncuestaEstudiantes.tex` — New annex with full student survey instrument
- `CapituloAAnexos/2_EncuestaDocentes.tex` — New annex with full teacher survey instrument (3 professors, estimated data; professors note students arrive with deficiencies from prior courses)
- `main.tex` — Annexes section uncommented and wired to new files
- Capitulo_2, Capitulo_4, Capitulo_5, Capitulo_6 — Still contain OLD OVA content, pending rewrite

**Why:** The full thesis is written chapter-by-chapter based on the anteproyecto in `draft/`.
**How to apply:** When user asks to write a chapter, base it on the corresponding section in `draft/sections/` and `draft/references.bib`. The bibliography key names from `draft/references.bib` are now in `Bibliografia.bib` unchanged.
