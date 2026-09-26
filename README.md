# KAC KUPA

The public shopwindow for KAC KUPA: a personal, experimental crypto ecosystem being built from $0. This is a fully static Vite + React + TypeScript site. It contains presentation and placeholders only — no contracts, wallets, bots, backend, database or live blockchain integrations.

## Local development

```bash
npm install
npm run dev
```

Build the production site with `npm run build` and preview it with `npm run preview`.

## GitHub Pages

The included GitHub Actions workflow builds and deploys on pushes to `main`. Vite is configured with `/SIPP/` as its base path for `https://kackupa.github.io/SIPP/`. In repository settings, set Pages → Source to **GitHub Actions**.

## Editing content

All editable content is in `src/data.ts`: headline metrics, treasury values, products, Round Table agents, build log entries and principles. The UI lives in `src/main.tsx` and styling in `src/styles.css`.

Replace product placeholders by adding files to `public/assets/` with these names: `arb-launchpad.jpg`, `degen-karts.jpg`, `caesar-engine.jpg`, and `round-table.jpg`. Recommended dimensions are 1600×900 (16:9). The current visual placeholders remain intentional until real screenshots are added.

## Scope

This first version is only the public static shopwindow. Future contracts, launchpad functionality, arbitrage execution, treasury integrations, games, AI agents and social integrations are represented as planned products rather than implemented systems.
