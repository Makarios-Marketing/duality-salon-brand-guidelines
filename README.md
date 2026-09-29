# Duality Salon — Brand Guidelines

Brand guidelines for **Duality Salon**, 1606 Hopkins Road, Williamsville NY 14221.
Prepared by Makarios Marketing.

## Files

| File | What it is |
|---|---|
| `index.html` | The guidelines. Open in a browser, or print to PDF. |
| `Duality-Salon-Brand-Guidelines.pdf` | 15-page A4 PDF, generated from `index.html`. |

## Contents

1. The Idea · 2. Positioning · 3. Colour · 4. Typography · 5. Layout
6. Photography · 7. Voice · 8. The Team · 9. Assets

## Design system

Tokens and typefaces match the reference build.

| Token | Hex | Use |
|---|---|---|
| `--sand` | `#EFE8DE` | Page ground, close to the salon's wall colour |
| `--ivory` | `#F8F4EE` | Panels |
| `--line` | `#E3DACD` | Hairlines |
| `--brass` | `#8C6D43` | The one accent |
| `--brass-deep` | `#6F5433` | Brass at text size |
| `--brass-lt` | `#C9AF86` | Accent on dark only |
| `--ink` | `#161412` | Body text and dark bands |
| `--stone` | `#72695F` | Secondary text |

Display: **Cormorant Garamond** 300/400. Interface: **Jost** 200–500.

## Regenerating the PDF

```
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless --disable-gpu --virtual-time-budget=12000 \
  --print-to-pdf="Duality-Salon-Brand-Guidelines.pdf" --no-pdf-header-footer \
  "file://$PWD/index.html"
```

## Open items

- Logo vectors: a script wordmark and a round monogram both exist. Need SVG/AI/EPS.
- Darcy Ragione has no portrait yet.
- Marianna has both a colour and a black-and-white frame. Pick the colour one.
- Service-area towns in the build are placeholders.
- Price menu needs client sign-off.
- Brass on sand measures 3.9:1, so links and small labels need `--brass-deep`.
