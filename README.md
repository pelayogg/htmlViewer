# HTML Viewer

A modern, real-time HTML editor and previewer — zero backend, pure static HTML.

## Features

- **Live preview** — HTML renders instantly in a sandboxed iframe as you type
- **Auto-run / Manual** — toggle automatic rendering or trigger manually with Run / `Ctrl+Enter`
- **Syntax highlighting** — full CodeMirror editor with HTML mixed mode (HTML + CSS + JS)
- **Code folding** — collapse HTML tags, CSS blocks, and JS functions
- **Auto-close** — tags and brackets close automatically
- **Tag matching** — highlights matching open/close tags
- **Format / Beautify** — prettify HTML with js-beautify (`Ctrl+Shift+F`)
- **Console capture** — `console.log`, `warn`, `error` from the preview are captured and shown in an integrated console panel
- **Device simulation** — preview in Desktop, Tablet (768px), or Mobile (375px) frames
- **Layout modes** — side-by-side or stacked layout
- **Import / Download** — import HTML files (click or drag & drop), download your work
- **Open in new tab** — launch the preview in a separate browser tab
- **Word wrap toggle** — switch line wrapping on/off
- **Stats** — file size, line count, and cursor position in the status bar

## Usage

### GitHub Pages

Enable GitHub Pages (Settings → Pages → Source: `main` / root) and visit:

```
https://pelayogg.github.io/htmlViewer/
```

### Local

Open `index.html` in any browser — no build step, no dependencies to install.

## Tech Stack

- [CodeMirror 5](https://codemirror.net/5/) — editor with HTML mixed mode, folding, tag matching (CDN)
- [js-beautify](https://github.com/beautifier/js-beautify) — HTML formatting (CDN)
- Vanilla JavaScript — zero frameworks
