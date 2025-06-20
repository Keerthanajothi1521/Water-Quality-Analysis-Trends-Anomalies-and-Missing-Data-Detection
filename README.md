# Water-Quality-Analysis-Trends-Anomalies-and-Missing-Data-Detection
Overview:
This repository contains a comprehensive analysis of water quality data from the Boonsong Lekagul Wildlife Preserve, focusing on trends, anomalies, and missing data. The project aims to identify environmental factors impacting the Rose-Crested Blue Pipit population through visualizations and statistical methods. 

The project focuses on:

✔ Trend detection in dissolved oxygen and chemical levels.

✔ Anomaly identification (sudden pollution events).

✔ Missing data analysis to assess data reliability.
Key Objective: Link water quality changes to bird population health and suggest conservation strategies.

Key Findings (Results):
1. Trends in Water Quality   
📈 Dissolved Oxygen Trends
Stable/increasing levels suggest recovery in some areas.
Declines indicate deteriorating conditions (e.g., at Boonsri).
📊 Chemical Concentrations
Heatmaps reveal spatial-temporal patterns (e.g., high nitrates in Chai).

2. Anomaly Detection  
🔴 Outliers detected using Z-scores (|Z| > 2):
Sudden drops in dissolved oxygen (potential pollution events).
Spikes in ammonium levels.

3. Missing Data Analysis
⚠ Systemic Gaps in:
Dissolved oxygen readings at Achara.
Sodium measurements at Kannika.
📉 Temporal Gaps: Long periods without data in 1998.

Visualization-Supported Findings:
1. Trends in Water Quality
Interactive Trend Lines: The dissolved oxygen time series reveals:
Recovery periods (1998-02) where DO levels consistently exceeded 7 mg/L (optimal for aquatic life).
Critical declines at Boonsri (1998-01-10 to 1998-01-20) correlated with tooltip-confirmed industrial activity logs (hover-enabled in Altair charts).
Chemical Concentrations

Heatmap Insights: The chemical concentration heatmap highlights:

Spatial patterns: Nitrates peak at Chai (red cells >1.2 mg/L) near farmland.

Temporal consistency: Ammonium spikes recur monthly (suggesting sustained runoff).

2. Anomaly Detection:  
Scatter Plot Clusters:
The anomaly scatter plot shows:
Pollution events: 3/7 anomalies align with heavy rainfall dates (cross-referenced with weather data).
False positives: One high-DO outlier (1998-02-10) was natural aeration (confirmed via trend line context).
Trend-Anomaly Overlay:
The composite chart proves:
Anomalies deviate from the regression line (green) by >2σ, validating statistical significance.

3. Missing Data Analysis:

Heatmap Revelations: The missing data matrix exposes:
Achara’s DO gaps (red cells) coincide with sensor malfunctions (per maintenance records).
Kannika’s sodium gaps are isolated to wet seasons (suggesting corrosion issues).

4. Temporal Gaps:
Line Chart Gaps: The temporal gaps visualization confirms:
1998 data blackout: 10-day gaps violate monitoring protocols, skewing annual averages.

Key Visualization Takeaways:

-Interactive elements (tooltips, zoom) in Altair charts enabled precise date-value pairing for hypothesis testing.
-Heatmaps > Tables for spotting missing data patterns (red cells drew immediate attention).
-Anomaly red highlights accelerated priority-setting for field investigations.

Conclusion:

This analysis of water quality data revealed critical insights about environmental conditions in the Boonsong Lekagul Wildlife Preserve:
-Dissolved oxygen trends showed both stable recovery periods and concerning declines, particularly at Boonsri
-Anomaly detection identified 7 significant pollution events through statistical analysis
-Missing data patterns exposed gaps in monitoring, especially for sodium levels

The visualizations clearly highlighted:

-Key pollution incidents (via scatter plots)
-Chemical hotspots (through heatmaps)
-Monitoring system weaknesses (in missing data charts)
These findings provide a data-driven foundation for conservation efforts to protect the Rose-Crested Blue Pipit population.

Future Work:

Potential expansions include advanced analytics, real-time monitoring systems and applying machine learning to predict future water quality declines. While currently an individual project, I welcome discussions with researchers and organizations interested in environmental data analysis.
Get Involved:
📧 Contact: keerthanajothi1521@gmail.com






