# Urban Heat Mitigation Dashboard

An interactive single-page web project for exploring urban heat mitigation strategies, microclimate sensing, and edge-actuated cooling. The page combines research framing with an operational concept for a low-cost urban microclimate station.

## Overview

This project is a self-contained HTML experience built around one file, `code.html`. It presents:

- a benchmarking section for existing urban sensing initiatives
- a hardware blueprint and bill of materials for a micro-station
- an interactive misting control simulator
- a four-phase deployment roadmap for city-scale rollout

The interface uses Tailwind CSS for layout and styling, and Chart.js for the embedded visualizations.

## Features

- Responsive single-page layout with sticky navigation
- Project comparison bar chart
- Budget breakdown doughnut chart
- Auto-generated bill of materials table
- Interactive temperature and humidity control simulator
- Deployment roadmap with a step-by-step implementation flow

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Chart.js via CDN
- Vanilla JavaScript
- Google Fonts

## How To Run

No build step is required.

1. Open `code.html` directly in your browser, or
2. Serve the folder with a local web server if you prefer a cleaner development workflow.

Example using Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/code.html` in your browser.

## Project Structure

```text
Rising_heatsress/
├── code.html
└── README.md
```

## Notes

- The charts and simulator depend on network access because Tailwind, Chart.js, and Google Fonts are loaded from CDNs.
- The project is designed as a presentation and research prototype, not as a production deployment package.

## Suggested Next Step

If you want, you can rename `code.html` to `index.html` so the site opens automatically when hosted on GitHub Pages.