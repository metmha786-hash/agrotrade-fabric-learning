# AgroTrade Fabric Learning

A practice project for learning Microsoft Fabric using fictional
AgroTrade sales data for Rice, Wheat, and Maize.

## Learning Goals
- Store sales CSV files in GitHub.
- Copy data into a Microsoft Fabric Lakehouse.
- Use notebooks to clean data and load Delta tables.
- Use SQL to analyse sales.
- Connect pipeline activities and schedule automatic runs.

## Planned Pipeline
1. Download the sales CSV from GitHub using an HTTP source.
2. Save the raw file in AgroTrade_Lakehouse.
3. Run a notebook after the copy succeeds.
4. Clean and load the data into a Delta table.
5. Schedule the pipeline and monitor its runs.

## Data
The practice data includes SaleID, SaleDate, Product,
QuantityBags, and SalesAmountPKR.

All data is fictional and intended for learning.
