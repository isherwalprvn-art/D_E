# RetailMart Dataset

Synthetic data created for learning. It contains intentional defects. Do not manually repair raw files. Detect, reject, and document invalid records in the ETL pipeline.

## Volumes
- 2,002 customer rows including defects
- 301 product rows including defects
- 30 stores
- 20 promotions
- 3,000 inventory snapshot rows
- 7 daily sales files, roughly 17,500 valid-pattern rows plus defects

## Intentional issues
- Duplicate customer and sales identifiers
- Invalid date
- Missing city
- Negative price and quantity
- Discount above allowed range
- Unknown store/customer identifiers
