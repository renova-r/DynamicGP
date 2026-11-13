# DynamicGP 1.1.9.9001

Renova release, based on CRAN DynamicGP 1.1-9 (archived on CRAN 2024-11-11).

- `R/gpsepms.r`: `predict.gpsepms` and `predict.gpseplmms` now take `(object, ...)` and read the test inputs from the first extra argument, matching the `predict()` generic; the computation is unchanged.
- `DESCRIPTION`: the arXiv reference `<arXiv:1611.09488>` in `Description` is written as `<doi:10.48550/arXiv.1611.09488>`, and the stale optional `Date: 2022-11-07` field was removed (metadata only).
- `DESCRIPTION`: `Version` set to `1.1.9.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was added and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
