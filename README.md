# clustering-legislative-data-r

R problem set on unsupervised clustering algorithms, including manual k-means derivation and application to real legislative data.

## Topics covered

**Part 1 — K-means by hand**
Manual k-means on a 6-observation simulated dataset, tracing centroid initialization, assignment, and update steps.

**Part 2 — Clustering U.S. state legislatures**
Applied to the Bowen & Greene state legislative professionalism dataset (50 states, 1974-2010). Variables: legislative session length, legislator salary, and staff/expenditures per legislator.

- K-means clustering (optimal k selected by within-sum-of-squares and silhouette width)
- Agglomerative hierarchical clustering (complete, single, average linkage)
- Gaussian Mixture Models via the EM algorithm

## Data

**Bowen & Greene Legislative Professionalism Dataset** (`legprof-components.v1.0.RData`)

Measures of legislative capacity across U.S. states spanning 1974-2010. Codebook included.

## Files

- `battishapset4.Rmd` — full R solution
- `battishapset4.pdf` — rendered output
- `Data and Codebook/` — dataset and codebook PDF

## Requirements

R with packages: `tidyverse`, `ggplot2`, `mclust`, `cluster`, `factoextra`
