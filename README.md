# notes

A personal, plain-HTML notebook. No build step, no server, no framework.

- Each note is a **single, self-contained HTML file** in `notes/` — open it by double-clicking, no internet required.
- `index.html` is the contents page with search; open it to browse all notes.
- `templates/note-template.html` is the starter skeleton for new notes.

## Convention

- **New topic** → create a new file `notes/<topic-slug>.html` and add a card for it in `index.html`.
- **Existing topic** → edit that note file in place; update the `index.html` card only if the title or summary changed.
