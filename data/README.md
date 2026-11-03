# Data

`adae.csv` is the ADaM adverse events dataset (ADAE) from the
[`pharmaverseadam`](https://pharmaverse.github.io/pharmaverseadam/) R package,
which is built from the CDISC pilot study. It is **synthetic example data**:
no real patients.

`export_adae.R` recreates it (run from the repository root, with `dplyr` and
`pharmaverseadam` installed):

```r
source("data/export_adae.R")
```

`pharmaverseadam` is licensed under Apache 2.0.
