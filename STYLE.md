# EXAMIND Documentation — Authoring & Structure Guide

> **Internal guide.** This file is intentionally **not** listed in `SUMMARY.md`, so it is not published to the GitBook site. It defines the conventions for authoring and structuring EXAMIND's customer-facing documentation — for both manual edits and automated/continuous updates.

## 1. Document only released capabilities

Only document behavior that is live in the **released** product. Do not document unreleased plans or in-progress work until it ships. When in doubt, the product **source code is the source of truth** for what has shipped (`feedback-machines`, `examind-web`).

## 2. Landing / menu pages

Every section landing page (a `README.md` with child pages) must orient the reader — **never a bare list of links.**

**Structure:**

1. **Title**
2. **Orientation** — 1–3 sentences: what this section is and who it's for. For concept-light sections, this doubles as the "what-is."
3. **Child links, each with a one-line description, kept high and scannable** — as cards for a few items, or a described list when there are many (see §6).
4. **Deeper context (only if needed)** — a short "How it works" block *below* the cards, or a dedicated **Overview** child page (first card) when the concept is substantial.

**Rules:**

- No page is only links.
- Every link carries a one-line description.
- Brief orientation goes **above** the links; deeper concept goes **below** them (or on a linked page) — never bury navigation under a wall of prose.

## 3. Diátaxis — keep the four modes distinct

Documentation serves four distinct needs (the [Diátaxis](https://diataxis.fr) framework). A page should do **one** of these well, not blur several:

- **Explanation** (*understanding-oriented*) — what something is and why it matters; our conceptual "Overview" / "what-is" pages. This is the layer EXAMIND docs have historically lacked, so it's usually where a gap is.
- **How-to guide** (*task-oriented*) — numbered steps to accomplish a specific goal; most existing pages. Keep them focused on the task; don't pad them with concept.
- **Reference** (*information-oriented*) — dry, factual lookup (e.g., the LMS Compatibility Matrix, a question type's options). Complete and accurate over narrative.
- **Tutorial** (*learning-oriented*) — a guided first experience for a newcomer. Rare in our docs; don't force one.

**Applying it:**

- Separate **what / why** (explanation) from **how** (how-to). A small concept → inline orientation on the landing page; a substantial concept → a dedicated **Overview** (explanation) page.
- Keep each page in a single mode. When a how-to needs concept, **link to the explanation** rather than repeating it (see §4).
- When catching docs up to a product change, ask which mode the gap is in — a new capability usually needs **explanation first** (what it is), then how-to coverage.

## 4. Cross-link, don't duplicate

When a capability surfaces in two places (e.g., Feedback Machines is also the engine behind EXAMIND's Essay/Simulation assessment types), give it **one canonical home** and **cross-link** to it from the other. Never copy content between pages.

## 5. Images

- **Allowed:** product screenshots and integration logos (LMS / proctoring).
- **Not allowed:** license-restricted third-party decorative art (e.g., stock illustrations under a personal-use-only license).
- Prefer screenshots accurate to the current released UI — they double as automatable artifacts for ongoing updates.

## 6. GitBook card syntax

Cards are a `data-view="cards"` table. Include a **title** column, a **description** column, and a hidden `data-card-target` (content-ref) column so the whole card is a link. A cover-image column is optional and, per the image policy, used only for real screenshots.

**Choose the format that's most scannable for the count and content — these are defaults, not rules. Use judgment; don't over-fit a card count.** The test is always the reader's: can they find the right link fast (time) and tell what each one is (clarity)?

- **A few items (~2–4) with descriptions → cards**, sized to fill the row: add `data-card-size="large"` to the `<table>` for 2 per row (and a clean 2×2 for 4); the Medium default (3 per row) suits 3.
- **Many items (~6+) → a described list** — a link plus a one-line description per row, optionally grouped under subheadings — usually beats a large card grid: it stays scannable and doesn't push the rest of the page far down.
- **In between → whichever reads better** on that specific page.

Example (title + description, no cover):

```html
<table data-view="cards"><thead><tr><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody>
<tr><td><strong>Installation</strong></td><td>Set up the EXAMIND Excel add-in.</td><td><a href="installation.md">installation.md</a></td></tr>
</tbody></table>
```
