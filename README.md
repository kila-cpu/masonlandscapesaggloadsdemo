# Mason Landscapes — Agg Loads Demo

Interactive prototype of the Agg Loads aggregate & quarry docket app, built from
the wireframes with a yellow theme. A single self-contained `index.html` served by
a tiny zero-dependency Node server.

## Run locally

```bash
npm start
```

Then open http://localhost:3000

## Deploy on Railway

Railway auto-detects the Node app via `package.json`:

- **Build:** none required (no dependencies)
- **Start command:** `npm start`
- The server binds to `process.env.PORT`, which Railway sets automatically.

Push to this repo's `main` branch and Railway will build and deploy.
Health check available at `/healthz`.
