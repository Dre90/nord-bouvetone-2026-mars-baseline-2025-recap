# Baseline 2025 – Web Platform Recap

A [Reveal.js](https://revealjs.com/) presentation covering the web platform features that became part of [Baseline](https://web.dev/baseline) in 2025. Created for **Nord Bouvet One**, March 2026.

## Topics Covered

- **CSS** – `@scope`, `content-visibility`, `scrollbar-color`, `sign()`, `abs()`, single-stop gradients
- **View Transitions** – View Transition API, `view-transition-class`, same-document transitions
- **HTML** – Popover API, `contenteditable="plaintext-only"`, `<link rel="dns-prefetch">`
- **Performance** – Largest Contentful Paint (LCP), Event Timing / INP, `scrollend`
- **DOM & Interaction** – Invoker Commands, `dialog.requestClose()`, `caretPositionFromPoint()`
- **Data & Parsing** – JSON import attributes, URLPattern, `Uint8Array` base64/hex
- **JavaScript** – Iterator helpers, `Promise.try()`, `RegExp.escape()`, `Float16Array`
- **Web APIs** – `ClipboardItem.supports()`, Screen Wake Lock, `Intl.DurationFormat`

## Getting Started

```bash
npm install
npm start
```

Open [http://localhost:3000/reveal.js/](http://localhost:3000/reveal.js/) in your browser.

### Speaker Notes

Press **S** during the presentation to open the speaker view with notes, a timer, and slide previews.

## GitHub Pages

The presentation can be hosted on GitHub Pages:

1. Go to **Settings → Pages**
2. Set source to **Deploy from a branch** → `main` / `/ (root)`
3. Access at `https://<username>.github.io/nord-bouvetone-2026-mars-baseline-2025-recap/reveal.js/`

## Sources

- [web.dev/baseline/2025](https://web.dev/baseline/2025)
- [Baseline Newly Available series](https://web.dev/series/baseline-newly-available)
- [MDN Web Docs](https://developer.mozilla.org/)

See [REFERENCES.md](REFERENCES.md) for a complete list of per-feature source links.
