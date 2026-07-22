# setup

Public host for the client-facing setup quizzes of the AI Setup Sprint. GitHub Pages serves these at `https://jdcondie.github.io/setup/`.

**These are the only client-facing files.** No operator docs, no secrets. The one external reference in each quiz is the intake Apps Script web app URL, which is deployed with "Anyone" access by design (write-only intake endpoint).

## The links you send clients

- **Get Set Up (the one post-signing quiz):** `https://jdcondie.github.io/setup/foundation-setup.html?client=Name`
- Bottleneck Triage (pre-audit lead magnet): `.../bottleneck-triage.html`
- Price Sheet Builder (when recipe 03 is in scope): `.../price-sheet-builder.html`
- Report Designer (when recipe 06 is in scope): `.../report-designer.html`

`client-setup-quiz.html` is a redirect tombstone so any old link still lands on Get Set Up.

## Source of truth + sync

These files are edited in the main hub at `~/Desktop/Ai Consulting Hub/00-launch/quizzes/`. This repo is a published copy. When a quiz changes there, copy the changed file here and push. (One CNAME file added here later swaps the URL to a real domain with no other change.)
