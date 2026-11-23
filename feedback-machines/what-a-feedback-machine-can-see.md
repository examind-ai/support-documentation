---
icon: eye
description: >-
  What a Feedback Machine can take into account from pasted text, .docx, .pdf,
  and recorded submissions — so the submission format matches what you want
  evaluated.
---

# What a Feedback Machine Can See in Submissions

The format a submission arrives in decides what the Feedback Machine can take into account. For written work, all three document formats carry the words. They differ in what else comes through — images, visual design, and exact formatting — so match the format to what your criteria ask about.

| You want it to evaluate…                              | Pasted text | `.docx`    | `.pdf`                     |
| ----------------------------------------------------- | ----------- | ---------- | -------------------------- |
| The words, paragraphs, headings, and lists            | ✓           | ✓          | ✓                          |
| Bold, italics, and underlining                        | ✓ (bold, italics) | ✓    | ✓                          |
| Images, charts, figures, and diagrams                 | —           | —          | ✓                          |
| Colors, layout, visual design, and use of white space | —           | —          | ✓ (as a reader would)      |
| Exact font, font size, margins, and line spacing      | —           | ✓          | — (judged by eye)          |
| Headers, footers, footnotes, and endnotes             | —           | ✓          | ✓ (as text on the page)    |
| Word count and page count                             | words only  | ✓          | approximate                |

## `.pdf` — sees the page the way a reader does

The whole document goes to the AI model as-is, so it sees what a person opening the file sees: the text, images, charts, figures, colors, layout, and how the page or slide is composed, including the balance of white space. Use `.pdf` for anything visual — presentation decks, reports with figures, posters, infographics, or any work where design is part of what you're assessing.

What it can't do is measure. A `.pdf` doesn't carry the font name, point size, or margin width as data the way a Word file does, so the model judges those the way a person would — by eye. It can tell that a document looks like a standard 12-point serif with ordinary margins; it can't confirm that it is Times New Roman 12 with one-inch margins. Word and page counts are estimated the same way. If a criterion depends on an exact formatting specification, ask for `.docx`.

## `.docx` — exact formatting facts, no images

The document's text and structure go to the model together with a precise readout of formatting details taken from the file itself. Criteria such as "12-point Times New Roman, double-spaced, one-inch margins, page numbers in the top-right header, footnotes in 10 point" are checked against facts, not by eye.

**The paper-formatting requirements of APA, MLA, and Chicago (CMOS / Turabian) are all covered** — fonts and sizes, double spacing with single-spaced block quotations or notes, one-inch margins, half-inch first-line and hanging indents, block quotations, running heads and page numbers with their position, title-page layout, footnotes or endnotes and their size and spacing, and a reference list on its own page.

**What the machine knows about a `.docx`:**

* **Text and structure** — paragraphs, headings, bulleted and numbered lists, the contents of tables and text boxes, bold, italics, underlining, strikethrough, superscript and subscript, hyperlinks, and page breaks.
* **Fonts** — every font used in the document and which one is the main one.
* **Font sizes** — every size used and which one is the main one.
* **Line spacing** — the document's predominant setting, and every paragraph whose spacing differs from it (a single-spaced block quotation or bibliography inside a double-spaced paper).
* **Page margins** — top, bottom, left, and right, and how far the header and footer sit from the page edge.
* **Paragraph layout** — alignment (left, centered, right, justified); first-line, hanging, and block indents with their exact size; space before and after paragraphs; and blank lines between them.
* **Headers and footers** — their text, which pages they appear on (all, first page only, odd or even pages), whether they include a page number, and whether they sit left, centered, or right.
* **Footnotes and endnotes** — their text, numbered as they appear in the document, plus the size, line spacing, and indentation of the note text itself. Footnotes are read separately from footers: a footnote is a numbered note at the bottom of the page, a footer is the text that repeats on every page.
* **Counts** — words, characters, paragraphs, and pages.

Fonts and sizes are known for the document as a whole: which ones appear and which dominates, not which words are set in which. "Body text is 12 point" is a fact the machine can check; "the title is 16 point" it can infer only from a 16-point size being present.

**What the machine can't see in a `.docx`:**

* **Images, photos, and figures.** Where each one was, a notice appears in the submission view saying the image isn't part of the evaluation. The student's own description of the image (its alt text), if they gave one, is kept.
* **Charts, SmartArt, shapes and drawings, equations, and embedded objects** such as an Excel table. These are left out without a notice.
* **Comments.** Tracked changes are read as if all changes had been accepted.
* **Text color and highlighting.**
* **Table formatting** — borders, shading, and column widths. The contents of the table are seen.
* **Page size and orientation.**

{% hint style="info" %}
**Need another `.docx` formatting property evaluated?** Most formatting details exist in the file, and adding one is usually a quick change. Contact support with the criterion you have in mind.
{% endhint %}

## Pasted text — the words

Pasted text carries the words and their basic structure — paragraphs, headings, lists, and bold or italic emphasis when pasted from a formatted source. There are no fonts, spacing, margins, or pages to evaluate. Any image in the pasted content is left out, and a notice appears in the submission view where it was. Word and character counts are exact.

## Recordings

Students submit one audio or video file of up to 2 GB: MP4, MOV, WebM, MKV, M4V, M4A, MP3, WAV, OGG, FLAC, Opus, or AAC.

Every recording is transcribed. The evaluator reads the timestamped transcript together with measured delivery facts: running time, pace, pauses, filler words, and each speaker's share of the talking. Whether it also hears or watches the recording follows from your criteria:

| What the evaluator receives | When | What it adds |
| --- | --- | --- |
| **Transcript only** | No criterion needs to hear or see the recording | — |
| **Audio and transcript** | A criterion needs to hear it | Tone, emphasis, pronunciation, and vocal delivery |
| **Video and transcript** | A criterion needs to see it | Slides, what is shown on screen, gestures, and eye contact |

Once one criterion needs to hear or see the recording, the evaluator does so for every submission to the machine. The **Configure & Publish** step shows the result under **What the Evaluator Receives**. You don't set it there: to change it, change the criteria on the review step, for example by asking in the [Modify panel](modifying-a-feedback-machine.md).

{% hint style="warning" %}
**Watching a video limits its length.** When any criterion is judged from the video, students must submit a video, not audio alone, of no more than 45 minutes; a longer one is refused at upload. Those criteria carry an **Evals visuals** tag on the review step. To accept longer recordings, remove or reword them.
{% endhint %}

### Who is speaking

When a recording has more than one voice, the machine needs to know which one is the student's. Set **Speakers in the Recording** on the **Configure & Publish** step; the builder suggests one from your assignment instructions:

* **Only the student speaks** — the whole recording is treated as the student's.
* **Others speak, and the student's role can be told apart from theirs** — describe the student's role (for example, the interviewee, who answers the questions). The student's voice is found from what is said, and the student is asked to confirm only when that's unclear.
* **Several people speak, and the transcript alone can't tell which one is the student** — before submitting, each student picks which speaker they are from a summary of what each speaker said.

### Reviewing a recording

The submission view plays the recording above its transcript, laid out as timed turns labeled by speaker. Feedback cites moments by their timestamp, and selecting one takes the player to that point.

## Choosing a format

* **Visual work** — decks, figures, design, layout: `.pdf`.
* **A formatting specification to comply with** — APA, MLA, Chicago, or your own: `.docx`.
* **Spoken work** — presentations, speeches, interviews, role-plays: an audio or video recording.
* **Both in one assignment** — set the submission type to **DOCX or PDF** and allow more than one file per submission (see [Build a Feedback Machine](build-a-feedback-machine.md)). A single submission can then mix the two formats, and all files are evaluated together: a report as `.docx` for the formatting criteria alongside a slide deck as `.pdf` for the visual ones, each file read with what its format carries.
