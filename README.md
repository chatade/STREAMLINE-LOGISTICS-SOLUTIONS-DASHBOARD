# Streamline Logistics Solutions — Delivery Performance Dashboard
## Project Overview
Streamline Logistics Solutions is a growing supply chain and logistics company (est. 2023) known for reliable, nationwide delivery services. Despite strong operational ambitions, the company was facing serious delivery performance issues — long delivery and delay times, high order backlogs, and rising negative customer feedback — that put its reputation for efficiency and customer satisfaction at risk.

This project analyzes delivery operations data and builds an Excel-based Delivery Performance Dashboard to uncover the root causes behind these issues and translate them into concrete operational recommendations.

## Business Problem
Streamline Logistics needed to understand:
- Why delivery times and delays were exceeding acceptable thresholds
- Which vehicle types, routes, and days were driving inefficiency
- How order backlog and in-progress volume were impacting completion rates
- What was driving the high rate of negative customer feedback

##  Tools Used
- **Microsoft Excel** — data analysis and dashboard build, including:
  - `COUNTIFS` and `DATEDIF` formulas to flag orders pending beyond SLA
  - Conditional formatting to prioritize aging orders
  - Slicers for filtering backlog by route, driver, and order age
  - Line charts and trendlines for backlog and forecast visualization
- **PowerPoint** — executive summary and insights presentation (`Streamline_Logistics_Final.pptx`)

##  Key Performance Indicators
Category	Metric	Value	Target / Benchmark Context
Volume	                    Total Orders              	1,500	        Baseline dataset volume
Speed & Timing	            Avg. Delivery Time	        152 mins	    Exceeds urban delivery target thresholds
Speed & Timing	            Avg. Delay Time	           14.5 mins	    Indicates dispatch & routing friction
Efficiency & Accuracy	      Delivery Efficiency	       90.50%	        Moderate overall efficiency score
Efficiency & Accuracy	     On-Time Delivery Rate	     3.00%	        Critical bottleneck (97% experience delays)
Customer Sentiment	       Negative Feedback Rate	     35.00%	        Driven primarily by delivery delays


## Key Insights

**Delivery Backlog**
- Daily backlog stayed above 85 orders throughout the analysis period, peaking at 106 before trending down to 86 — a persistent, unresolved volume issue rather than a one-off spike

**Vehicle Performance**
- Average delivery time varies by vehicle type: Truck B is slowest (155 min), Bike C mid-range (152 min), Van A fastest (149 min)
- Delay times are similar across vehicle types (~14–15 min), meaning longer delivery times aren't driven by proportionally higher delays — it's a routing/assignment issue

**On-Time Performance**
- Only 3% of deliveries were on time, with 97% delayed — a systemic issue pointing to routing, dispatch timing, or traffic forecasting failures rather than isolated incidents

**Forecasting & Volume**
- Daily deliveries ranged from 148–156 before forecasting, with forecasts closely tracking actuals (154–160 range), validating the forecasting model
- Sept 12 hit a peak of 160 deliveries, the highest in the period

**Order Completion**
- 767 orders remained in progress vs. 733 completed — a 34-order gap suggesting bottlenecks or uneven route distribution rather than a fully resolved pipeline

**Delay & Sentiment Correlation**
- Average delays ranged from 51–79 minutes, well above acceptable thresholds
- Days with the highest delays (Sept 3, 4, 6) directly aligned with spikes in negative sentiment, confirming delivery time as a key driver of customer experience
- Negative feedback (529) outweighs both Neutral (490) and Positive (481) responses, revealing a real perception gap in service quality

## Recommendations
- Set a daily backlog target of ≤ 50 orders within 30 days, using Excel filters and conditional formatting to prioritize aging orders
- Reassign vehicles by route type: Van A for short-haul/urban, Truck B for consolidated long-haul, limit Bike C to low-density or off-peak zones
- Implement dynamic routing with real-time traffic data and predictive ETAs to address the 97% delay rate
- Use forecast data to pre-allocate drivers and vehicles ahead of predicted high-volume days
- Set a target to reduce average delivery delay to ≤ 30 minutes within 30 days
- Launch proactive customer communication (ETA updates, service recovery credits) and post-delivery satisfaction surveys to close the sentiment gap


## ⚙️ How to View This Project
1. Clone or download this repository
2. Open the Excel workbook to explore the interactive dashboard (slicers, KPI cards, trend charts)
3. Refer to `Streamline_Logistics_Final.pptx` for the executive summary and slide-by-slide insights

## Screenshots
https://github.com/chatade/STREAMLINE-LOGISTICS-SOLUTIONS-DASHBOARD/blob/main/Streamline%20Logistics%20Dashboard.xlsx
https://github.com/chatade/STREAMLINE-LOGISTICS-SOLUTIONS-DASHBOARD/blob/main/Streamline%20Logistics%20Final.pptx
