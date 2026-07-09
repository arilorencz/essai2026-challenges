# Logo assets

Drop image files here with the exact filenames below. PNG (transparent background) or SVG both work; `.png` is what the HTML currently references — rename accordingly if you use SVG.

## Header (top of page)

| Filename            | Used for               | Rendered height |
| ------------------- | ---------------------- | --------------- |
| `essai-logo.png`    | ESSAI 2026 logo        | 64 px           |

To add more ESSAI/partner logos to the header strip, edit `challenges.html` and add another `<img>` inside `<div class="logo-strip">`.

## Footer (bottom of page)

| Filename       | Used for            | Rendered height |
| -------------- | ------------------- | --------------- |
| `tu-wien.png`  | TU Wien host logo   | 44 px           |

To add more sponsors, edit `challenges.html` and add another `<img>` inside `<div class="sponsor-strip">`.

## Notes

- Prefer transparent PNGs at 2x their rendered height (e.g. 128 px tall) or SVG for crispness on high-DPI screens.
- The `object-fit: contain` CSS keeps aspect ratio, so any reasonable dimensions will fit.
