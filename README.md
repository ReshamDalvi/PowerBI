# Supply Chain & Operations Analytics Dashboard

**Project Objective**

The objective of this project is to develop an interactive Power BI dashboard that analyzes supply chain operations, supplier performance, manufacturing efficiency, inventory levels, and logistics costs. The dashboard helps identify cost patterns, monitor product quality, evaluate shipping performance, and generate actionable insights to support data-driven business decisions.

## Dataset Description

The project uses a sample makeup and cosmetics supply chain dataset covering product information, suppliers, inventory, manufacturing, quality inspections, and transportation.

### Dataset Columns

| Column                           | Description                                                                     |
|--------------------------------- | ------------------------------------------------------------------------------- |
| Product Type                     | Category or type of product                                                     |
| SKU                              | Unique stock-keeping identifier for a product                                   |
| Product Price                    | Price of an individual product                                                  |
| Availability                     | Indicates the availability status of products                                   |
| Products Sold                    | Number of units sold                                                            |
| Revenue Generated                | Revenue generated from product sales                                            | 
| Customer demographics            | Provides information about customer gender                                      |
| Stock Levels                     | Quantity of product currently in stock                                          |
| Operational Lead Time (Days)     | Duration recorded for the first operational lead-time measure, recorded in days |
| Order Quantities                 | Quantity of products ordered                                                    |
| Shipping Time (Days)             | Time taken for shipping, recorded in days                                       |
| Shipping Carriers                | Carrier responsible for transporting products                                   |
| Shipping Costs                   | Cost associated with shipping products                                          |
| Supplier Name                    | Name or label identifying the supplier                                          |
| Location                         | Location recorded for the supply-chain operation                                |
| Additional Lead Time (Days)      | Duration recorded for the second lead-time measure, recorded in days            |
| Production Volumes               | Quantity of products produced                                                   |
| Manufacturing Lead Time (Days)   | Time required for manufacturing, recorded in days                               |
| Manufacturing Costs              | Costs associated with manufacturing products                                    |
| Inspection Results               | Outcome of product quality inspections                                          |
| Defect Rates                     | Recorded product defect-rate value                                              |
| Transportation Modes             | Method used to transport products                                               |
| Routes                           | Route label associated with product transportation                              |
| Transportation Costs             | Costs associated with transportation                                            |

## Project Overview
**The Power BI report will help supply chain teams understand:**
- Overall revenue and product sales performance
- Production volumes and inventory levels
- Supplier contribution and operational performance
- Manufacturing costs and production efficiency
- Manufacturing and operational lead times
- Product quality through inspection results and defect rates
- Shipping costs and transportation expenses
- Shipping performance across carriers and transportation modes
- Location-wise revenue and logistics performance
- Cost variations across suppliers, products, and transportation routes


# Page 1 — Supply Chain Overview

**Cards**
- Total Revenue
- Total Products Sold
- Total Production Volume
- Total Inventory
- Average Defect Rate
- Total Suppliers

**Visuals**
- Quality Inspection Results - Donut Chart
- Revenue By Product Type - Pie Chart
- Inventory Distribution By Product Type
- Products Sold By Supplier - Clustered Column Chart
- Manufacturing Cost Vs Revenue By Product Type - Scatter Chart

**Slicers**
- Supplier Name
- Product Type

**Purpose:** Understand the overall supply chain performance through revenue, sales, production, inventory, and supplier distribution.

# Page 2 — Supplier & Manufacturing Analysis

**Cards**
- Total Manufacturing Cost
- Average Manufacturing Lead Time
- Total Production Volume
- Average Defect Rate

**Visuals**
- Manufacturing Cost vs Production Volume — Scatter Chart
- Average Operational Lead Time by Supplier — Clustered Bar Chart
- Manufacturing Lead Time by Supplier — Clustered Bar Chart
- Manufacturing Cost Breakdown - Waterfall Chart
- Supplier Quality Comparison — Matrix
- Production Volume By Supplier - Pie Chart

**Slicers**
- Location
- Supplier Name
- Inspection Results

**Drill-Through Analysis**
- Location & Supplier - Wise Total Revenue
- Supplier & Product Type - Wise Production Volume
- Location & Product Type - Wise Manufacturing Cost

**Purpose:** Evaluate supplier performance, manufacturing efficiency, production costs, lead times, and product quality.

# Page 3 — Logistics & Transportation Analysis

**Cards**
- Total Shipping Cost
- Total Transportation Cost
- Average Shipping Cost
- Average Shipping Time

**Visuals**
- Shipping Cost by Transportation Mode — Clustered Column Chart
- Revenue Analysis by Location & Shipping Carrier — Clustered Column Chart
- Shipping Cost Distribution by Route — Donut Chart
- Average Shipping Time by Shipping Carrier — Pie Chart

**Slicers**
- Location
- Routes
- Shipping Carriers
- Transportation Mode

**Interactive Features**
- Drill-Down Analysis — Location to Shipping Carrier
- Bookmarks — Switch between Shipping Cost and Shipping Time By Transportation Mode

**Purpose:** Analyze logistics expenses, shipping performance, carrier distribution, and transportation efficiency across locations and routes.

# Tools & Technologies
- Power BI — Dashboard development and data visualization
- Power Query — Data cleaning and transformation
- DAX — Measures, KPIs, and analytical calculations

#  Key Power BI Features
- Interactive Slicers and Filters
- Drill-Down
- Drill-Through
- Bookmarks
- Tooltips
- KPI Cards
- Data Modeling and Visualizations
