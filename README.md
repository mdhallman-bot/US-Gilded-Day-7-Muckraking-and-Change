# Day 7 — Exposing Injustice, Creating Change

**Status: PRE-RELEASE / NOT YET CLASSROOM-VERIFIED**

Lesson: Monday, November 9, 2026 (100 minutes). Central question: Why does exposing injustice sometimes lead to rapid change, while other problems take decades to address?

## Backend configuration (do not modify deployed student work)

- Lesson ID: `us-gilded-age-day-7-exposing-injustice-2026`
- Contract version: `gilded-day7-state-v1`
- Destination tab: `Gilded_Day7_Responses`
- Apps Script property: `SHEET_ID` (configured in Apps Script, not in HTML)
- Confirm exact endpoint in `index.html`: `https://script.google.com/macros/s/AKfycbwjLslBUQSR9NjbnEwQg7veRKztLTD68LMHxxXMFe93vi1GKhV5HrOFIFKrEGw70xrY1w/exec`
- No secret and no real student names in the assignment.

## Contents
- `index.html` — complete interactive student lesson, username-gated load, immediate local save, revision-verified cloud autosave, two PDF routes, sentence frames, hover/tap vocabulary definitions
- `assets/jspdf.umd.min.js` — pinned local jsPDF 2.5.2 with upstream license notice
- `assets/pullman.jpg` — reusable historical labor image copied from the Day 6 project
- Library of Congress photo/document images currently linked to the LOC host, rather than copied locally. **Network availability and image zoom need verification on school Chromebooks.** Source links remain available as fallbacks.

## Release gates — MUST test
1. Exact `SHEET_ID` Script Property and deployment diagnostic `ok:true` with correct lesson/tab.
2. Enter throwaway alias (at least 2 letters and 2 numbers), type into multiple fields, click Save now, verify **Cloud verified** and correct Sheet row.
3. Reload; verify all controls return. Repeat in a second browser/device with the same alias.
4. Simulate network failure and recovery. Ensure local copy survives and changes retry.
5. In two tabs, save a newer snapshot and test that stale changes do not overwrite it.
6. Generate and **open** both PDFs with short and 1,000+ character responses; inspect the prominent alias/completion header and every response.
7. Check all images enlarge, return without resetting work, and their attribution is correct.
8. Audit Chrome console and network; verify PDF library loads from this repository.

This is not the separate 7-question all-MC Google Form (to be created later).

Note: Images hosted by the Library of Congress and Google Apps Script are not guaranteed to function without network access; student work and PDF rendering use local persistence and locally hosted jsPDF. Do not assign to students until the teacher-side live tests pass.
