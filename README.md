# Duct Tape — landing page concepts

Three design directions for the landing page of an AI-readiness diagnostic built by
[Atom & Bits](https://www.linkedin.com/company/atom-bits-ai/). Each is a complete,
self-contained, responsive HTML page — no build step, no dependencies beyond a
webfont link.

**Live:** https://akmcgill.github.io/duct-tape-ui/

> **"Duct Tape" is a working code name.** This repository is an internal design
> exploration. Nothing here is final copy, final naming, or a launched product.

---

## The three concepts

| | Concept | Direction |
|---|---|---|
| **A** | [Atomic Age Playful](https://akmcgill.github.io/duct-tape-ui/01-atomic-age.html) | Built from the Atom & Bits style guide — cream and ink, Space Grotesk, orbit motif, warm and optimistic. The most on-brand of the three. |
| **B** | [Instrument Panel](https://akmcgill.github.io/duct-tape-ui/02-instrument-panel.html) | Derived from the diagnostic report design — dark, monospaced labels, hairline panels, with a sample readout in the hero. Serious and executive. |
| **C** | [Rugged & Scrappy](https://akmcgill.github.io/duct-tape-ui/03-rugged-scrappy.html) | The name taken literally — kraft paper, stencil headlines, torn tape strips, marker annotations. The most distinctive and the highest risk. |

All three carry the same content and the same core message: every operation runs on
some duct tape, and the useful question is where yours is load-bearing. They differ
only in visual register.

## Files

```
index.html                  cover page linking all three concepts
01-atomic-age.html          Concept A
02-instrument-panel.html    Concept B
03-rugged-scrappy.html      Concept C
```

## Viewing locally

Clone or download, then open `index.html` in any browser. Everything is inlined —
no server, no install, no build.

```bash
git clone https://github.com/akmcgill/duct-tape-ui.git
cd duct-tape-ui
open index.html
```

To check responsive behavior, narrow the window or use your browser's device
toolbar. Each page has breakpoints at 900px and 560px.

## Notes

- Styles are inline in each file by design, so any page can be opened, moved, or
  sent on its own without breaking.
- Fonts load from Google Fonts; the pages degrade to system sans-serif offline.
- These are references for a future Framer build, not production code.

## Status

Design pass 1 — August 2026. Concept not yet selected.

---

Karina McGill · Atom & Bits
