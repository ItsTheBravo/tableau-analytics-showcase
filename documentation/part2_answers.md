# Part 2: Supply Chain Analytics - Answers

## Q3: Percentage of Delayed Orders

**Question**: What percentage of orders were delayed?

**Answer**: 22.96% delayed, 77.04% delivered

**Methodology**:
- Created pie chart with Delivery Status as Color
- Added Quantity Ordered to Size
- Added Quantity Ordered to Label with Percent of Total calculation
- Visualization shows distribution of delivery performance

**Visualization**: See `screenshots/q3_delivery_status_pie_chart.png`

---

## Q4: Courier Performance Analysis

**Question**: Using the plot answer the following questions:
- (a) Which courier had the most delayed deliveries and how many?
- (b) Which courier had the most on time (delivered) deliveries and how many?

**Answers**:
- **(a)** Maersk Shipping had the most delayed deliveries: **6,273 orders**
- **(b)** FedEx Logistics had the most on-time deliveries: **20,469 orders**

**Methodology**:
- Created vertical bar chart with Quantity Ordered on Rows
- Added Delivery Status and Transporter Name to Columns
- Color-coded by Delivery Status for visual separation
- Analyzed bar heights to identify best and worst performers

**Visualization**: See `screenshots/q4_courier_performance_bar_chart.png`

---

## Section 2.3: Customer Map

**Objective**: Visualize geographic distribution of customers and order quantities

**Methodology**:
- Created map using Longitude and Latitude (double-click method)
- Set opacity to 60% to reduce overplotting
- Added Quantity Ordered to Size for visual proportionality
- Added Quantity Ordered to Color (as Average) to show quantity intensity
- Applied Orange-Blue Diverging color palette (reversed)
- Added Customer Country to Details for tooltip information

**Key Insights**: 
- Geographic spread across USA, Europe, and Asia
- Larger circles indicate higher order volumes
- Color intensity shows average order quantities by location

**Visualization**: See `screenshots/world_map_customer_distribution.png`

---

## Q5: Scatterplot Regression Analysis

**Question**: Use the scatterplot to answer the following questions:
- (a) The slope of the line
- (b) The intercept
- (c) The R-squared value

**Answers**:
- **(a) Slope: 98.3255**
- **(b) Intercept: 26633**
- **(c) R-squared: 0.981412**

**Equation**: Total Price = 98.3255 × Unit Price + 26633

**Interpretation**:
- Strong positive linear relationship between Unit Price and Total Price
- R² of 0.981 indicates 98.1% of variance in Total Price is explained by Unit Price
- For every $1 increase in Unit Price, Total Price increases by approximately $98.33
- P-value < 0.0001 indicates highly significant relationship

**Methodology**:
- Created scatterplot with Unit Price (x-axis) and Total Price (y-axis)
- Color-coded by Product Name to show distribution across products
- Added linear trend line using Analytics pane
- Extracted regression statistics from trend line description

**Visualizations**: 
- See `screenshots/q5_scatterplot_with_trendline.png`
- See `screenshots/q5_regression_statistics.png`

---

## Q6: Sales Performance Dashboard Insights

**Question**: Using the dashboard answer the following questions:
- (a) Which supplier generated the least revenue?
- (b) Which product generated the most revenue?
- (c) Which two countries generated the most revenue for the country?

**Answers**:
- **(a) Global Tech Parts** generated the least revenue among suppliers
- **(b) Solar Panel** generated the most revenue among products
- **(c) India and UK** were the top two revenue-generating countries

**Methodology**:
- Created three individual bar charts (Total Price per Product, Supplier, and Country)
- Combined all three into a unified Sales Performance dashboard
- Sorted all charts by Total Price in descending order
- Arranged dashboard with 2x1 layout (Supplier and Country on top, Product on bottom)

**Key Business Insights**:
- Solar Panel, WiFi Module, and Door Sensor are top revenue drivers
- India and UK represent the strongest markets
- Quantum Supplies leads supplier revenue generation
- Global Tech Parts may need sales strategy review

**Visualization**: See `screenshots/q6_sales_performance_dashboard.png`

---

## Q7: Warehouse Performance Analysis

**Question**: Using the visualizations created above answer the following questions:
- (a) Which Warehouse generated the most revenue?
- (b) Which Warehouse had the most orders?

**Answers**:
- **(a) West Coast DC** generated the most revenue: **$5,697,314**
- **(b) Middle East Hub** had the most orders: **224 orders**

**Methodology**:
- Created two horizontal bar charts to analyze warehouse performance
- Chart 1: Total Price by Warehouse Name (revenue analysis)
- Chart 2: Distinct Count of Order ID by Warehouse Name (order volume analysis)
- Sorted both charts in descending order for easy comparison

**Key Business Insights**:
- West Coast DC leads in revenue despite not having the highest order count
- Middle East Hub processes the most orders but ranks second in revenue
- Suggests West Coast DC handles higher-value orders on average
- East Coast DC underperforms in both metrics, may need attention

**Visualizations**: 
- See `screenshots/q7_warehouse_revenue.png`
- See `screenshots/q7_warehouse_order_count.png`

---

