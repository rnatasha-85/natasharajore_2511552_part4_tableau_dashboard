# natasharajore_2511552_part4_tableau_dashboard

## 1. Business Problem Summary

The leadership team wants to understand sales performance across regions, products, customer segments, shipping methods, and discounts. The objective is to identify the factors affecting sales, profit, and returns so that informed business decisions can be made to improve overall performance.

## 2. Dataset Description

The dataset contains retail order information, including order details, customer information, product categories, geographic locations, shipping details, sales, profit, discounts, delivery time, customer ratings, campaign channels, and return status. The data was used to analyse business performance and build an interactive executive dashboard.

### Dataset Review

Date fields (Datatype: Date)
- order_date
- ship_date
  
Geographic fields (Datatype: Text (Categorical))
- region
- state
- city

Categorical fields (Datatype: Text (Categorical))
- customer_segment
- category
- sub_category
- product_name
- ship_mode
- campaign_channel
  
Numerical measures (Datatype: Numeric)
- sales
- quantity
- discount
- profit
- delivery_days
- customer_rating

Binary/flag fields (Datatype: Integer - Binary (0/1) )
- return_flag
  
Identifier Fields (Datatype: Text / ID)
- order_id
- customer_id

### Assumptions
- order_id uniquely identifies each order, while customer_id identifies individual customers.
- order_date and ship_date are assumed to be valid dates and are used to calculate or verify delivery_days.
- Geographic fields (region, state, and city) are assumed to follow consistent naming conventions after data cleaning.
- Categorical fields (such as customer_segment, category, sub_category, ship_mode, and campaign_channel) are assumed to contain valid business-defined categories after standardization.
- Numerical fields (sales, quantity, discount, profit, delivery_days, and customer_rating) are assumed to contain valid numeric values suitable for analysis after data validation.
- No assumptions are made about the relationships between variables; the analysis relies solely on the values present in the dataset.

## 3. Tableau Workbook Description

The Tableau workbook contains:
- Calculated fields for business metrics.
- Individual worksheets for each business view.
- An executive dashboard with KPI cards, charts, filters, and interactive actions.
- Interactive filters that allow users to analyse performance across different business dimensions.

## 4. Calculated Fields Created

The following calculated fields were created:
- Profit Margin = Profit ÷ Sales
- Cost = Sales − Profit
- Average Order Value = Total Sales ÷ Total Orders
- Return Rate = Returned Orders ÷ Total Orders
- Shipping Delay Bucket = Delivery days grouped into meaningful ranges

## 5. Dashboard Components

The dashboard includes:
- Dashboard title
-KPI cards:
  - Total Sales
  - Total Profit
  - Return Rate
- Sales Trend (Line Chart)
- Regional Performance (Bar Chart)
- Category Profitability (Bar Chart)
- Shipping Performance (Bar Chart)
- Discount vs Profit (Scatter Plot)
- Return Analysis (Bar Chart)

## 6. Filters and Interactions Used

Filters:
- Region
- Category
- Customer Segment

Dashboard Interaction:
A filter action was added so that selecting a region updates the remaining charts in the dashboard, allowing users to analyse regional performance in more detail.

## 7. Key Business Insights
- Sales fluctuate over time, with recent months showing stronger performance.
- The South region records the highest sales.
- Profit differs across product categories and sub-categories.
- Higher discounts do not always lead to higher profits.
- Furniture has a higher return rate than Technology.
- Delivery performance varies across shipping modes.
- Returns and delivery delays may affect overall profitability.
- Regional and product-level analysis helps identify improvement opportunities.

## 8. Dashboard Story Summary

The dashboard provides a complete view of retail business performance by combining sales, profit, regional performance, product profitability, discounts, shipping performance, and returns. While sales remain strong, opportunities exist to improve profitability by reducing returns, reviewing discount strategies, and improving delivery performance. The dashboard helps leadership quickly identify business strengths, risks, and areas that require further investigation.

## 9. Assumptions and Limitations

Assumptions:
- Order IDs uniquely identify customer orders.
- Discount values are stored as decimal values.
- Return Rate is calculated using unique orders.
- Delivery days correctly represent the difference between the order date and ship date.
- All calculations are based on the cleaned dataset.

Limitations:
- The dashboard provides summary-level analysis and does not explain the reasons behind business performance.
- Marketing activities, inventory levels, supplier information, and customer feedback are not included in the dataset.
- Customer behaviour can only be analysed using the available fields.

## 10. Screenshots Included
The following screenshots are included as part of the submission:
- Complete executive dashboard
- Sales trend chart
- Regional performance
- Category profitability
- Evidence of filter or dashboard interaction
