# Steps used in the fragment bias simulation

* `simulate_tx.R`
* `simulate_make_data.R`
* `simulate_shuffle.R`

The first one is quick, the second two take ~1 hour each.
`simulate_make_data.R` requires ~12 Gb and `simulate_shuffle.R`
requires ~ 2 Gb. You can run with:

```
R CMD BATCH --no-save filename.R
```
