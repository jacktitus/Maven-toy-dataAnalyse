Maven Toy Data Analysis

The aim of this SQL project is to analyze the toy sales data to gain insights into inventory management, 
product performance, sales trends, and store operations. The analysis will be performed using four tables: 
inventory, products, sales, and stores.

Dataset:
1. inventory
• Store_ID: Unique identifier for the store.
• Product_ID: Unique identifier for the product.
• Stock_On_Hand: Number of units available in stock.
2. products
• Product_ID: Unique identifier for the product.
• Product_Name: Name of the product.
• Product_Category: Category of the product (e.g., educational, plush, action figures, etc.).
• Product_Cost: Cost price of the product.
• Product_Price: Selling price of the product.
3. sales.
• Sale_ID: Unique identifier for the sale.
• Date: Date the sale was made.
• Store_ID: Identifier linking to the stores table.
• Product_ID: Identifier linking to the products table.
• Units: Number of units sold.
4. stores
• Store_ID: Unique identifier for the store.
• Store_Name: Name of the store.
• Store_City: City where the store is located.
• Store_Location: Location details of the store.
• Store_Open_Date: Date when the store was opened
