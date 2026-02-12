# Data Dictionary — Superstore Sales Dataset

| Column Name | Data Type | Description | Business Relevance |
|--------------|-----------|-------------|-------------------|
| Row ID | Integer | Unique identifier for each transaction | Helps identify duplicates |
| Order ID | Object | Unique order identifier | Used to track orders |
| Order Date | Date | Date of order placement | Time-series sales analysis |
| Ship Date | Date | Date of shipment | Delivery performance analysis |
| Ship Mode | Category | Shipping method used | Logistics analysis |
| Customer ID | Object | Unique customer identifier | Customer segmentation |
| Customer Name | Object | Name of customer | Customer-level analysis |
| Segment | Category | Customer segment | Segment performance analysis |
| Country | Category | Country of order | Geographic analysis |
| City | Category | Customer city | Regional analysis |
| State | Category | Customer state | Location analysis |
| Postal Code | Numeric | Postal area code | Delivery mapping |
| Region | Category | Sales region | Regional comparison |
| Product ID | Object | Product identifier | Product tracking |
| Category | Category | Product category | Category sales analysis |
| Sub-Category | Category | Product sub-category | Detailed performance analysis |
| Product Name | Object | Name of product | Product-level insights |
| Sales | Float | Revenue generated | Key business KPI |