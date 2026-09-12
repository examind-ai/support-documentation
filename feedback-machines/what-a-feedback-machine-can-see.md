---
icon: eye
description: >-
  What a Feedback Machine can take into account from pasted text, .docx, and
  .pdf submissions — so the submission format matches what you want evaluated.
---

# What a Feedback Machine Can See in Submissions

The format a submission arrives in decides what the Feedback Machine can take into account. All three formats carry the words. They differ in what else comes through — images, visual design, and exact formatting — so match the format to what your criteria ask about.

| You want it to evaluate…                              | Pasted text | `.docx`    | `.pdf`                     |
| ----------------------------------------------------- | ----------- | ---------- | -------------------------- |
| The words, paragraphs, headings, and lists            | ✓           | ✓          | ✓                          |
| Bold and italics                                      | ✓           | ✓          | ✓                          |
| Images, charts, figures, and diagrams                 | —           | —          | ✓                          |
| Colors, layout, visual design, and use of white space | —           | —          | ✓ (as a reader would)      |
| Exact font, font size, margins, and line spacing      | —           | ✓          | — (judged by eye)          |
| Headers, footers, and footnotes                       | —           | ✓          | ✓ (as text on the page)    |
| Word count and page count                             | words only  | ✓          | approximate                |

## `.pdf` — sees the page the way a reader does

The whole document goes to the AI model as-is, so it sees what a person opening the file sees: the text, images, charts, figures, colors, layout, and how the page or slide is composed, including the balance of white space. Use `.pdf` for anything visual — presentation decks, reports with figures, posters, infographics, or any work where design is part of what you're assessing.

What it can't do is measure. A `.pdf` doesn't carry the font name, point size, or margin width as data the way a Word file does, so the model judges those the way a person would — by eye. It can tell that a document looks like a standard 12-point serif with ordinary margins; it can't confirm that it is Times New Roman 12 with one-inch margins. Word and page counts are estimated the same way. If a criterion depends on an exact formatting specification, ask for `.docx`.

## `.docx` — exact formatting facts, no images

The document's text and structure go to the model together with a precise readout of formatting details taken from the file itself. Criteria such as "12-point Times New Roman, double-spaced, one-inch margins, page numbers in the footer, footnotes in 10 point" are checked against facts, not by eye.

**What the machine knows about a `.docx`:**

* **Text and structure** — paragraphs, headings, bulleted and numbered lists, the contents of tables and text boxes, bold, italics, strikethrough, superscript and subscript, hyperlinks, footnotes, and page breaks.
* **Fonts** — every font used in the document and which one is the main one.
* **Font sizes** — every size used, which one is the main one, and the size of the footnote text.
* **Line spacing** — the document's predominant setting.
* **Page margins** — top, bottom, left, and right.
* **Paragraph layout** — alignment (left, centered, right, justified), first-line and hanging indents, space before and after paragraphs, and blank lines between them.
* **Headers and footers** — their text, which pages they appear on, and whether they include a page number.
* **Counts** — words, characters, paragraphs, and pages.

Fonts and sizes are known for the document as a whole: which ones appear and which dominates, not which words are set in which. "Body text is 12 point" is a fact the machine can check; "the title is 16 point" it can infer only from a 16-point size being present.

**What the machine can't see in a `.docx`:**

* **Images, photos, and figures.** Where each one was, a notice appears in the submission view saying the image isn't part of the evaluation. The student's own description of the image (its alt text), if they gave one, is kept.
* **Charts, SmartArt, shapes and drawings, equations, and embedded objects** such as an Excel table. These are left out without a notice.
* **Comments.** Tracked changes are read as if all changes had been accepted.
* **Underlining, text color, and highlighting.**
* **Table formatting** — borders, shading, and column widths. The contents of the table are seen.
* **Page size and orientation.**

{% hint style="info" %}
**Need another `.docx` formatting property evaluated?** Most formatting details exist in the file, and adding one is usually a quick change. Contact support with the criterion you have in mind.
{% endhint %}

## Pasted text — the words

Pasted text carries the words and their basic structure — paragraphs, headings, lists, and bold or italic emphasis when pasted from a formatted source. There are no fonts, spacing, margins, or pages to evaluate. Any image in the pasted content is left out, and a notice appears in the submission view where it was. Word and character counts are exact.

## Choosing a format

* **Visual work** — decks, figures, design, layout: `.pdf`.
* **A formatting specification to comply with** — fonts, margins, spacing, footers: `.docx`.
* **Both in one assignment** — for example a report with charts that must also meet a formatting spec: choose the one that matters more to the grade, and evaluate the other by eye in your own review. Feedback Machines shows you every submission alongside its evaluation.
