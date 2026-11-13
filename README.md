# DynamicGP

Emulation of large-scale dynamic computer experiments with localized Gaussian process models, and solution of inverse problems for them.

Compatibility updates by Renova.

Version 1.1.9.9001 changes the `predict` methods for `gpsepms` and `gpseplmms` objects to the `predict(object, ...)` form required of S3 methods (the computation is unchanged), writes the arXiv reference in `DESCRIPTION` as a DOI, and removes the stale optional `Date` field.

## Install

```r
install.packages("DynamicGP", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/DynamicGP@renova-1.1.9.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

DynamicGP is by Ru Zhang (maintainer), Chunfang Devon Lin and Pritam Ranjan, with contributions from the authors of bundled code listed in `inst/COPYRIGHTS` (Robert B Gramacy, Nicolas Devillard, the L-BFGS-B authors, Berend Hasselman and the BLAS authors); the original CRAN package is at <https://CRAN.R-project.org/package=DynamicGP>. License: GPL (>= 2); see [COPYING](COPYING).
