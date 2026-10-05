# TypewriterLM poster

This directory contains the A0 portrait (841 mm x 1189 mm) poster for *A Language Model from
1913: Pretraining on Historical Text*. Its LaTeX structure, Palatino typeface,
colors, rounded headers, six-column grid, and font scale follow
`../poster-example/poster.tex`.

## Build

Run from this directory:

```bash
pdflatex poster.tex
pdflatex poster.tex
```

The poster uses a local copy of `baposter.cls` and local figure copies. The
source paper and example poster remain unchanged.

## Replace placeholders

- Replace `uw.png`, `vector.png`, and `conference.png` in `figures/` with the
  final university and conference logo set, then update the title block if
  the aspect ratios change.
- Replace the QR-code placeholder in the Resources box with the final QR code.
- Keep replacement assets in `figures/` so the poster remains portable.
