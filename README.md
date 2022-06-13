# Datasets

## Singapore HDB Flat Resale Prices (1990-2020)

###  Columns:
  - `month`: month and year of transaction _(Datetime "YYYY-MM")_
  - `town`: town _(Text)_
  - `flat_type`: flat type _(Text)_
  - `block`: block number _(Text)_
  - `street_name`: street name _(Text)_
  - `storey_range`: storey range _(Text)_
  - `floor_area_sqm`: floor area in square metres _(Numeric)_
  - `flat_model`: flat model _(Text)_
  - `lease_commence_date`: the year the lease started _(Datetime "YYYY")_
  - `remaining_lease`: remaining lease _(Text)_
  - `resale_price`: nominal resale price _(Numeric)_

### Info

- Source: https://data.gov.sg/dataset/resale-flat-prices
- Metadata: [metadata-resale-flat-prices](singapore-flat-proces/metadata-resale-flat-prices.txt)
- Last updated	June 13, 2022
- Created	July 28, 2021
- Format	CSV
- Coverage	January 1, 2017 to June 12, 2022
- Licence	Singapore Open Data Licence

- Raw CSV for Jan. 2017 onward: https://github.com/noghte/datasets/blob/main/singapore-flat-prices/resale-flat-prices-based-on-registration-date-from-jan-2017-onwards.csv?raw=true