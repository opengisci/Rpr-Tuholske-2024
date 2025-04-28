- `Title`: states.shp
- `Abstract`: state boundary polygons with region
- `Spatial Coverage`: The 50 US states and Washington DC
- `Spatial Resolution`: US state
- `Spatial Representation Type`: `vector` `MULTIPOLYGON`
- `Spatial Reference System`: EPSG 4269
- `Temporal Coverage`: n/a -- should I say as of 2020 ish?
- `Temporal Resolution`: n/a
- `Lineage`: unknown
- `Distribution`: Data available in original study's [git repository](https://github.com/sparklabnyc/temperature_prisons_united_states_2024)
- `Constraints`: Public domain
- `Data Quality`: n/a
- `Variables`: For each variable, enter the following information. If you have two or more variables per data source, you may want to present this information in table form (shown below)
  - `Label`: variable name as used in the data or code
  - `Alias`: intuitive natural language name
  - `Definition`: Short description or definition of the variable. Include measurement units in description.
  - `Type`: data type, e.g. character string, integer, real
  - `Accuracy`: e.g. uncertainty of measurements
  - `Domain`: Expected range of Maximum and Minimum of numerical data, or codes or categories of nominal data, or reference to a standard codebook
  - `Missing Data Value(s)`: Values used to represent missing data and frequency of missing data observations
  - `Missing Data Frequency`: Frequency of missing data observations: not yet known for data to be collected

| Label | Alias | Definition | Type | Accuracy | Domain | Missing Data Value(s) | Missing Data Frequency |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| STATE_NAME | Name | Name of state | character string | n/a | US state names | n/a | n/a |
| DRAWSEQ | Draw Sequence | unknown | integer | n/a | 1-51 | n/a | n/a |
| STATE_FIPS | FIPS Code | State FIPS code (two digit) | integer | n/a | 01-56 | n/a | n/a |
| SUB_REGION | Sub-Region | Sub-Region of the US | character string | n/a | n/a | n/a | n/a |
| STATE_ABBR | Abbreviation | Two letter abbreviation | character string | n/a | two-letter postal abbreviations | ... | ... |
