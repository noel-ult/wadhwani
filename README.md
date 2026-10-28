# FairCredit AI concept page

A static landing page presenting a credit-assessment concept for gig workers and micro-entrepreneurs. The repository contains the marketing concept, not an implemented credit-scoring service.

## Preview

Open `index.html`, or run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Visit http://localhost:8000. No installation or build step is needed.

## Files and behavior

- `index.html`: publishable HTML page with inline CSS, problem/solution sections, benefits, and contact anchor.
- `Wadhwani.txt`: another copy of HTML source saved as a text file; browsers should enter through `index.html`.

The buttons have no application action handlers. Bank-data connection, AI analysis, credit profiles, and early-access collection are described concepts with no backing API or model in this repository. Edit `index.html` for the displayed site and keep the text copy synchronized only if it is still useful.

Manually check anchor links, text, buttons, and mobile layout after changes. No automated tests are present. Static hosting is sufficient for the current page.

## More documentation

- [Source, command, and configuration reference](docs/REFERENCE.md)
- [Contributing](CONTRIBUTING.md)

<!-- developer-handbook-20261028 -->
[Source reference](docs/REFERENCE.md) · [Verification and operations](docs/OPERATIONS.md)
<!-- /developer-handbook-20261028 -->
