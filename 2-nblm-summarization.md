---
layout: default
title: 2 - Summarizing
nav_order: 3
parent: Workshop Activities
---

# Summarizing Text, Audio & Video

![NotebookLM source summary view](images/nblm-summarize-text2.gif)

In this activity you'll use NotebookLM to transform uploaded documents, meeting transcripts, and videos into audience-ready summaries — then refine, translate, and output them in multiple formats.

> **Important:** Even when grounded in your sources, NotebookLM can still miss nuances or make errors. Treat its output as a highly capable first draft, not a finished product. Always verify critical facts and quotes against the original source.

If you need help at any time, ask the instructor.

---

## Learning goals

By the end of this activity, you will be able to:

* Generate short and long **source-grounded summaries** for text, audio, and video.
* Adapt summaries for **different audiences and purposes** (beginner vs. expert, student vs. supervisor).
* Combine multiple sources into a **cross-document synthesis**.
* Use **citations and source previews** to verify and correct NotebookLM's summaries.
* Adjust **tone, length, and language level** to fit your real-world use case.

---

## 1) Getting started: upload your sources

1. Open [notebooklm.google](https://notebooklm.google/) and click **Create** to start a new notebook. Name it something like "Summarization Practice."
2. Upload the three sample documents for this module:
   * [Document 1](images/badge-article.pdf)
   * [Document 2](images/badge-article-2.pdf)
   * [Document 3](images/badge-article-3.pdf)
3. Confirm each document appears in the **Sources** panel on the left.
4. Click the first document and read its **auto-generated source summary**, then skim the original document.
5. Check that the text is legible — if you see garbled characters it likely means the PDF is image-only and needs an OCR'd version.

> **Pro tip:** Mix formats in one notebook (PDF + webpage + slides). NotebookLM can weave them together, but always know which source each claim came from.

---

## 2) Summarize with purpose: audience, tone & length

Avoid vague prompts like "summarize this." You'll get generic, forgettable output. Anchor every summary in a **real scenario** with a specific audience, tone, and word count.

**Scenario A — parent-facing promotional copy**

1. In the **Sources** panel, de-select Documents 2 and 3 so only **Document 1** is active.
2. Paste this prompt into the chat box:
