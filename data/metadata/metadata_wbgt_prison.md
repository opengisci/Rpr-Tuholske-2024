-   `Title`: wbgt_raw/prison/weighted_area_raster_prison_wbgtmax_daily\_(year).rds
-   `Abstract`: Daily WBGTmax, weighted by area, from 1982-2020
-   `Spatial Coverage`: United States Lower 48
-   `Spatial Resolution`: Prison by prison ID
-   `Spatial Representation Type`: N/A
-   `Spatial Reference System`: N/A
-   `Temporal Coverage`: Year
-   `Temporal Resolution`: Day of year
-   `Lineage`:
    -   Heat data acquired from Parameter-elevation Regressions on Independent Slopes Model (PRISM) [dataset](https://prism.oregonstate.edu/recent/)
    -   Prison data acquired from Homeland Infrastructure Foundation-Level Data (HIFLD), produced by the Department of Homeland Security
    -   WBGTmax estimated by authors using high-resolution (4 km) daily maximum 2 m air temperature data (Tmax), and maximum vapour pressure deficit data (VPDmax)
-   `Distribution`: Data available in original study's [git repository](https://github.com/sparklabnyc/temperature_prisons_united_states_2024)
-   `Constraints`: Open access Creative Commons Attribution 4.0 International License,
-   `Data Quality`: Data lacks sufficient documentation in the original study repository/resources, further, the link to the HIFLD data no longer works.

| Label | Alias | Definition | Type | Accuracy | Domain | Missing Data Value(s) | Missing Data Frequency |
|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
| prison_id | ... | unqiue prison id | integer | ... | 6640 prisons | ... | ... |
| wbgtmax | ... | wbgtmax estimated for specified day | integer | ... | ... | missing data not included | ... |
| date | ... | day of year (dd/mm/yyyy) | character string | ... | ... | ... | ... |
| day | ... | day | integer | ... | ... | ... | ... |
| month | ... | month | integer | ... | ... | ... | ... |
| year | ... | year | integer | ... | ... | ... | ... |

