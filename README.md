# FORENSICS — The Missing Window

**T-MODS cybersecurity investigation event | Case N-114 | HOD demonstration**

A working, self-contained, browser-based prototype for a university digital-forensics competition. The app is implemented in **one HTML file** with embedded CSS, JavaScript and 17 synthetic evidence artifacts. No server or dependencies are required to explore the demo.

## Try the demo

1. Download [index.html](./index.html) (GitHub file page → **Download raw file**).
2. Open it using Microsoft Edge or Chrome.
3. Select **Play cinematic briefing**.
4. Investigate the Evidence Vault, CCTV Viewer, Persons of Interest, Timeline Lab and Investigation Board.
5. Submit a structured final report to see the **prototype** scoring rubric.

### Optional browser-hosted demo

To enable GitHub Pages for this repository: **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**. Once publishing is completed, open the URL GitHub provides. GitHub Pages is not automatically enabled by this commit.

## Demo functionality

- Six-scene cinematic briefing with optional browser speech narration and captions.
- 17 internally consistent fictional evidence artifacts with file downloads and SHA-256 manifest.
- Search, filter and bookmarking in the evidence vault.
- Visual *reconstructions* of two CCTV event indexes (not real CCTV footage).
- Camera clock normalization calculator.
- Four fictional suspects, notes and evidence linking.
- Investigator-built timeline with CSV export.
- Structured final submission, provisional rubric and JSON report export.
- Local browser persistence; responsive layout.

## Limitations

**This is a stakeholder demo, not production competition infrastructure.** The case, identities, logs and dates are invented for education. All submission scoring happens in browser JavaScript and can be reverse engineered; scores are not protected against repeat submissions, and team authentication or synchronized online leaderboards are not implemented. Written narratives still need human review. For a real competition, move grading and answer keys to a protected backend, add accounts, audit logs, team-specific datasets and secure time controls.

**Organizer solution is intentionally not published in this repository.** Because the prototype grading code is visible to clients, do not deploy it as an unmodified live competition challenge.

Case date is fictional: **14 November 2026**.
