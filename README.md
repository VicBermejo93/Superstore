# Superstore



The Dataset

Context
With growing demands and cut-throat competitions in the market, a Superstore Giant is seeking your knowledge in understanding what works best for them. They would like to understand which products, regions, categories and customer segments they should target or avoid.

You can download the original dataset here: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The original dataset consists only on one table, containing the following columns:

Campo
Descripción
Data Type
Row ID
Unique ID for each row.
Int
Order ID
Unique Order ID for each Customer.
String
Order Date
Order Date of the product.
DateTime
Ship Date
Shipping Date of the Product.
DateTime
Ship Mode
Shipping Mode specified by the Customer.
String
Customer ID
Unique ID to identify each Customer.
Int
Customer Name
Name of the Customer.
String
Segment
The segment where the Customer belongs.
String
Country
Country of residence of the Customer.
String
City
City of residence of the Customer.
String
State
State of residence of the Customer.
String
Postal Code
Postal Code of every Customer.
Int
Region
Region where the Customer belongs.
String
Product ID
Unique ID of the Product.
String
Category
Category of the product ordered.
String
Sub-Category
Sub-Category of the product ordered.
String
Product Name
Name of the Product
String 
Sales
Sales of the Product.
Float
Quantity
Quantity of the Product.
Int
Discount
Discount provided.
Float
Profit
Profit/Loss incurred.
Float



Data Transformation and Processing

The building of the data model consist in:
Creating Dimensional Tables for readability such as DimProduct, DimLocation and Dim Customer.
Creating a DimDate or Calendar table to apply time intelligence approach.
Writing DAX measures as business metrics.

Insights

Although the current Revenue has ramped up with an average annual growth rate about 15%, the analysis has identified reported that the profit has experienced reductions due to patterns identified:
1 out of 5 states is reporting negative results (e.g., Texas only reports above 25k USD). Other States showing the same results are Ohio, Tennessee, Illinois,  North Dakota and Pennsylvania. Besides, the financial results rely on the market segment, being the final consumer segment with the greatest impact in the financial result overall.
Product Families such as Supplies (Office Supplies), tables and Bookcases (Furniture) reported losses, meanwhile same categories providing discounts, specially for furniture subcategories are impacting directly their financial performance.
Apart from the discount contribution, the output comparison between ship mode is giving a relationship in financial performance per category. For example, Bookcases is reporting a positive output overall when a customer chooses “same day” as delivery option, otherwise, the profit will come back as losses.

Recommendations and Next Steps

Addressing efforts for those customers and interactions in those states reporting the lowest financial performance.
Adapting the Costs dynamic for shipping mode, specially for furniture subcategories.
Optimizing the Discount/Pricing strategy for the subcategories Supplies (included Office Supplies categories), Bookcases and Tables (both included in Furniture).

