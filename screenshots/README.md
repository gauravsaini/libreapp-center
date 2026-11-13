# PR screenshots (widget-test renders)

Renders captured 2026-11-13 with Flutter 3.47.6 widget tests
(`RenderRepaintBoundary.toImage()`, pixelRatio 2.0) of the real widgets.
They are NOT full desktop screenshots.

- `2051-error-before.png` — About page, contributors provider throwing,
  upstream main `ed230d50` (heading + raw exception text visible).
- `2051-error-after.png` — same error state, PR 2051 branch
  `fix/socket-exception-error-ui-2020` at `e96a1516` (whole contributors
  section gone).
- `2051-success.png` — contributors loaded, same PR branch/HEAD
  (title + avatar wrap visible).

No PR 2062 images: the sidebar focus-ring render could not be produced
faithfully headless (see the wave evidence file, lanes/screenshots).
