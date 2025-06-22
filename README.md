Analyzing 2024 batters to optimize performance 
⚾ MLB Player KPI & Predictive Ranking Model (2024 Season)
📌 Objective
This project analyzes 2024 season MLB batter statistics to identify Key Performance Indicators (KPIs) that contribute to player success, particularly their expected contribution to team wins. Using advanced metrics such as xWOBA, Barrel Rate, and Hard Hit Rate, the project builds a predictive model and ranks players based on these KPIs.

📊 Dataset
The dataset includes 129 MLB players with ≥500 plate appearances in the 2024 season. It contains the following features:

Basic Info: Player name, ID, season year, plate appearances (PA)

Plate Discipline: Strikeout Rate, Walk Rate, Swing Rate, Whiff Rate

Statcast Metrics: WOBA, Expected WOBA (xWOBA), Barrel Rate, Hard Hit Rate, Sweet Spot %, Average Best Speed, Average Hyper Speed

Source: Statcast & Baseball Savant (2024 season data)

🔍 Exploratory Data Analysis
Key Analyses
Distribution of xWOBA: Helps visualize spread of expected offensive performance.

Swing vs Whiff Rate Scatterplot: Visualizes plate discipline and power potential.

Correlation Matrix: Assesses interrelationships among all numerical features.

Top Performers: Sorted by Expected WOBA to highlight elite contributors.

Over/Under Performers: Compared WOBA vs xWOBA to identify players exceeding or falling short of expectations.

Sample Insights
Top Expected Performers: Aaron Judge, Juan Soto, Shohei Ohtani

Underperformers: Juan Soto (xWOBA far exceeded actual WOBA), Corey Seager

Overperformers: Daulton Varsho, Trea Turner

📈 Visualizations
Distribution plots for key metrics (xWOBA)

Scatterplots for relationships (e.g., Swing Rate vs Whiff Rate)

Correlation heatmap for feature selection

Regression plot for Hard Hit Rate vs Barrel Rate

Tables of Top 10 Overperformers and Underperformers by WOBA differential

🔧 Next Steps
Modeling: Train regression or classification models (e.g., linear regression, random forest) to predict team contribution or WAR based on Statcast metrics.

Ranking System: Develop a composite score combining KPIs to produce a player ranking system.

Validation: Compare predictions to actual WAR or win shares to evaluate accuracy.
