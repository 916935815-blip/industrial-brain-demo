# Industrial Brain — Landing & Interactive Demo

Public landing page and interactive scenario demo for **Industrial Brain — Based on Data Ontology & Multi-Agent Collaboration**.

- Live: https://916935815-blip.github.io/industrial-brain-demo/
- Static site, no dependencies, no backend, no API keys.
- All names, numbers and events in the demo are **simulated and desensitized**.

## Pages

| Path | Purpose |
|---|---|
| `index.html` | Landing page (hero, agents, scenarios, video, screenshots, FAQ, contact) |
| `demo.html` | Interactive workbench demo — 6 end-to-end factory scenarios |
| `assets/` | Screenshots, logos, favicon, social preview (og.png), demo video + poster |

## Demo URL parameters

The interactive demo (`demo.html`) accepts optional parameters:

| Parameter | Effect |
|---|---|
| `?sc=N` | Jump straight to scenario N (1–6) |
| `&auto=1` | Auto-play the scenario flow |
| `&noanim=1` | Disable UI animations (useful for screen recording) |

Example: `demo.html?sc=4&auto=1`

## Updating the site

Upload `index.html`, `demo.html` and the `assets/` folder to the repository root (branch `main`, served by GitHub Pages). Keep file names unchanged so links stay valid.
