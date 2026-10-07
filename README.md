# Cláusulas adverbiales

Practice site for Spanish adverbial clauses (time, purpose, condition and contingency, cause, concession) and the choice between indicative and subjunctive. Students read a short explanation (English), then write directly on the page (Spanish), self-check, and keep their work as a PDF.

Content is adapted from *Spanish for a Sustainable World II* — [Cláusulas adverbiales](https://louis.pressbooks.pub/sustainablespanish/chapter/clausulas-adverbiales/), © Liliana Naranjo, CC BY 4.0. The exercises are new.

## Pages

| File | Topic |
|---|---|
| `index.html` | Landing page and how to use the site |
| `01-temporales.html` | cuando, hasta que, después de que, tan pronto como, en cuanto, antes de que |
| `02-finalidad.html` | para que, a fin de que, con el propósito de que (and para + infinitive) |
| `03-condicion-y-contingencia.html` | si, a menos que, con tal (de) que, siempre y cuando, en caso de que, sin que |
| `04-causales-y-concesivas.html` | porque, ya que, dado que, como · aunque, a pesar de que, por mucho que |
| `05-proyecto.html` | Writing project (ideas for your city) and cultural research planner |
| `06-repaso-y-referencia.html` | One-page reference table, mixed review, grammar journal |
| `assets/style.css`, `assets/app.js` | Shared styles and the save / print / check script |

## What students can do on every page

- **Write on the page.** Answers autosave in the browser on that device (`localStorage`). Nothing is sent to a server.
- **Imprimir / Guardar en PDF.** Opens the print dialog; choose "Save as PDF". Typed answers are included.
- **Descargar mis respuestas.** Saves a `.txt` copy.
- **Revisar mis respuestas.** Checks fill-in blanks and drop-downs (accent-only mistakes are flagged separately). Open writing has a collapsible model answer.
- **Borrar todo.** Clears the page after a confirmation.

## Publish with GitHub Pages

1. On GitHub, create a new public repository named `clausulas-adverbiales`.
2. Upload everything in this folder (keep the `assets/` folder), or push it with git.
3. In the repository: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save**.
4. After a minute the site is at `https://<username>.github.io/clausulas-adverbiales/`.

To preview locally, open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit `http://localhost:8000`.

## Editing

Each page is plain HTML. Fill-in blanks are `<input class="f blank" data-a="answer|alternative">`; drop-downs are `<select class="f" data-a="correct option">`; open writing is `<textarea class="f">`. Keep the `f` class on anything students should be able to save, and keep each page's `data-page` value unique.

## License

CC BY 4.0 — see `LICENSE.md`.
