# Portfolio leadership redesign

Working copy: `C:\Scripts\Github\Infrastructure\portfolio-redesign`
Branch: `codex/leadership-redesign`
Known-good baseline commit: `208ffdf`.

The archive had no Git metadata. A separate repository was initialized in the extracted site, and the original site was committed before changes. The surrounding Infrastructure repository and its existing untracked work were not modified. The source archive remains in Downloads; archived backup files remain intact.

## Changes

- Added `leadership/index.html`: technology capability lifecycle; 3–5 year strategy and operating/capital planning; incident recovery; Windows Server modernization; Service Desk operating model; conference/collaboration modernization. Existing Exchange and RingCentral cards in Experience are the canonical migration case studies.
- Updated Home with the leadership thesis, three direct exploration paths, lifecycle, evidence and links to all six detailed technical studies.
- Updated Experience with organizational responsibility and expanded existing Exchange and RingCentral cases. Titles, employers and dates were preserved.
- Updated About to explain the decision-making value of technical depth.
- Reframed Training as Learning & Innovation at its existing URL; retained every training entry and added Learn → Lab → Build → Validate → Apply plus applied AI/workforce augmentation.
- Projects is labeled Technical Capability and connects to Leadership, Skills and Learning. The complete existing catalog remains.
- Resume has a narrow Exchange wording update for consistency. Military content remains intact.
- All 15 pages share Home / Leadership / Technical / Experience / Learning / About / Resume navigation. Skills and Military remain in every footer and existing contextual links. No pages were removed; no original URL was removed.
- CSS retains existing layout classes with warm graphite surfaces, brass accents, sage technical indicators, parchment learning indicators, serif hero headings, responsive diagrams, visible focus, reduced-motion support and readable labels. Added a local SVG favicon.

## Verification

- All 15 active pages tested with headless Microsoft Edge at 1440 and 390 pixels: HTTP 200, one main and h1, visible navigation, no horizontal overflow.
- All 43 unique local link/asset URLs resolved; fragment targets checked. Includes relative paths from technical study subdirectories.
- No browser console/page errors after adding the favicon.
- Computed text contrast sampled across all pages, including inherited opacity and solid backgrounds: no failures at WCAG AA text thresholds. This is a targeted contrast check, not a complete accessibility certification.
- Skip links, semantic navigation, current-page indicators, focus styles and reduced-motion handling present. No duplicate IDs.
- Main content of all six technical case studies compared to the baseline: unchanged. Navigation, footer, skip link and favicon are the only HTML changes in those pages.
- `git diff --check` passes.
- Original `js/site.js` is empty and remains unchanged. Navigation and lifecycle views work without JavaScript or a backend.
- Desktop Home and mobile Leadership screenshots visually reviewed. Screenshots also captured for Learning and the PCAP case study at both sizes.
- Raw results: `browser-validation.json` and `contrast-validation.json`.

## Content provenance and remaining review

New leadership claims and metrics come from the supplied request. No new employer, title, date, certification, team size, budget amount or technology was added. Recovery details omit root cause, attribution, attacker methods, failed controls and sensitive architecture. The 170-hour figure is supporting context, not the accomplishment. No new quantified resilience or AI productivity outcome is asserted.

No factual clarification blocks this working copy. Before public release, review the time period behind “zero customer complaints” and the survey evidence, and confirm that the incident recovery wording is appropriate for public disclosure. The original portfolio’s factual claims were preserved, not independently verified. Existing project development-status labels were preserved; no unsupported status advancement was made.

## Preview in PowerShell

```powershell
& 'C:\Users\plarussa\.cache\codex-runtimes\codex-primary-runtime\dependencies\python\python.exe' -m http.server 8080 --bind 127.0.0.1 --directory 'C:\Scripts\Github\Infrastructure\portfolio-redesign'
```

Open http://127.0.0.1:8080/ . A preview server was started during validation.

Recommended commit: `Evolve portfolio around technology leadership and applied engineering`

Approved by the user on October 3, 2026 and finalized as a local Git commit. UTA Education and Black Hat Advanced Training appear in separate full-width Resume sections, verified at desktop and mobile widths. Nothing was pushed or deployed.

