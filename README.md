# MarketFlash_BIproject
## 📊Overview
MarketFlash is an end-to-end Business Intelligence solution designed to track, visualize, and optimize marketing campaign performance. By integrating raw data into a structured SQL database and visualizing it through Tableau, this project provides actionable insights into audience engagement, executive efficiency, and global sales growth.

## 🎯Project Objective
Performance Tracking: Analyze key metrics like Views, Clicks, and Conversions across various marketing channels.

Financial Oversight: Monitor campaign expenses versus total sales to calculate ROI.

Strategic Optimization: Identify high-performing audiences and locations to guide future marketing spend.

Accountability: Measure executive and team performance based on conversion targets.


## 🏗️ Database Design/Architecture
The project utilizes a Star Schema centered around a primary Fact Table to ensure high-performance querying and reporting.

Data Model Highlights:
Fact Table (Campaigns): Stores quantitative metrics including views, likes, clicks, conversions, expense, and total_sales.

Dimension Tables:

Clients: Contact and company details for business partners.

Executives: Internal managers overseeing specific campaigns.

Channels: Marketing mediums (e.g., Social, Email, Search).

CampaignTypes: Categorization of marketing strategies.

Locations & Audiences: Geographic and demographic targeting data.

## 📈 BI Insight (Tableau Dashboard)
The included Tableau dashboard transforms raw data into a visual story:

Global Sales Map: Visualizes "Company Max Sales" by region (notably high activity in North America and Australia).

Engagement Funnel: Comparison of "Sales vs. Engagement" metrics over time.

Leaderboards: "Executive & Team Performance" based on total conversions.

Market Segmentation: Audience performance breakdown (Adults, Female, Male, Seniors, Teens).

## 🛠️ Tech Stack
Database: SQL (Data Modeling, DDL, DML)

Visualization: Tableau Public / Desktop

Design: LucidChart (for ER Diagrams)

Data Source: Excel / CSV


## 🚀 How to Get Started
Design: Create a mock-up diagram (Crow Foot & E-R diagram)
Database Setup: Execute the scripts in the SQL/ folder to build the schema.
Data Load: Import the provided files from the data_source/ folder into Tableau to create a dashboard.
Explore Insights: Open the MarketFlash.twbx file in Tableau to interact with the live performance dashboard.

## Closing Reports
Contains a summarized report.
