# Model-based Estimates of Deaths Caused by SARS-CoV-2 Variants in the United States

Contents:

*DeathsByVariants_V1.Rmd*: Primary code used to replicate the analysis.

* *Provisional_COVID-19_Death_Counts_by_Week_Ending_Date_and_State (3).csv*: COVID-19 death data downloaded from the CDC NCHS on May 12th, 2022 from https://www.cdc.gov/nchs/nvss/vsrr/covid19/index.htm. Input to *DeathsByVariants_V1.Rmd*.

* *RegionsDashboard (3).csv*: National and regional-level SARS-CoV-2 variant proportions estimated by the CDC. Downloaded on May 12th, 2022 from https://covid.cdc.gov/covid-data-tracker/#variant-proportions. Input to *DeathsByVariants_V1.Rmd*.

* *variant surveillance system.R*: Slightly modified CDC code used to generate jurisdiction-level variant proportions. Original code (which produces national and regional-level estimates only) downloaded from https://github.com/CDCgov/SARS-CoV-2_Genomic_Surveillance/tree/master/Code. Before this code can be run, one must download https://github.com/CDCgov/SARS-CoV-2_Genomic_Surveillance/blob/master/Code/example_data.csv.

* *variant_share_weekly_weighted.csv*: National- and regional-level variant proportions for the year 2021. Output from *variant surveillance system.R*. Input to *DeathsByVariants_V1.Rmd*.

* *state_variant_share_weekly_weighted.csv*: Jurisdiction-level variant proportions for the year 2021. Output from *variant surveillance system.R*. Input to *DeathsByVariants_V1.Rmd*.
