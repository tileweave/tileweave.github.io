# TileWeave project website

Paper introduction, method diagram, interactive experimental results, and supporting materials for *TileWeave: Programming Across Abstraction Levels for Coding Agents on Accelerator Kernels*.

The site is static HTML, CSS, and JavaScript and can be served directly by GitHub Pages from `main` at the repository root. No build step is required.

## Local preview

```sh
python3 -m http.server 8765
```

Open `http://localhost:8765/`. Serving the site over HTTP enables the interactive result data to load.

## Contents

- `index.html`: introduction, workflow, results, case studies, reading guide, and downloads.
- `assets/`: responsive styling, browser interactions, and the explanatory workflow diagram.
- `data/results.json`: aggregate results, workload summaries, and search-progress coordinates derived from the supplied CSV files.
- `downloads/TileWeave.pdf`: supplied anonymous manuscript.
- `downloads/tileweave-materials.zip`: original source, experiment data, and case records.
- Other downloads provide individual material bundles, key CSV files, and documentation.

The original figures, numerical records, and PDF are retained unchanged. The website's explanatory workflow is an overview of the method, with a link to Figure 2 in the paper. Source and materials retain their existing notices and dependency terms.

## Reporting notes

Figure 4 uses the MinGPT case's own reference latency; Figure 5 uses the reference shared with its three baseline trajectories. The difference between the candidate's 3.831 ms search evaluation and 4.138 ms final verification is a roughly 8% remeasurement change, independent of reference normalization. The reading guide explains these conventions, the main-table endpoint definition, uncertainty, and platform timing boundaries.

The supplied manuscript is anonymous. No publication status or accepted venue is asserted on this site.

## Supplemental verification and search notes

Measured final-verification values accompany the original endpoints in the result data. The webpage includes a separate sensitivity-analysis table; existing confidence intervals continue to describe the original endpoints only. The supplementary notes document the unchanged MinGPT iter-58 repeat, the shared High-only/High-to-Low trajectory and autonomous stopping, and the coverage limits of the retained records.
