# EnergyAgent (yourenergyagent.com)

The landing page for **EnergyAgent** — the umbrella brand for an energy SaaS that deploys AI agents to watch, verify, and value renewable energy. It presents two doors: **NEPOOL Verifiers** for stamping agents and solar operators (automated NEPOOL-GIS reporting, utility-portal auto-capture, pixel-perfect workbooks), and **Array Owners** for people who own arrays (connect an inverter, see live ground-truth generation, and watch the array's value tick up in real time). The page is a single, dependency-free static page (vanilla HTML/CSS, system-ui fonts, a few lines of inline JS for entrance animations) — no build step, fully responsive, and respects `prefers-reduced-motion`. EnergyAgent is a Dyson Swarm Technologies product.

## Deploy (Netlify)

No build is required — this is a static site. Either drag-and-drop the project folder onto the [Netlify](https://app.netlify.com/drop) dashboard, or connect the repo and set **Build command:** _(empty)_ and **Publish directory:** `.` (the repo root). The `_redirects` file is an empty placeholder for any future Netlify redirect rules. To preview locally, just open `index.html` in a browser (or run `python3 -m http.server` and visit `localhost:8000`).
