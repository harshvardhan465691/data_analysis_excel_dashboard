#  Road Accident Analysis

 dashboard link (https://1drv.ms/x/c/7b97ba1b95b18ec7/EXsjxZ53XoJLk3udGBCX38wBML5rvJwac0zWxpvWrR9QEQ?e=kmOChl)
## overview
I developed an interactive Road Accident Dashboard in Excel to analyze accident data from 2021–2022 containing 3.07 million rows and 21 fields. The goal was to provide insights into accident trends, casualty severity, and high-risk factors based on client requirements
## Problem Definition
Road accidents have become a serious issue, leading to thousands of deaths and injuries every year. The raw data about these accidents is huge and difficult to understand, which makes it hard for authorities to find out the main reasons and patterns behind them. Questions like “Which vehicles are most involved in accidents?”, “Are more accidents happening in urban or rural areas?”, “Do most accidents happen because of bad weather or normal conditions?” often remain unanswered because the information is not presented clearly.
To solve this problem, I created an interactive Excel dashboard that takes millions of accident records and turns them into simple, easy-to-read visuals. This helps in identifying accident trends, casualty severity, road conditions, and other key insights that can actually support better decision-making for road safety.
Road Accident Data Analysis Project
# 1. Business Requirement
The client wanted to create a Road Accident Dashboard for years 2021 and 2022 to analyze accident data and gain actionable insights.
Requirements:
Primary KPIs:
Total casualties after accidents.
Casualty breakdown by severity (Fatal, Serious, Slight) with percentages.
Maximum casualties by type of vehicle.
Secondary KPIs:
Casualties with respect to vehicle type.
Monthly trend comparing Current Year (CY) vs Previous Year (PY).
Maximum casualties by road type.
Distribution of casualties by road surface.
Relationship between casualties by area/location (Urban/Rural) and day/night conditions.
# 2. Dataset Metadata
File Extension: .xlsx
Rows: 3.07 million
Fields: 21
Data Period: 2021–2023
Key columns included: Accident Date, Vehicle Type, Area (Urban/Rural), Road Type, Road Surface, Light Condition, Severity, Casualty Count.
# 3. Data Cleaning & Preparation
Steps performed:
Removed missing/duplicate records.
Standardized categorical fields (e.g., "Urban" vs "urban").
Created calculated fields for:
Casualty Severity %
Monthly Trend (CY vs PY)
Aggregated KPIs by vehicle, area, surface, and light conditions.
Filter panel created for year selection and Urban/Rural segmentation.
# 4. Dashboard Design
The dashboard contains the following sections
Top KPIs Panel:
Total Casualties, Fatal, Serious, Slight, Car-specific casualties.
Casualties by Vehicle Type: Cars, Vans, Bicycles, Motorcycles, Buses, Agricultural vehicles.
Monthly Trend (CY vs PY): Accident trend line comparing 2021 vs 2022.
Casualties by Road Type: Single carriageway, Dual carriageway, Roundabout, One-way street.
Casualties by Road Surface: Dry, Wet, Frost/Snow.
Casualties by Area: Rural vs Urban.
Casualties by Light Condition: Daylight vs Dark.
Interactive Filters: Year (2021–2023), Urban/Rural toggle, Time period selection.
# 5. Insights Derived
Casualty Severity
Fatal: 7,135 (1.7%)
Serious: 59,312 (14.2%)
Slight: 351,436 (84.1%)
👉 Majority of accidents result in slight injuries.
Vehicle Type
Cars contribute 81.8% of casualties (333,485) → highest risk category.
Vans (33,472), Bicycles (23,466), and Buses (12,708) follow.
Road Type
Single Carriageways cause the maximum casualties (309.7k).
Dual Carriageway (67.4k) and Roundabout (26.8k) much lower.
Road Surface
Dry roads: 279,445 casualties.
Wet roads: 115,261 casualties.
👉 Most accidents happen on normal/dry conditions, not due to bad weather.
Area Analysis
Urban: 255.9k (61%)
Rural: 162k (39%)
👉 Higher traffic density in urban areas → more accidents.
Light Condition
Daylight: 305k (73%)
Dark: 113k (27%)
👉 Accidents are mostly daytime-related due to high traffic flow.
Monthly Trend
Accident numbers peak in January & November.
Lowest in December, likely due to holidays or restricted movement.
# 6. Recommendations
Car Safety Focus: Since cars account for majority accidents, stricter enforcement of traffic laws, seatbelt usage, and speed limits should be emphasized.
Single Carriageway Improvements: Add road dividers, better signage, and stricter lane enforcement.
Urban Traffic Management: Improve junction control, roundabouts, and congestion management.
Awareness Campaigns: Focus on daytime driver attention & fatigue management.
Seasonal Awareness: Extra monitoring in January and November.
# 7. Tools & Techniques
Excel: Pivot Tables, Slicers, Charts, Conditional Formatting, Interactive Dashboard.
Visualization: Donut charts, bar charts, line charts, KPIs cards.
Data Size Handling: Optimized Excel performance for 3M+ rows.
