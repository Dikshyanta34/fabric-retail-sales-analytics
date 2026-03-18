# fabric-retail-sales-analytics
Microsoft fabric to Power BI
## Data Ingestion (Lakehouse)

1. Created a Lakehouse in Microsoft Fabric.
2. Uploaded the Excel dataset into the Files section.
3. Loaded Excel sheets into Lakehouse tables:
   - Sales_Fact
   - Customers
   - Products
   - Stores
   - Date_Dimension

## Semantic Model

A Direct Lake semantic model was created using the following tables:

- Sales_Gold
- Customers
- Products
- Stores
- Date_Dimension

Relationships were defined to form a star schema.

## End-to-End Workflow

1. Data Source: Excel dataset
2. Data Storage: Microsoft Fabric Lakehouse
3. Data Processing: PySpark Notebook
4. Data Layers:
   - Bronze: Raw data
   - Silver: Cleaned data
   - Gold: Analytics-ready data
5. Semantic Model: Direct Lake
6. Visualization: Power BI Dashboard
