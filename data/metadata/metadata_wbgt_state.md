-   `Title`: wbgt_raw/state/weighted_area_raster_fips_wbgtmax_daily\_(year).rds
-   `Abstract`: Daily WBGTmax, weighted by area, from 1982-2020
-   `Spatial Coverage`: United States Lower 48
-   `Spatial Resolution`: County by FIPS Code
-   `Spatial Representation Type`: N/A
-   `Spatial Reference System`: N/A
-   `Temporal Coverage`: Each year, 1982-2020
-   `Temporal Resolution`: Day of year
-   `Lineage`:
    -   Acquired from Parameter-elevation Regressions on Independent Slopes Model (PRISM) [dataset](https://prism.oregonstate.edu/recent/)
    -   WBGTmax estimated by authors using high-resolution (4 km) daily maximum 2 m air temperature data (Tmax), and maximum vapour pressure deficit data (VPDmax)
-   `Distribution`: Data available in original study's [git repository](https://github.com/sparklabnyc/temperature_prisons_united_states_2024)
-   `Constraints`: Open access Creative Commons Attribution 4.0 International License,
-   `Data Quality`: Data lacks sufficient documentation in the original study repository/resources.

| Label | Alias | Definition | Type | Accuracy | Domain | Missing Data Value(s) | Missing Data Frequency |
|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
| fips | ... | county fips code | integer | ... | ... | ... | ... |
| wbgtmax | ... | wbgtmax estimated for specified day | integer | ... | ... | missing data not included | ... |
| date | ... | day of year (dd/mm/yyyy) | character string | ... | ... | ... | ... |
| day | ... | day | integer | ... | ... | ... | ... |
| month | ... | month | integer | ... | ... | ... | ... |
| year | ... | year | integer | ... | ... | ... | ... |
