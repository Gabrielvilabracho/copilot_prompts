# Microsoft 365 Copilot prompt catalog

Objective: Produce an evidence-based Spanish guide to Microsoft 365 Copilot prompting, high-impact skills, implementation patterns, and reusable prompts. The final deliverable is `MICROSOFT_365_COPILOT_PROMPTS.md`.
Delivery: local Markdown document; this workspace is not a Git repository, so branch, commit, and PR evidence are unavailable. Verification uses structural checks, source validation, and prompt-count checks.

## Specs

S1. Research scope: "BUSCA TODO LO QUE PUEDAS SOBRE COPILOT, LOS PROMPTS Y SKILLS CON MAS USO Y IMPACTO EN TRABAJO EN LAS DIFERENTES CATEGORIAS QUE OFRECE COPILOT Y MICROSOFT 365."

S2. Analysis scope: "ANALISIS SUS SISNTAXIS, SY PROMPT SYSTEM". Explain a practical prompt system, syntax, grounding, context, limitations, and implementation patterns using authoritative Microsoft sources where available.

S3. Deliverable: "GENERA UAN LISTA EN .MD SOBRE LOS PROMPTS , SUS CATEGORIA, CONENIDO, COMO IMPLEMENTARLO Y CATEGORIZALOS , DAME EL DOCUEMNTO ESTRUCUTRADO". Create a structured Spanish Markdown catalog with categories, prompt content, implementation guidance, and source references.

S4. Coverage: "GNERA 10 PROMPTS POR CADA UNO DE LAS CATEGORIAS IDENTIFICADAS." Every identified prompt category must contain exactly 10 reusable prompt templates.

S5. Research plan: prioritize current Microsoft Learn, Microsoft Support, Microsoft Adoption, WorkLab, and official product documentation; distinguish documented facts from synthesis; avoid unsupported popularity rankings when usage data is unavailable.

S6. Intended audience assumption: knowledge workers, team leads, and Microsoft 365 administrators who need practical prompts for daily work. Cover Microsoft 365 Copilot rather than GitHub Copilot except where a boundary clarification is useful.

S7. Document design: lead with a quick-start prompt formula, use progressive disclosure, tables, copy-ready prompt templates, placeholders, implementation notes, risk cautions, and a source bibliography.

S8. Intranet publishing formats: "genra el formato 2 y otro con el formato 3 y un tercero con el formato 1 ." Produce three clean, editorial, professional variants: a multipage Markdown site with relative navigation, a single Markdown page with anchor navigation, and a SharePoint/Microsoft 365 modern-page publishing package.

S9. Scheduled Copilot tasks: "genera una  lista de ideas y como aplicarlas con sus ejeemplos y templetes". Add a practical, source-backed guide to Copilot Scheduled tasks with ideas, schedules, copy-ready prompts, implementation steps, approval safeguards, and reusable templates.

## Tasks

- T1 — S1, S2, S5, S6 — Route: delegated read-only research; status: completed; evidence: eight official Microsoft sources mapped, S1/S2/S5/S6 covered.
- T2 — S2, S3, S7 — Route: inline synthesis and document architecture; status: completed; evidence: OCFE framework, syntax, taxonomy, implementation, governance, impact, and antipattern sections written.
- T3 — S3, S4, S7 — Route: inline drafting; status: completed; evidence: `MICROSOFT_365_COPILOT_PROMPTS.md` contains 10 categories and 100 prompts.
- T4 — S3, S4, S5 — Route: inline structural and citation verification; status: completed; evidence: automated check passed for 10 categories, exactly 10 prompts per category, seven resolved footnotes, and balanced code fences.
- T5 — S8 — Route: inline; status: completed; evidence: `intranet/markdown-multipage/` contains a portada, 10 category pages, usage guidance, governance, and sources with previous/home/next navigation.
- T6 — S8 — Route: inline; status: completed; evidence: `MICROSOFT_365_COPILOT_PROMPTS.md` now includes editorial metadata, a primary navigation table, 10 stable category anchors, and local previous/home/next links.
- T7 — S8 — Route: inline; status: completed; evidence: `intranet/sharepoint/` contains the publishing guide, 14-page site map, category-page template, and homepage content.
- T8 — S4, S8 — Route: inline; status: completed; evidence: validation passed for 100 prompts in the single-page edition, 10 multipage categories with 10 prompts each, all local links, and 10 stable anchors.
- T9 — S9 — Route: inline; status: completed; evidence: `intranet/markdown-multipage/13-tareas-programadas.md` contains 24 ideas, 24 frequency recommendations, 24 implementation notes, four reusable templates, safeguards, maintenance guidance, and three official Microsoft sources; integrated into all intranet navigation variants.

## Log

L1. BUSCA TODO LO QUE PUEDAS SOBRE COPILOT, LOS PROMPTS Y SKILLS CON MAS USO Y IMPACTO EN TRABAJO EN LAS DIFERENTES CATEGORIAS QUE OFRECE COPILOT Y MICROSOFT 365. ANALISIS SUS SISNTAXIS, SY PROMPT SYSTEM , Y GENERA UAN LISTA EN .MD SOBRE LOS PROMPTS , SUS CATEGORIA, CONENIDO, COMO IMPLEMENTARLO Y CATEGORIZALOS , DAME EL DOCUEMNTO ESTRUCUTRADO , Y GNERA 10 PROMPTS POR CADA UNO DE LAS CATEGORIAS IDENTIFICADAS.

L2. Research plan: build an educational guide supported primarily by official Microsoft sources. Treat “most used” as “commonly documented and broadly applicable” unless Microsoft publishes comparable usage data. Planned categories will be selected from Microsoft 365 application surfaces and cross-application work outcomes after source review.

L3. Forecast: approximately 1,200–2,000 authored Markdown lines because each identified category requires 10 implementation-ready prompts. No Git delivery strategy applies in this empty non-repository workspace.

L4. Research outcome: Microsoft documents the prompt framework as goal, context, source, and expectations. No universal cross-product prompt-length limit or current comparable ranking of “most used” prompts was verified, so the guide avoids both claims.

L5. Final taxonomy: search/synthesis, writing/editing, data/decisions, presentations, email/calendar, meetings, collaborative knowledge, surveys, document management, and planning/automation.

L6. Verification: `MICROSOFT_365_COPILOT_PROMPTS.md` has 389 lines. Structural validation reported `PASS categories=10 prompts=100`, with 10 prompts in every category, seven resolved footnotes, and balanced code fences.

L7. User requested all three intranet delivery variants after clarification: format 2 (multipage Markdown), format 3 (single Markdown), and format 1 (SharePoint/Microsoft 365 modern pages).

L8. Intranet editions completed. Automated validation reported: `PASS single_prompts=100 multipage_categories=10 multipage_prompts=100 local_links=valid stable_anchors=10`.

L9. User requested ideas, examples, and templates specifically for Copilot's scheduled task feature. Official Microsoft Support confirms the rename from Scheduled prompts to Scheduled tasks, Task Hub management, natural-language scheduling, Copilot license requirement, and initial web/desktop availability.

L10. Scheduled-task guide completed and verified. Validation reported: `PASS ideas=24 frequencies=24 implementation_notes=24 sharepoint_pages=15 local_links=valid navigation=integrated`.
