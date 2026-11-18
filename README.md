# Mercio — AI Business Advisor

A standalone multilingual concept website and interactive product prototype for an AI-powered business advisor designed for independent retailers.

## Features
- Responsive SaaS-style landing page and interactive dashboard
- Business overview: revenue, gross margin, stock and waste indicators
- Inventory search with stock status and suggested actions
- Category performance insights and sustainability indicators
- Scenario-based conversational assistant
- English, French, Spanish and Portuguese interface
- No build step or external dependencies

## Run locally
Open `index.html` in a browser, or run `python -m http.server 8000` and visit `http://localhost:8000`.

## Publish with GitHub Pages
In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then save. The site will be published at `https://zakaryaslm.github.io/Mercio/` once deployment completes.

## Important product disclaimer
This is an early-stage concept prototype. All store names, metrics, inventory levels and sustainability indicators are illustrative. The assistant uses predefined scenarios; it is **not connected to a live LLM, point-of-sale system, accounting platform or real store data**. Do not use it to make actual purchasing, financial or operational decisions.

## Suggested next milestones
1. Interview independent retailers and validate their highest-value decisions.
2. Define a data model for sales, products, purchases and inventory.
3. Import CSV exports and implement auditable KPI calculations.
4. Add secure authentication, backend services and tenant-level data isolation.
5. Integrate a language model with controlled tools grounded in calculated metrics.
6. Pilot with retailers and measure decision quality and business impact.

## Technology
HTML5 · CSS3 · Vanilla JavaScript
