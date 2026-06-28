# natasharajore_2511552_part4_tableau_dashboard

## Dataset Review

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
