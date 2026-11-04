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

## November 3 expanded Day 7 lesson revision — not yet live-tested
- Eight Yes/No government policy prompts were added to the saved state schema, PDF and completion count; existing field IDs remain unchanged. The completion denominator is now **17**.
- Revised sequence totals approximately 87 minutes of HTML + 10-minute separate seven-question all-MC Google Form; actual classroom timing has not been measured.
- Historical child labor now includes family economics and an ethical discussion, five images, government-change comparison and Populism; Section 7 includes YouTube Scripps News and 2023 NYT reporting.
- The exact teacher-supplied modern photograph is **not yet committed locally**: Section 7 currently references a published photo of the same 14-year-old construction worker via Scholastic, whose embedding in school browsers needs a live check. Other new external historical photos also need a live check and ideally local copies.
- Saving protocol, namespace, endpoint, cloud API, localStorage keys and existing answer field IDs have not changed. Test existing-alias restoration and new field round trip, including all eight radio controls, before classroom use.


## November 3 revision: expanded analytical checks
- Sinclair's question now asks whether he would consider the book a success, using his reported disappointment about workers' welfare; same response ID `jungleWriting`.
- Historical child labor context includes two distinct 1900 measures: 18.2% of ages 10–15 worked, and 79.8% of ages 10–14 attended some school. These are **not** interchangeable age cohorts and school attendance does not prove lack of work.
- Existing `hineWriting` now asks students to take the role of a 1905 lawmaker, weighing workers, families, employers, and accompanying reforms.
- New saved fields: `govWriting`, `farmWriting`, `article1–article3`, and `video1–video5`. The state schema now contains **27 fields**, and the completion denominator is **27**. Original saved field IDs, Apps Script endpoint, lesson namespace, revision and save functions remain unchanged.
- Only one `assets/pullman.jpg` image remains. The substitutions in the original photo gallery and Populist section still need **live image-load and zoom checks** (Populist image is externally hosted).
- Extra article/video questions extend reading time. The original 87-minute HTML estimate is no longer reliable. Time this with a student before classroom use; protect the separate 10-minute Google Form.
- **Release not verified:** existing-alias recovery after schema expansion, new radio selections round-trip through cloud, completion grade, both PDFs, image and zoom availability on school devices, and video availability. Do not change or clear student work during tests. Use an unused test alias.
