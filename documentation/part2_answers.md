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

