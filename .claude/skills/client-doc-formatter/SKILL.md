---
name: client-doc-formatter
description: Transforms raw consulting notes or bullet points into polished, client-ready documents. Use this skill whenever the user wants to turn messy notes, bullets, or rough drafts into a professional consulting deliverable — including status updates, executive summaries, one-pagers, or client briefs. Trigger on phrases like "make this client-ready", "clean this up for the client", "turn these notes into a doc", "format this as a status update", "write an exec summary from this", or any request to produce a polished document from rough input. Always use this skill when consulting document output is the goal, even if the user doesn't say "skill" or "document formatter" explicitly.
---

# Client-Ready Document Formatter

Transforms raw bullet points or consulting notes into polished, professional documents ready to share with clients.

## Supported Document Types

- **Status Update** — Progress report on a project or workstream
- **Executive Summary** — High-level synthesis for senior stakeholders
- **One-Pager / Brief** — Concise standalone document on a topic or recommendation
- **Meeting Summary** — Structured recap with key decisions and next steps

---

## Workflow

### Step 1 — Identify the Document Type

If the user hasn't specified, infer the best format from the content:
- Progress/milestone info → Status Update
- Strategic or decision-focused → Executive Summary
- Single topic overview → One-Pager
- Meeting context → Meeting Summary

If ambiguous, ask: *"Should I format this as a status update, exec summary, one-pager, or meeting summary?"*

### Step 2 — Clarify Audience (if unknown)

Ask if needed:
- Who is the audience? (e.g., client executive, project team, steering committee)
- Is there a client name or project name to include?

Skip this step if context is clear from the input.

### Step 3 — Produce the Document

Use the appropriate template below. Output clean markdown the user can copy-paste.

**Tone guidelines:**
- Professional but not stiff — clear, direct, confident
- Lead with the "so what" — clients care about impact and decisions, not activity
- Avoid internal jargon; translate to plain business language
- Use short paragraphs and headers; respect the reader's time

---

## Templates

### Status Update