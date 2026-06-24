🏠 Airbnb Performance Dashboard
Power BI | Data Visualization | Business Intelligence
https://github.com/ayushripu/Airbnb-Dashboard---Power-BI-Project/blob/main/Screenshot%25202026-06-25%2520000720.png

📌 Project Overview
An interactive Power BI dashboard analyzing Airbnb booking performance, revenue trends, and occupancy patterns across different property types, neighbourhoods, and time periods. This dashboard provides actionable insights for property managers, hosts, and business analysts to optimize pricing strategies and maximize revenue.

🎯 Business Objectives
Track key performance metrics including revenue, occupancy, and cancellation rates

Analyze booking trends by property type and neighbourhood

Monitor seasonal patterns in revenue and bookings

Identify high-performing locations and property types

Support data-driven pricing and marketing decisions

📊 Key Performance Indicators (KPIs)
Metric	Value
💰 Total Revenue	$258,986
💵 Average Nightly Rate	$263.99
📈 Occupancy Rate	46.97%
❌ Cancellation Rate	23.08%
🧩 Dashboard Features
Feature	Description
🔍 Interactive Filters	Filter by room type (Entire home, Hotel room, Private room, Shared room) and year (2023–2026)
📊 KPI Cards	High-level metrics displayed prominently for quick insights
📉 Revenue Trends	Monthly and yearly revenue analysis
🗺️ Neighbourhood Analysis	Total bookings by neighbourhood (Bronx, Crown Heights, East Village, Staten Island, Brooklyn)
🏷️ Property Insights	Analysis by accommodates, amenities, bathrooms, and more
📈 Visualizations Included
1. Total Revenue by Month & Year
Track revenue fluctuations across January – December

Filter by year: 2024, 2025, 2026

Identify peak and off-peak seasons

2. Total Bookings by Neighbourhood
Compare booking volumes across:

Bronx

Crown Heights

East Village

Staten Island

Brooklyn

Identify high-demand locations

3. KPI Summary Cards
Total Revenue: $258,986

Average Nightly Rate: $263.99

Occupancy Rate: 46.97%

Cancellation Rate: 23.08%

🗂️ Data Model
The dashboard is built on a star schema data model:

Table Name	Description
dim_date	Calendar attributes (year, month, day)
dim_host	Host-related information
dim_location	Geographic details (city, state, neighbourhood, zipcode)
dim_property	Property attributes (accommodates, bathrooms, amenities, base price)
Measure Table	Calculated measures using DAX (Revenue, Occupancy, Cancellation Rate)
🛠️ Tools & Technologies
Tool	Purpose
Power BI Desktop	Data modeling, DAX calculations, and visualization
Power Query	Data extraction, transformation, and loading (ETL)
DAX (Data Analysis Expressions)	Custom measure creation
Excel / CSV	Source data files

📁 Repository Structure
text
Airbnb-Dashboard---Power-BI-Project/
│
├── AirbnB.pbix                          # Power BI dashboard file
├── Screenshot_2026-06-25_000720.png     # Dashboard preview
├── README.md                            # Project documentation
│
├── data/
│   ├── dim_date.csv
│   ├── dim_host.csv
│   ├── dim_location.csv
│   └── dim_property.csv
│
└── docs/
    └── DAX_Measures.md                  # Custom DAX documentation
🚀 How to Use
Prerequisites
Power BI Desktop (Version: November 2023 or later)
Download here

Installation & Usage
Clone the repository:

bash
git clone https://github.com/ayushripu/Airbnb-Dashboard---Power-BI-Project.git
Navigate to the project folder and open the AirbnB.pbix file.

Refresh data if necessary (ensure CSV files are in the correct path).

Interact with filters and visuals to explore insights.

💡 Sample Business Questions This Dashboard Answers
Which room type generates the highest revenue?

How does occupancy vary by neighbourhood?

What are the peak booking months?

Which properties have the highest cancellation rates?

How does average nightly rate impact occupancy?

📊 Key Insights
Revenue Trends
Peak revenue months: Identified through monthly trend analysis

Year-over-year growth: Compare 2024, 2025, and 2026

Neighbourhood Performance
Brooklyn shows highest booking volumes

Bronx and Staten Island have lower booking counts

Property Performance
Entire homes generate higher revenue

Private rooms show better occupancy rates

🤝 Contributing
Contributions, issues, and feature requests are welcome!

Fork the repository

Create a feature branch:

bash
git checkout -b feature/YourFeature
Commit your changes:

bash
git commit -m "Add your feature"
Push to the branch:

bash
git push origin feature/YourFeature
Open a Pull Request

📬 Contact
Ayush Kumar
🐙 https://github.com/ayushripu
🔗 https://www.linkedin.com/in/ayush-kr37/

📄 License
Distributed under the MIT License. See LICENSE for more information.

⭐ Acknowledgments
Data sourced from publicly available Airbnb datasets

Built with ❤️ using Microsoft Power BI

