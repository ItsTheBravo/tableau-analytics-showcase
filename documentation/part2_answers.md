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

