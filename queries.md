# Named queries — 2026-10-19

Prior-art scope before any candidate: Notion data source `collection://382d9c24-c10c-4fbf-9628-c7be3a1e4007` through CLOSED-2026-10-18, and `sENZ5hFx` repositories through `walker-pdf-bytes-missing-2026-10-18`. Kind-Overshoot was still queued. No 2026-10-19 repository existed at the start.

## Retrieval attempts

1. Unpaywall `https://api.unpaywall.org/v2/10.1029/2024GB008329?email=heyhaleybird@gmail.com` — sole OA PDF is `https://onlinelibrary.wiley.com/doi/pdfdirect/10.1029/2024GB008329`.
2. `https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2024GB008329` — HTTP 403, cf-mitigated challenge, 2026-10-19T17:42:10Z.
3. `https://agupubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1029/2024GB008329?download=true` — HTTP 403, same minute.
4. `https://doi.org/10.1029/2024GB008329` with `Accept: application/pdf` — 302 to Wiley, then 403, 2026-10-19T17:42:59Z.
5. Europe PMC search `DOI:10.1029/2024GB008329` — 0 hits.
6. Crossref preprint `10.22541/essoar.172434585.50661378/v1` — PDF URL `https://essopenarchive.org/doi/pdf/10.22541/essoar.172434585.50661378/v1` — HTTP 403, 2026-10-19T17:43:15Z.
7. GitHub user `steviewalker` — repository `CMIP6_POC_flux_comparison`, tree `b32dddf4b87d7da6cee37897df6b305ec4c748a0`, 65 blobs, no PDF, no CSV.
8. GitHub code search `"Table S2" OR "Pg C" repo:steviewalker/CMIP6_POC_flux_comparison` — 0 hits.

## Not scored

- Any search-index excerpt of the Wiley or ResearchGate HTML. An excerpt is not the file.
- Wang and Fennel 2024. Already used up on 2026-10-18.
- Doney et al. 2024 Table 5. Already used up on 2026-10-15.
- Friedlingstein Global Carbon Budget residual 1.7. Inherited, not re-measured.
