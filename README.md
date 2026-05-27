
# Creator Shortlist Deck - Soshman



---

A no-install pitch tool for building, editing, and exporting influencer shortlists — built for speed, designed to impress clients.

---

**What it does**
- Multi-page interactive deck builder (cover, brand context, creator cards, conclusion)
- Inline editing — click any field to edit directly
- Internal-only sections visible to SoshMan editors, stripped on client export
- HTML export (client-safe) and PDF export
- AI-generated "Why This Creator" blurbs via Claude API
- Data auto-saved to localStorage per deck

---

**Tech stack**
- Vanilla HTML + React (loaded via CDN, no build step)
- Babel standalone (JSX in-browser transpilation)
- Plus Jakarta Sans + Playfair Display (Google Fonts)
- Anthropic Claude API (`claude-sonnet-4-20250514`) for AI features
- No backend, no framework, no dependencies to install


**How to use**
- Edit any text field by clicking on it
- Toggle **Preview Mode** to see the client view (hides internal sections)
- **Export HTML** — downloads a clean client-safe file with all internal content stripped
- **Export PDF** — triggers browser print dialog, optimised for A4
- Add/remove creator cards from the toolbar
- Internal red boxes on page 2 are editor-only and never reach the client


**Known limitations**
- No multi-user collaboration (one editor at a time)
- localStorage is per-browser — deck data doesn't sync across devices
- PDF export quality depends on the browser's print engine (Chrome recommended)
- API key is client-side — not suitable for production use with a real key in a public repo

---

**Roadmap / planned**
-  Supabase or Notion backend for persistent deck storage.
-  Brand color theming per client.
-  Creator card drag-to-reorder.
-  Password-protected client share links.
-  Multi-deck management from a dashboard.

---

**Author**

Vasudev Pal
- SoshMan Media [thesoshalman@gmail.com]
