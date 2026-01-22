# CSV to JSON Converter

- Accepts raw CSV via the textarea in `index.html` and parses it with [Papa Parse](https://www.papaparse.com).
- Normalizes values so Dynamo-style attribute maps (`{"S": ...}`, `{"M": {...}}`, `{"N": ...}`, etc.) are unwrapped into plain JSON primitives and objects.
- Outputs formatted JSON with booleans/numbers preserved, keeping other structures intact so you can immediately copy-paste into downstream tooling.
- Served via Netlify—pushes to this repository automatically redeploy the live demo.
- Portfolio updates and contact details live on [jovylle.com](https://jovylle.com); you can link back to this repo under `mini-projects`.