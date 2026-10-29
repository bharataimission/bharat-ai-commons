Bharat AI Commons live-catalogue portal

The webpage fetches public CSV files from the main branch of https://github.com/bharataimission/bharat-ai-commons at runtime. Current configured paths: datasets/catalog.csv, models/catalog.csv, benchmarks/catalog.csv, tools/catalog.csv, language-resources/catalog.csv. Missing optional catalogues are skipped.

For GitHub Pages, keep index.html and assets/ together in the same published directory. If the portal is hosted under dashboard/, place this index.html and assets/ in dashboard/.

The state map only shows state-level counts when records contain a state, states, or state_coverage column. Existing catalogues may not yet contain this field, so the map may be grey until documented geographic coverage is added. This is intentional and avoids inventing state-level coverage.

Branding update: header and footer now lead with Bharat AI Mission, followed by bold Bharat AI Commons. Keep the assets folder beside index.html.
