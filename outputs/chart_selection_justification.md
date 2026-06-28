## Chart Selection Justification

### 1. Sales Trend View – Line Chart

A line chart was chosen because it is the best way to show how sales change over time. It helps identify increasing or decreasing sales trends and seasonal patterns across different months.

### 2. Regional Performance View – Bar Chart

A bar chart was chosen because it makes it easy to compare sales and profit across different regions. The length of the bars clearly shows which regions perform better and which perform worse.

### 3. Category Profitability View – Bar Chart

A bar chart was chosen because it allows easy comparison of profit across product categories and sub-categories. It helps identify the most profitable categories as well as those with lower profits.

### 4. Customer Segment View – Bar Chart

A bar chart was chosen because customer segments are separate groups. It provides a clear comparison of sales performance across the Consumer, Corporate, and Home Office segments.

### 5. Shipping Performance View – Bar Chart

A bar chart was chosen because it compares the average delivery days for each shipping mode. This makes it easy to identify which shipping methods deliver faster and which take longer.

### 6. Discount vs Profit View – Scatter Plot

A scatter plot was chosen because it is the most suitable chart for showing the relationship between two numerical variables. It helps identify whether profit tends to increase or decrease as discounts change and highlights any unusual values.

### 7. Return Analysis View – Bar Chart

A bar chart was chosen because it clearly compares return rates across categories, regions, or customer segments. It helps quickly identify the groups with the highest number of returns.



## Chart Selection Detailed Explanation

### 1. Sales Trend

**Question the chart answers:**
How have sales changed over time?

**Why the chart type is appropriate:**
A line chart is the best choice for showing changes and trends over time.

**Fields used:**

* **X-axis:** Order Date (Month)
* **Y-axis:** Sales
* **Color:** Single color used for consistency.
* **Filters:** Region, Category, Customer Segment.

**Design principle applied:**
A simple line chart was used to make the sales trend easy to follow without unnecessary visual elements.

**Mistake avoided:**
A bar chart was not used because it is less effective than a line chart for showing trends over time.



### 2. Regional Performance

**Question the chart answers:**
Which region generates the highest sales?

**Why the chart type is appropriate:**
A horizontal bar chart makes it easy to compare sales across regions.

**Fields used:**

* **Y-axis:** Region
* **X-axis:** Sales
* **Label:** Sales value
* **Color:** Profit
* **Filters:** Category, Customer Segment.

**Design principle applied:**
Bars were sorted to make comparisons quick and easy.

**Mistake avoided:**
State-level data was not used because it would create too many bars and make the chart difficult to read. Region-level data provides a clearer comparison and is more suitable for an executive dashboard.


### 3. Category Profitability

**Question the chart answers:**
Which categories and sub-categories generate the highest profit?

**Why the chart type is appropriate:**
A bar chart clearly compares profit across multiple categories and sub-categories.

**Fields used:**

* **Rows:** Category and Sub-category
* **Columns:** Profit
* **Label:** Profit value
* **Color:** Single color for consistency.
* **Filters:** Region, Customer Segment.

**Design principle applied:**
The chart groups sub-categories under each category to improve readability.

**Mistake avoided:**
Too many colours were avoided because they can make the chart difficult to understand.



### 4. Shipping Performance

**Question the chart answers:**
Which shipping modes have longer delivery times?

**Why the chart type is appropriate:**
A bar chart makes it easy to compare delivery performance across different shipping modes.

**Fields used:**

* **Rows:** Ship Mode
* **Columns:** Average Delivery Days
* **Color:** Shipping Delay Bucket
* **Filters:** Region, Category, Customer Segment.

**Design principle applied:**
Delivery times were grouped into delay buckets to make the comparison easier.

**Mistake avoided:**
Individual delivery records were not displayed because they would make the chart cluttered.



### 5. Discount vs Profit

**Question the chart answers:**
How does discount affect profit?

**Why the chart type is appropriate:**
A scatter plot is the best chart for showing the relationship between two numerical values.

**Fields used:**

* **X-axis:** Discount
* **Y-axis:** Profit
* **Detail:** Order ID
* **Filters:** Region, Category, Customer Segment.

**Design principle applied:**
Each point represents an order, making it easy to identify patterns and unusual values.

**Mistake avoided:**
A line or bar chart was not used because they do not show the relationship between two continuous variables.



### 6. Return Analysis

**Question the chart answers:**
Which product categories have higher return rates?

**Why the chart type is appropriate:**
A bar chart clearly compares return rates across categories.

**Fields used:**

* **Y-axis:** Category
* **X-axis:** Return Rate
* **Label:** Return Rate
* **Color:** Single color for consistency.
* **Filters:** Region, Customer Segment.

**Design principle applied:**
Percentage values were used to make the comparison easier to understand.

**Mistake avoided:**
Return counts alone were not used because percentages provide a fair comparison between categories.
