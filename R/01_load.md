## Loading data


``` r
data_raw <- read.csv("~/projects/project_r4bd/Data/risk_factors_cervical_cancer.csv")
```

## Exporting data

``` r
write_csv(x = data_raw,
          file = "~/projects/project_r4bd/Data/data_raw.csv")
```
