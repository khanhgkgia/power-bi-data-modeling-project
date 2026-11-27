# Data Modeling Process

## 1. Data Organization
- 01_Stage
- 02_Dimensions
- 03_Facts
- 04_Support

## 2. Dimension Tables
- Combine tables by entity
- Remove testing and duplicate records
- Merge related tables
- Validate relationships

## 3. Additional Dimensions
- Identify remaining descriptive attributes
- Create junk dimensions for flags

## 4. Fact Tables
- Identify business processes
- Retrieve dimension keys
- Remove redundant descriptive columns
- Validate duplicate keys

## 5. Factless Fact Tables
- Identify events without measures
- Connect relevant dimensions

## 6. Accumulating Snapshot Fact
- Combine order, shipping, delivery,
  invoicing and payment stages

## 7. Date Dimension
- Create dim_date
- Add year and month attributes
- Connect fact tables to dates

## 8. Final Validation
- Check formats and column names
- Review aggregation settings
- Validate the model in Table View