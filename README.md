# World Bank Publications — Download Dashboard

A live, self-updating dashboard of download statistics for Ezequiel Molina's
World Bank publications (Latin America & the Caribbean portfolio), aggregated
across both World Bank repositories:

- **Documents & Reports** — documentos.bancomundial.org
- **Open Knowledge Repository** — openknowledge.worldbank.org

It shows total downloads, per-publication and per-language breakdowns, and
**reader geography** (downloads by country and region, via the Documents &
Reports country API).

👉 **Live dashboard:** https://ezequielmolina-lang.github.io/wb-downloads-dashboard/

## How it updates

The figures are collected by a small local pipeline (headless Chromium + the
repositories' public APIs) and published here. It refreshes **every 2 months**
via a scheduled task; `index.html` is regenerated and pushed automatically.

_Last data: see the date on the dashboard. Numbers are read live from the World Bank repositories._
