# Model-based Estimates of Deaths Caused by SARS-CoV-2 Variants in the United States

Contents:

* *Provisional_COVID-19_Death_Counts_by_Week_Ending_Date_and_State (3).csv*: COVID-19 death data downloaded from the CDC NCHS on May 12th, 2022 from https://www.cdc.gov/nchs/nvss/vsrr/covid19/index.htm.

* *RegionsDashboard (3).csv*: National and regional-level SARS-CoV-2 variant proportions estimated by the CDC. Downloaded on May 12th, 2022 from https://covid.cdc.gov/covid-data-tracker/#variant-proportions.

* *variant surveillance system.R*: Slightly modified CDC code used to generate jurisdiction-level variant proportions. Original code (which produces national and regional-level estimates only) downloaded from https://github.com/CDCgov/SARS-CoV-2_Genomic_Surveillance/tree/master/Code.

* *example_data.csv*: Unmodified CDC variant surveillance data. Used as an input for *variant surveillance system.R*. Originally downloaded from https://github.com/CDCgov/SARS-CoV-2_Genomic_Surveillance/tree/master/Code.
