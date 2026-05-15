# Village Economic Growth Intelligence
## Kritter Software Technologies — Data Assignment

### Project Overview
Identifies Top 100 economically growing districts in India using Census data and multi-indicator scoring.

### Data Source
- Dataset: Census of India 2011 — District Level
- Source: Kaggle Public Dataset (datameet/india-census)
- Coverage: 640 districts, 118 variables

### Scoring Framework
| Indicator | Weight |
|-----------|--------|
| Digital Access | 25% |
| Income Level | 25% |
| Infrastructure | 20% |
| Education | 15% |
| Mobility | 10% |
| Workforce | 5% |

### Key Findings
- #1 Bangalore (Score: 100)
- #2 Mumbai Suburban (Score: 89.94)
- #3 Thane (Score: 83.44)
- Southern states dominate Top 100
- Strong North-South divide identified

### Files in Repository
- Village_Economic_Growth.ipynb — Main notebook
- top100_villages.csv — Final ranked dataset
- village_growth_map.html — Interactive map
- top20_chart.html — Top 20 bar chart
- state_distribution.html — State pie chart
- heatmap.html — Growth drivers heatmap
- Village_Economic_Growth_Intelligence.pptx — Slides

### How to Run
1. Open notebook in Google Colab
2. Upload india-districts-census-2011.csv to Drive
3. Run all blocks sequentially

### Tools Used
Python, Pandas, NumPy, Folium, Plotly, python-pptx

### Limitations
- Census data from 2011
- District level not village level
- Static snapshot not time-series

### With More Time
- NASA VIIRS nighttime lights 2019 vs 2024
- SHRUG dataset for village level data
- Time series growth tracking

## Live Interactive Visualizations
- [🗺️ Interactive Map](https://tusharjoshi07.github.io/village-economic-growth-intelligence/village_growth_map.html)
- [📊 Top 20 Districts](https://tusharjoshi07.github.io/village-economic-growth-intelligence/top20_chart.html)
- [🥧 State Distribution](https://tusharjoshi07.github.io/village-economic-growth-intelligence/state_distribution.html)
- [🔥 Growth Drivers Heatmap](https://tusharjoshi07.github.io/village-economic-growth-intelligence/heatmap.html)

Submitted by: Tushar Joshi | May 2026
