# chifumi-site (build output)

Static build of the new Chifumi website by GRAPHIQ Studio, published here only so Fregio can fetch it.
Source lives in a private repo. Do not edit these files by hand.

Serving notes:
- `/` -> `index.html`; `/murals`, `/collaborations`, `/augmented-reality`, `/shop`, `/about` -> `<page>/index.html`
- `rive/rive.wasm` must be served as `application/wasm`
- Pages carry `noindex` while the client reviews; `robots.txt` disallows crawling.
