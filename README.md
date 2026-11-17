# Search Sprint

A responsive higher-or-lower game about estimated monthly Google searches. Every keyword is one or two words. Each correct answer raises the difficulty: the search-volume gap narrows, and the pool shifts toward more specific terms. Your best streak is saved in your browser.

## Play

https://epidemikgg.github.io/search-up-or-down/

## Images and search volume data

Cards request lead thumbnails from the English Wikipedia REST page-summary API when a keyword appears. Each visible photo links to its matching Wikipedia article; cards use the default design when no thumbnail is available. The game includes hand-curated, illustrative global monthly search-volume estimates for gameplay. These are not verified Google Ads figures or live data. For authoritative monthly search-volume ranges, export keyword data from Google Ads Keyword Planner and replace the in-page dataset in index.html.

## Run locally

Open index.html in a modern browser. No build step or server is required. Internet access is needed for Wikipedia thumbnails.

## Publish

GitHub Pages serves the main branch from the repository root.
