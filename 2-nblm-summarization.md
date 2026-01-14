---
layout: default
title: 2 - Summarizing
nav_order: 7
parent: Workshop Activities
---

# Summarizing Text, Audio & Video)
<img src="images/nblm-summarize-text2.gif" style="float:right;width:420px;padding:10px;border:1px solid #555;" alt="NotebookLM source summary view">

In this module, you’ll use **NotebookLM** to transform your uploaded documents, meeting transcripts, and even videos into audience-ready summaries—and then refine, translate, and output those summaries in multiple formats.

> **Important:** AI tools can still miss nuances—even when grounded in your sources. Treat output as a highly capable assistant, not an autopilot. Always verify critical facts and quotes.

If you need help at any time, please ask the instructor.

---

## Learning goals

By the end of this activity, you will be able to:

- Generate short and long **source-grounded summaries** for text, audio, and video.  
- Adapt summaries for **different audiences and purposes** (beginner vs expert, student vs supervisor, parent vs colleague).  
- Turn one or more sources into a **study guide, FAQ, or outline** using NotebookLM.  
- Use **citations and source previews** to verify and correct NotebookLM’s summaries.

---

## 1) Getting Started: Upload Your Sources

1. Create a new notebook in **NotebookLM**: from the dashboard, click **Create**.  
2. Upload the sample sources for this module:
   - [Document 1](images/badge-article.pdf){:target="_blank"}
   - [Document 2](images/badge-article-2.pdf){:target="_blank"}
   - [Document 3](images/badge-article-3.pdf){:target="_blank"}
3. Confirm that each document appears under the **Sources** panel on the left.  
4. Click the first document → read the **auto-generated source summary** and skim the original document.  
5. Check that the text is legible (no garbled OCR). If a document is mostly images without selectable text, upload a text-based or OCR’d version if possible.

> **Pro tip:**  
> Mix formats in one notebook (PDF + webpage + slides). Later, you can ask NotebookLM to summarize or compare across formats as long as the sources are text-readable.

---

## 2) Summarize With Purpose (Audience • Tone • Length)

Avoid generic prompts like “summarize this.” You’ll get vague, forgettable output. Instead, anchor the summary in a **real scenario**.

**Scenario:** You’re preparing promotional copy for parents about the University Makerspace / Library Digital Scholarship Commons.

1. In the **Sources** panel, **de-select** Documents 2 and 3 so that only **Document 1** is active.  
2. In **Chat**, ask something like:

```text
Create a 180–220 word summary for parents explaining how the University Makerspace (Library Digital Scholarship Commons) helps with co-op job searches and post-graduation employment. 

Use plain language, include three concrete benefits supported by evidence from Document 1, and include inline citations.
