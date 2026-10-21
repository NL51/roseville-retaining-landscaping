# Retaining Walls & Landscaping | Roseville

Live website: https://roseville-retaining-landscaping.roundprawn256.chatgpt.site

## Source and hosting

The complete buildless website is in `dist/`. Deploy that folder to any static host. For local preview, run `python3 -m http.server 8000 --directory dist`.

`dist/index.html` contains page content, responsive styles, structured business data, and the SMS inquiry interaction. `dist/assets/garden.webp` is the generated landscape image, labeled as inspiration on the website.

## Contact behavior

Call links use (916) 728-8990. The project form prepares an SMS in the visitor's messaging app; the visitor must send it. No server stores inquiries. Facebook and Google Maps links point to the business listings.

## Handoff

No dependencies or build are required. Copy `dist/` to the chosen host and configure the purchased domain there. Update absolute Open Graph URLs when changing domains. `.openai/hosting.json` records the existing Sites identity; do not reuse that project ID for a different client.

## Synchronization

This repository contains the published source snapshot. GitHub pushes do not automatically deploy to Sites; republish through Sites after future edits, or configure separate hosting from this repository.
