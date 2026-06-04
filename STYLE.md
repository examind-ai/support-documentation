# EXAMIND Documentation — Authoring & Structure Guide

> **Internal guide.** This file is intentionally **not** listed in `SUMMARY.md`, so it is not published to the GitBook site. It defines the conventions for the documentation catch-up and enhancement (intention EXI-33), and is intended as a basis the CTO can reuse to guide continuous, automated doc updates.

## 1. Document only released capabilities

Only document behavior that is live in the **released** product. Do not document unreleased plans or in-progress work until it ships. When in doubt, the product **source code is the source of truth** for what has shipped (`feedback-machines`, `examind-web`).

## 2. Landing / menu pages

Every section landing page (a `README.md` with child pages) must orient the reader — **never a bare list of links.**

**Structure:**

1. **Title**
2. **Orientation** — 1–3 sentences: what this section is and who it's for. For concept-light sections, this doubles as the "what-is."
3. **Child links as cards, each with a one-line description** — kept high and scannable.
4. **Deeper context (only if needed)** — a short "How it works" block *below* the cards, or a dedicated **Overview** child page (first card) when the concept is substantial.

**Rules:**

- No page is only links.
- Every link carries a one-line description.
- Brief orientation goes **above** the links; deeper concept goes **below** them (or on a linked page) — never bury navigation under a wall of prose.

## 3. Concept vs how-to (Diátaxis-lite)

Separate **what / why** (concept) from **how** (steps):

- **Small concept** → inline orientation on the landing page.
- **Substantial concept** → a dedicated **Overview** page.
- Keep how-to pages task-focused; link out to the concept rather than repeating it.

## 4. Cross-link, don't duplicate

When a capability surfaces in two places (e.g., Feedback Machines is also the engine behind EXAMIND's Essay/Simulation assessment types), give it **one canonical home** and **cross-link** to it from the other. Never copy content between pages.

## 5. Images

- **Allowed:** product screenshots and integration logos (LMS / proctoring).
- **Not allowed:** license-restricted third-party decorative art. (The previous Toonville card illustrations are personal-use-only and are being removed.)
- Prefer screenshots accurate to the current released UI — they double as automatable artifacts for ongoing updates.

## 6. GitBook card syntax

Cards are a `data-view="cards"` table. Include a **title** column, a **description** column, and a hidden `data-card-target` (content-ref) column so the whole card is a link. A cover-image column is optional and, per the image policy, used only for real screenshots.

Example (title + description, no cover):

```html
<table data-view="cards"><thead><tr><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody>
<tr><td><strong>Installation</strong></td><td>Set up the EXAMIND Excel add-in.</td><td><a href="installation.md">installation.md</a></td></tr>
</tbody></table>
```
