# Logo assets

Logos referenced by `challenges.html`. Sourced from the ESSAI 2026 site (https://essai2026.eu/organization.php).

## Header (top of page) — 64 px

| File               | Used for            |
| ------------------ | ------------------- |
| `essai-logo.png`   | ESSAI 2026 event logo |

## Footer sponsors — 44 px

| File                          | Sponsor / Partner              |
| ----------------------------- | ------------------------------ |
| `eurai.svg`                   | EurAI                          |
| `tu-wien.png`                 | TU Wien                        |
| `wu-wien.svg`                 | WU Wien                        |
| `aij.jpg`                     | AI Journal                     |
| `bilateral-ai.png`            | Bilateral AI                   |
| `asai.png`                    | ASAI                           |
| `erste-bank.png`              | Erste Bank                     |
| `graphwise.svg`               | Graphwise                      |
| `city-of-vienna.svg`          | City of Vienna                 |
| `hostel-ruthensteiner.png`    | Hostel Ruthensteiner           |
| `secai.png`                   | SECAI                          |
| `mdv.jpg`                     | Meeting Destination Vienna     |
| `fwf.svg`                     | Austrian Science Fund (FWF)    |

## Adding / removing logos

Edit `challenges.html` — add or remove `<img>` tags inside `<div class="sponsors-logos">` (footer) or `<div class="logo-strip">` (header). CSS keeps every image at a consistent height with `object-fit: contain`, so any reasonable dimensions will fit.
