# Mitigating-Global-Supply-Chain-Risks-for-GlobalLogiX

📊 Overview
A comprehensive Power BI dashboard designed to transform reactive supply chain management into proactive risk mitigation for GlobalLogiX. This solution provides real-time visibility into supplier risks, logistics bottlenecks, inventory inefficiencies, and cost leakage across global operations.

🎯 Key Objectives
Centralized Risk Identification: Proactively identify high-risk suppliers before failures occur

Logistics Transparency: Uncover root causes of shipment delays

Inventory Optimization: Balance stock levels across high-demand and overstocked regions

Cost Control: Monitor and reduce return costs from damaged items and quality issues

📁 Datasets
The dashboard integrates data from five core pillars:

Suppliers: Risk score, region, reliability, defect rates

Shipments: Delivery status, delay reasons, shipping dates, regions

Orders: Past orders, delivery timelines, demand trends

Warehouses: Inventory levels, replenishment status, thresholds

Returns: Return reasons, costs, frequencies, shipment links

🛠️ Technical Implementation
Data Transformation (Power Query)
Consolidated 5 distinct datasets into a structured data model

Corrected data types (e.g., Order Date from text to date format)

Cleaned null/hyphen values in Returns table

Created dedicated Date Table for time-intelligence analysis

Data Modeling
Star Schema architecture with Orders as the central fact table

Dimension Tables: Suppliers, Warehouses, Returns, Shipments, and Date

Established relationships using primary/foreign keys for optimal performance

DAX Measures
Key performance indicators developed for dynamic analysis:

Avg Supplier Risk Score - Supply chain health monitoring

ON-TIME DELIVERY RATE - Logistics efficiency tracking

Total Return Cost & Total Transportation Cost - Financial impact analysis

Supplier Risk Flag - High-risk supplier identification (Risk_Score > 80)

📱 Dashboard Pages
Risk Suppliers & Stock Monitoring - Conditional formatting highlights high-risk, low-stock suppliers

Return & Delivery Performance - Pie/Stacked charts analyze return reasons and delivery status

Supplier Performance Dashboard - Drill-down matrix from country to individual supplier

Dynamic KPI Metrics - Executive scorecard with 8+ real-time KPIs

Logistic Cost Optimization - Combo chart correlating order volume with freight costs

🎨 User Experience
Custom Theme: Dark-mode "CY24SU10" for enhanced readability

Synchronized Slicers: Cross-page filtering for consistent analysis

Drill-through Features: Detailed supplier cards accessible from any page

Interactive Visuals: Dynamic updates based on user selections

💡 Business Impact
This dashboard enables GlobalLogiX to:

Transition from reactive firefighting to proactive risk management

Predict supply chain disruptions before they occur

Optimize inventory allocation across global regions

Reduce operational costs through data-driven decisions

🚀 Technical Stack
Power BI - Dashboard development and visualization

Power Query (M) - Data transformation and cleaning

DAX - Custom measures and business logic

Data Modeling - Star schema architecture

Excel/CSV - Source data formats
