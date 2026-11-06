# TruthLens AI

A browser-based evidence organization prototype for misinformation investigations.

## Run locally
Open `index.html` in a modern browser. No installation or API key is required.

## Features
- Dashboard and navigation
- Claim submission and web-search shortcuts
- Manual supporting and contradicting source collection
- Human-selected provisional verdict and reasoning
- Local browser investigation history
- Search/filter history
- Printable report (choose Save as PDF in the print dialog)

## Important limitation
This version does not automatically verify claims or use an AI model. It opens public search tools and lets the investigator review original sources and record findings. It intentionally does not invent citations or claim automated fact-checking. For production use, connect a trusted search API and AI service through a secure backend, then validate all source URLs and excerpts.

## Data storage
Investigations are saved in the browser's localStorage on the device/browser where the site is used. Clearing browser storage will remove them.
