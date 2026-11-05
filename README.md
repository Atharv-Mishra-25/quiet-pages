# Quiet Pages

A distraction-free PDF reader that feels like reading a real book.

- Realistic page turning: click or swipe a page edge, or drag a corner to peel it slowly
- Synthesised page-turn sound (can be switched off)
- Bookmarks with a ribbon on the page and a list with text previews
- Highlighter in four colours that snaps to the words you drag across, with a list of every highlight
- The PDF's own table of contents in a side drawer
- White, Sepia and Night paper
- Controls hide until you move to the top or bottom edge
- Two-page spread on wide screens, single page on phones
- Your shelf remembers every book and the page you stopped on

Your PDFs never leave your device. They are stored in the browser's IndexedDB.

## Run it

It's a single `index.html` with no build step. Open it in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then go to http://localhost:8000.

## Keyboard

| Key | Action |
| --- | --- |
| `←` `→` / Space | Turn pages |
| `B` | Bookmark the current page |
| `H` | Highlighter on/off |
| `T` | Contents |
| `F` | Full screen |
| `Home` / `End` | First / last page |

## Built with

- [PDF.js](https://mozilla.github.io/pdf.js/) for rendering pages
- [StPageFlip](https://github.com/Nodlik/StPageFlip) for the page-turn effect
