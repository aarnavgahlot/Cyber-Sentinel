# Cyber-Sentinel

CYBER/SENTINEL is a frontend-only cybersecurity intelligence demo built with React, TypeScript, Vite, and deterministic synthetic data.

## Run locally

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
npm run preview
```

## Demo boundaries

- All assets, incidents, indicators, timelines, scores, and graph relationships are synthetic examples.
- The URL scanner evaluates the entered text with local deterministic rules. It does not resolve, fetch, or open URLs and does not query external reputation services.
- TinyFish is shown as a future integration point. No live research, API credentials, or external responses are present in this demo.
- Incident actions, settings, notes, and scenario selections only change frontend state for the current session. Use **Reset Demo** to restore the starter data.
