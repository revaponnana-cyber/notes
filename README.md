# notes

A personal, plain-HTML notebook. No build step, no server, no framework.

- Each note is a **single, self-contained HTML file** in `notes/` — open it by double-clicking, no internet required.
- `index.html` is the contents page with search; open it to browse all notes.
- `templates/note-template.html` is the starter skeleton for new notes.

## Notes

- [The Jacobian — Quick Study Sheet (Handwritten)](notes/jacobian-quick.html) — short handwritten-style revision sheet: formulas with terms explained, important statements, formula → theory links.
- [The Jacobian Determinant — Change of Variables](notes/jacobian-determinant.html) — complete interactive study resource (derivations, worked problems, quizzes, exam prep) built from a YouTube transcript.

## Convention

- **New topic** → create a new file `notes/<topic-slug>.html` and add a card for it in `index.html`.
- **Existing topic** → edit that note file in place; update the `index.html` card only if the title or summary changed.
