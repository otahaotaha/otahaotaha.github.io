# NOTES — design decisions and changelog

## Design decisions (2026-10-29, first build)
- **Idea:** the site reads like a well-organized internal report. Every page opens with a memo header (Prepared by / Subject / Date), the summary comes first, and evidence sits in real tables with aligned numbers. This came from Omar's brief: "closer to a well-organized report than a creative portfolio."
- **The one live thing:** the Messy → Usable switch on Home. The same five demo rows shown as a raw export and as the validated version. CSS-only (two radio inputs and `:checked`). It demonstrates the headline instead of restating it.
- **Palette:** ink `#1b2432` (charcoal-navy), ground white, accent `#2a7f79` (muted teal; `#1f5f5a` when used as text on white, for contrast), surface `#f3f5f7`, muted `#5b6673`, signal `#b4532a` used only to mark problems in the messy table.
- **Type:** Source Serif 4 for headings, Public Sans for text and tables. Five sizes: 14 / 17 / 22 / 32 / 48. Tabular figures everywhere.
- **Corners:** square, on purpose. It is a document, not an app.
- **Motion:** none. Playfulness level 1. Only focus rings and link hover.
- **Privacy:** no phone, hometown, GPA, Dean's List or transcript, per Omar's rule. Email and LinkedIn from his résumé. GitHub unknown, left as a placeholder.
- **Pages:** five (Home, About, Projects, Résumé, Contact), per the course handout, although the brief said three to start. About and Résumé split so they do not repeat: About holds who/what/education/certs/skills, Résumé holds the dated experience and projects table.
- **Not used (anti-slop):** centered hero, icon cards, skill pills, eyebrow labels, gradients, hover-lift, Inter.

## Changelog
- **2026-10-29** First build: eight files. Checked in the browser pane at 375, ~760 and 1440 px with zero console errors. Two fixes during the check: the radio inputs had to sit directly in the fieldset for the `:checked ~` selector to reach the tables; and grid items needed `min-width: 0` so the demo table could not push the Home column past a phone viewport.

## Next
- Add `photo.jpg` and `resume.pdf` (with QR code once the site has a live URL).
- Omar writes the 150–250 word project summary.
- Report, slides and chart links as milestones land (M4 Nov 12, M5 Nov 19, M6 Dec 3).
- Decide on GitHub link; decide whether Dean's List goes back on.
- Publish to GitHub Pages only on Omar's explicit go-ahead.
