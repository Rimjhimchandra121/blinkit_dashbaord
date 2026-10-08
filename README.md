# blinkit_dashbaord
its a power bi dashboard
🛒 Blinkit Sales Dashboard (Power BI)

An interactive Power BI dashboard analysing Blinkit (India's Last Minute App) grocery sales across item types, outlet sizes, outlet locations, outlet types and establishment years.

📸 Dashboard preview: add a screenshot here ![Dashboard Preview](images/dashboard.png)

📌 Project Overview

This project explores a grocery retail dataset (BlinkIT Grocery Data) to understand what drives sales and customer ratings. The dashboard gives a single-page, filterable view of performance so business users can quickly compare outlets, product categories and locations.

Key questions answered

How much are total and average sales, and how many items are sold?
What is the average customer rating?
Which item types contribute the most to sales?
How do sales differ by fat content (Low Fat vs Regular)?
How do outlet size, location tier and outlet type affect performance?
How have sales evolved by outlet establishment year?
📊 Dashboard Features

KPI cards

KPI	Description
Total Sales	Sum of sales across the selected filters
Average Sales	Average sales per item/transaction
No. of Items	Count of items
Average Rating	Mean customer rating

Visualizations

Visual	Purpose
Donut chart: Fat Content	Share of sales by item fat content
Clustered bar: Fat Outlet	Outlets by size, split by fat content
Clustered bar: Item Type	Total sales by product category
Line chart: Outlet Establishment Year	Sales trend by year the outlet was established
Donut chart: Outlet Size	Share of sales by outlet size
Funnel: Outlet Location	Sales by location tier
Table: Outlet Type	Total sales, items, average sales, average rating and item visibility per outlet type

Interactivity

Filter panel with slicers for Outlet Location Type, Outlet Size and Item Type
Metric selector (parameter slicer) to switch the displayed measure
Cross-filtering between all visuals
🗂️ Data Model
Table	Description
BlinkIT Grocery Data	Fact table with item and outlet level records
Metrics	Parameter table used for the metric selector

Main fields used: Item Fat Content, Item Type, Item Visibility, Outlet Size, Outlet Location Type, Outlet Type, Outlet Establishment Year, Sales, Rating

Measures: Total Sales, Avg Sales, No of Items, Avg Rating

🛠️ Tools & Technologies
Power BI Desktop: data modelling, DAX and visualization
DAX: calculated measures
Power Query: data cleaning and transformation
🚀 How to Use
Clone or download this repository:
bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
Open BLINKIT.pbix in Power BI Desktop (free download from Microsoft).
Use the Filter Panel to slice by location, outlet size and item type.
Hover over or click any visual to cross-filter the rest of the dashboard.
📁 Repository Structure
├── BLINKIT.pbix        # Power BI dashboard file
├── README.md           # Project documentation
└── images/
    └── dashboard.png   # Dashboard screenshot
🔍 Key Insights

Add your own findings here after exploring the dashboard, for example:

Top-performing item types: …
Best-performing outlet size / location tier: …
Sales trend by establishment year: …
Low Fat vs Regular share of sales: …
