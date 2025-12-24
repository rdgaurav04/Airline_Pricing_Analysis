📊 Airline Market Pricing Analysis – Tableau Dashboard
📌 Objective

Build an interactive analytics solution to help airline pricing managers:

Compare fares against competitors

Identify pricing risks and opportunities

Understand customer preference drivers

Monitor pricing trends and market presence

🧠 Business Context

Airline pricing decisions are influenced by competitor behavior, customer preferences, and market dynamics.
This project simulates a real-world scenario where a pricing manager needs fast, actionable insights rather than static reports.

The dashboard is designed to answer:

Are we overpriced or underpriced on specific routes?

How do competitor fares evolve over time?

Do customers pay more for fewer stops and shorter flights?

Is underperformance driven by pricing or by market share?

🗂 Dataset Overview

Key Fields

Routes (Origin–Destination)

Airline (Carrier)

Fare (Price including stopovers)

Number of stops

Flight duration

Departure date

🛠 Data Preparation & Modeling

Created calculated fields for:

Route-level market average fare

Fare difference vs market

Airline classification (John’s airline vs competitors)

Standardized date, duration, and stop fields

Used parameters and filters to enable interactive analysis

Applied LOD expressions for route-level benchmarking

📈 Dashboard Modules
1️⃣ Pricing Competitiveness

Average fare comparison by airline and route

Instantly flags over- and under-priced routes

2️⃣ Price Influencers

Impact of number of stops, flight duration, and departure dates

Interactive filters for scenario-based analysis

3️⃣ Fare Trends

Daily minimum, maximum, and average fare trends

Identifies volatile routes requiring closer monitoring

4️⃣ Outlier Detection

Highlights routes with abnormal pricing behavior

5️⃣ Market Share Analysis

Flight count comparison by airline

Distinguishes pricing issues from capacity disadvantages

6️⃣ Drill-Down Explorer

Parent–child views to move from market overview to route-level detail

💡 Key Insights

Certain routes show persistent overpricing risk relative to competitors

High-volatility routes require stronger pricing governance

Non-stop and shorter-duration flights justify premium pricing

Market share context is essential before adjusting fares

🚀 Tools & Technologies

Tableau Desktop / Tableau Public

Calculated fields & LOD expressions

Dashboard & filter actions

UX-focused dashboard design

🔗 Dashboard Access

Tableau Workbook: https://public.tableau.com/app/profile/gaurav.kumar4299/viz/Tableau_Assingment_airline/AvgFareperAirlineperRoute?publish=yes

Screenshots: Attached
