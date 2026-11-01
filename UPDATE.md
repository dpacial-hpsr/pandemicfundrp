# Resilient Philippines Baseline page: update procedure

This file governs every update to `index.html`, whether from the weekly Friday run or an on-request update.

## What the page is
- Public page: https://dpacial-hpsr.github.io/pandemicfundrp/
- `index.html` at the root of `main` is the whole site. GitHub Pages publishes it.
- Prepared by the Epidemiology Bureau and the Resilient Philippines Project Management Office.
- Purpose: a baseline reference on plans, progress and budget for the Pandemic Fund Resilient Philippines (RP) Project. It states what the documents say. It makes no recommendations.

## Sources (Google Drive)
- Project folder "Pandemic Fund Resilient Philippines": `1v1OJaqeHWseHYoPv4hLiuF_WJr5Lzk6y`
  - Meeting Minutes: `1FW9XhvUB05cFx2_vY1CIX3V4gZU_HXgT`
  - References: `1r89jrYx0QnsLC6Axr-xvc2OTmbHN0cMW`
  - TORs: `1nSZynW-r1ohHn2K2HjC7YT_1ByoNXpGO`
  - World Bank Comments: `1XRZv2PzJM1r8BZrcSnLusy_yHlq0xlJs`
- Shortcut targets that change often (check their modified time directly):
  - AWFP 2027 (WB submission): `1Rq6y1PpLVG4Nq0l8wWMtWvyN7Z9zkDaiQp6wyZ94JrM`
  - C. Procurement Plan & Document Tracker: `1VovyhZfNPX1I7LrWEgCbV63xuonEnuErZwzGNu1J8Cw`
  - Joint Memorandum Circular v4: `1T99E0F1X84O2d4KSZ6N4nT6_6GjNAXvWIDoaOm3Tj9c`
  - Draft concept note, project launch: `1G4BjvLFnfSQAB45T9kE6-crIG0LNCNqjLhZr2M8bXhM`
- New shortcuts in the folders point to other files. Resolve each by searching its title and read the target.

## Steps
1. Read `index.html`. The compile date in the masthead "as of" line and the footer marks the last update.
2. List every file in the project folder and its subfolders, plus the shortcut targets above, modified after the last update.
3. If nothing changed, stop and report "No changes since <date>".
4. If something changed, read each changed or new document. Update only the figures, rows and sections it affects. Keep the page structure, section order, styling and colour tokens unchanged.
5. Recompute every total, share and count in code. Never estimate figures in prose.
6. Add any new disagreement between documents to section 11, "Check before quoting". Remove an item only when a document resolves it.
7. Update the "as of" line, the compile date and the footer date.
8. Render the page once at 1280 px and 390 px, light and dark, and confirm there is no horizontal page scroll.

## Rules
- Formal register, active voice, one idea per sentence. Conclusions first.
- No recommendations. State what the documents say.
- Label each section's basis: Documented, Derived, or To confirm. Cite the source document under each block.
- Name officials only by position and surname as written in an official document, and flag designations that conflict.
- Do not add individual salaries or personal contact details.
- Keep `<meta name="robots" content="noindex, nofollow">` in the head.
- Palette: purple `#A320E0` and yellow `#FBD301` as primaries. Fonts: Literata for headings, Atkinson Hyperlegible for body text.
- Never push to `main`, never merge, and never change repository settings.

## Delivery
- Commit `index.html` to a new branch named `update-YYYY-MM-DD` and open a pull request against `main`.
- The pull request body lists what changed, the source of each change, and new items to check.
- The repository owner reviews and merges. GitHub Pages then updates the live page.
