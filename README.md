

# Bakken Shale Analytics – Rystad Energy Case Study

## Overview
This project analyzes well-level production data from the Bakken Shale region to evaluate operational efficiency, production trends, and strategic insights for oil & gas decision-makers. The study focuses on identifying top-performing operators and formations, evaluating cycle times, and analyzing post-peak production across counties using exploratory data analysis and data visualization techniques.

## Objectives
- Scrape and clean well data from the Bakken Shale public repository.  
- Analyze operator-level and formation-level activity patterns.  
- Compute cycle time (spud-to-completion) and 90-day post-peak production metrics.  
- Visualize trends using Power BI dashboards to derive actionable business insights.  

## Tools & Technologies
- **Python**: Data scraping (`BeautifulSoup`), data wrangling (`pandas`, `numpy`), and EDA.  
- **Power BI**: Interactive dashboards for visualizing operator activity, county-level trends, and production insights.  
- **Data Sources**: Public Bakken well databases; structured into 16,000+ records.  

## Key Metrics
- **Cycle Time**: Duration from spud to well completion.  
- **Post-Peak Production**: Aggregate output over the first 90 days after peak production.  
- **Formation & Operator Insights**: Activity analysis across major operators like Continental Resources and formations such as Middle Bakken and Three Forks.  

## Highlights
- 🔍 Identified **Middle Bakken** as the most consistent and high-performing formation.  
- 🏭 Highlighted **Continental Resources** as the most active operator with >1,800 wells.  
- 📈 County 10 emerged with the **lowest average cycle time**, signaling operational efficiency.  
- 🧠 Inferred production bottlenecks and recommended infrastructure focus in underperforming counties.  

## Visuals
The Power BI dashboards include:
- Operator-wise and formation-wise activity breakdown  
- Completion trends over time  
- Cycle time distribution across counties  
- Post-peak production heatmaps and outlier detection  

## Recommendations
- Prioritize investments in **Middle Bakken** for stability and **Three Forks** for growth potential.  
- Monitor **top-performing wells** and counties for future resource allocation.  
- Address inefficiencies in high-cycle-time regions via targeted infrastructure improvements.  
