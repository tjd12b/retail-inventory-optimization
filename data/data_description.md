# Data Description

## reorderpoints(Store and Warehouse Reorders).csv
Contains warehouse and accounting information regarding reorder points, reorder amounts, cost and price.

Columns:
- Product: Product name
- Fully Stocked: Warehouse level inventory limit
- Reorder Point: Inventory level at which the Warehouse will order more of a product
- Reorder Amount: Quantity of each product received when an order is placed
- Quantity per case: Quantity of each product per case received during reorder
- Wholesale Price Each: Wholesale price for each individual product in a case
- Cost per Case: Total cost for entire case
- Retail Price: Total price that a case level quantity of product is sold for at the store level

## 8weekInventories(Store 1).csv
Contains weekly inventory levels for Store 1 over an 8-week period. Used for Warehouse visualisations.

Columns:
- Product: Product name
- Fully Stocked: Store level inventory limit
- Week 1-8 Inventory: Store level inventory status per product per week
- On Hand: Number of each product on hand at the store level

## 8weekInventories(Store 2).csv
Contains weekly inventory levels for Store 2 over an 8-week period. Used for Point of Sale (POS) visualisations.

Columns:
- Product: Product name
- Fully Stocked: Store level inventory limit
- Week 1-8 Inventory: Store level inventory status per product per week

## 8weekInventories(Store 8).csv
Contains weekly inventory levels for Store 8 over an 8-week period. Used for Accounting visualisations.

Columns:
- Product: Product name
- Fully Stocked: Store level inventory limit
- Week 1-8 Inventory: Store level inventory status per product per week