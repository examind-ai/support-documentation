# Changelog — Documentation Catch-Up (EXI-33), first big drop

**Date:** June 4 2026 · **Branch:** `feedback-machines-docs` · **PR #2**

> Internal review note, not in `SUMMARY.md` (unpublished). Delete once reviewed.

## New pages

- **Feedback Machines:** Get Started · Build a Feedback Machine · Deliver to Students · Review & Export Results. *(Overview already existed.)*
- **Build › Assessments:** Essay Assessments · Simulation Assessments.
- **Our Approach** *(new section)*: Overview · Understanding Cheating Modes · Working with Online Proctoring · About EXAMIND.

## Rewritten / restructured

- **Welcome homepage** — now leads with a concise **"What EXAMIND can do"** overview + a "Where to start" card row. The mission/values/psychology-of-cheating/proctoring walls were moved **off** the homepage into the new **Our Approach** section (Diátaxis: support docs lead with capability, not company philosophy).
- **Understanding Cheating Modes** — refreshed to foreground **AI-generated content as the top threat**.
- **Online proctoring** — stance reversed: from "Structural Issues with Online Proctoring" to **"Working with Online Proctoring"**, framing EXAMIND as a **complement** to proctoring, compatible via third-party launch.
- **Section landing pages** (Get Started ×2, Build ×4, Assessments, Excel Assignments) — applied the landing-page pattern (orientation + described cards/lists) and removed the personal-use-only **Toonville** card covers. Question Types is now a described **list** (8 items).

## Accuracy corrections (from reading the code)

- **Feedback Machines can *auto-grade* Simulation assessments** — Simulation is a native EXAMIND assessment type, and linking a Feedback Machine to auto-grade it is optional. The **Essay** type is **instructor-graded** with an optional AI writing assistant. (Earlier framing and the Products KB implied FM "powers" these types; corrected per the code and per Kenny.) Fixed on the homepage, FM Overview, and Simulation page.
- **Review page** documents bulk import/export and machine modify, and deliberately does **not** document manual score override / regrade / feedback editing — those aren't in the code.

## Please verify (judgment calls)

- **Proctoring** — no proctoring code exists in `examind-web`; you confirmed it's third-party-launch compatibility (Honorlock/Proctorio) and the existing docs describe it. I kept the proctoring content on that basis — please confirm the framing.
- **About EXAMIND (mission/values)** — *deleted* per Kenny's call (per Diátaxis, company values don't belong in support docs).
- **FM Get Started** mentions launching from **Canvas** via LTI (that's what FM's code shows). Confirm whether other LMSs are supported for FM specifically.
- **FM "auto-grading at scale"** is achieved via class sharing + bulk import/export (not a labeled toggle); described that way.

## Deferred to next iteration

- Toonville covers are removed from the **main section landing pages**; decorative covers may still remain on **deeper/content pages** (e.g., individual dynamic-engine topics, information-for-students). The asset **files** are still in `.gitbook/assets` (left for a bulk cleanup once all references are gone).
- LMS-integration and proctoring-integration landing pages still use brand **logos** as covers — intentionally kept (logos are allowed).
- Deeper how-to detail with **screenshots** (FM build flow, essay room) — pending real product screenshots.

## Conventions

All new/edited pages follow `STYLE.md` (released-only · landing-page pattern · concept-vs-how-to · cross-link don't duplicate · image policy · card sizing by scannability).
