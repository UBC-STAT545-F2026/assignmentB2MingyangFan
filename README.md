
<!-- README.md is generated from README.Rmd. Please edit that file -->

# assignmentB2MingyangFan

The goal of assignmentB2MingyangFan is to provide a function that counts
the number of missing values for all columns in each group of a dataset.
This package gives users the opportunity to identify and compare these
missing values.

## Installation

Package installation can be done directly by calling

`devtools::install_github("UBC-STAT545-F2026/assignmentB2MingyangFan", ref = "0.1.0")`

## Example

This is an example using the built-in airquality dataset to count the
missing values in each column for each month:

``` r
library(assignmentB2MingyangFan)

count_all_missing_by_group(airquality, Month)
#> # A tibble: 5 × 6
#>   Month Ozone Solar.R  Wind  Temp   Day
#>   <int> <int>   <int> <int> <int> <int>
#> 1     5     5       4     0     0     0
#> 2     6    21       0     0     0     0
#> 3     7     5       0     0     0     0
#> 4     8     5       3     0     0     0
#> 5     9     1       0     0     0     0
```
