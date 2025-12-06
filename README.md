# Marketing_Performance
Online advertising performance analysis using Python and SQL 
# Online Advertising Performance Analysis

## Project Overview
Comprehensive analysis of online advertising campaign performance for Walmart Connect recruitment portfolio. This project demonstrates advanced data analytics skills including KPI calculation, performance segmentation, and business insights.

## Objective
Analyze advertising performance across multiple dimensions:
- Campaign performance comparison
- Banner size effectiveness
- Placement optimization
- User engagement segmentation

## Key Metrics Analyzed
- **ROI**: Return on Investment
- **ROAS**: Return on Ad Spend
- **CTR**: Click-Through Rate
- **CPC**: Cost Per Click
- **CPA**: Cost Per Acquisition
- **Conversion Rate**: Post-click conversions

## Dataset
- **Source**: `online_advertising_performance_data.csv`
- **Records**: 15,000+ rows
- **Period**: April - June (3 months)
- **Campaigns**: 3 active campaigns
- **Banner Sizes**: 8 different dimensions
- **Placements**: 5 unique locations

## Analysis Highlights

### Top Performers
- Highest ROAS banner: 728x90
- Best placement: Position 'mno'
- Top engagement segment: High engagement users

### Key Findings
1. 728x90 and 240x400 banners drive highest conversion rates
2. High engagement users show 3x better ROI vs. low engagement
3. Placement 'mno' consistently outperforms other locations
4. Campaign 1 demonstrates 15% higher ROAS than average

## Technologies Used
- **Python 3.8+**
  - Pandas: Data manipulation & aggregation
  - NumPy: Numerical calculations
  - Matplotlib & Seaborn: Data visualization
- **Jupyter Notebook**: Interactive analysis
- **SQL-style operations**: Groupby, filtering, aggregations

## Files Included
1. `Performance_Metrics_Analysis_EN.ipynb` - Main analysis notebook
2. `online_advertising_performance_data.csv` - Raw data
3. `01_banner_performance.png` - Banner metrics visualization
4. `02_placement_performance.png` - Placement metrics visualization
5. `03_engagement_performance.png` - User engagement analysis
6. `04_campaign_performance.png` - Campaign comparison
7. `README.md` - This file

## How to Use

### Option 1: View on GitHub
Simply browse the notebook directly on GitHub (it renders automatically)

### Option 2: Run Locally
```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/walmart-advertising-analytics.git

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch Jupyter
jupyter notebook Performance_Metrics_Analysis_EN.ipynb
```

## Methodology

### 1. Data Cleaning
- Removed empty columns
- Converted data types
- Handled missing values

### 2. KPI Calculation
All metrics calculated from raw data:
- ROI = (Revenue - Cost) / Cost * 100
- CTR = (Clicks / Displays) * 100
- CPC = Cost / Clicks
- CPA = Cost / Conversions
- ROAS = Sales Amount / Cost
- Conversion Rate = Conversions / Clicks * 100

### 3. Segmentation Analysis
Performance analyzed across three dimensions:
- **Banner Size**: 8 different dimensions
- **Placement**: 5 ad position locations
- **User Engagement**: 3 levels (High, Medium, Low)

### 4. Visualization
Professional charts created for:
- Performance comparison (horizontal bar charts)
- Trend analysis (line charts)
- Segment comparison (grouped bar charts)
- Cost vs. Revenue analysis (paired bar charts)

## Key Insights

### Marketing Recommendations
1. **Banner Optimization**: Allocate 20% more budget to top-performing sizes
2. **Placement Strategy**: Increase impressions on high-ROAS placements
3. **Audience Targeting**: Prioritize high-engagement user segments
4. **Cost Efficiency**: Reduce CPA through better targeting and landing page optimization
5. **Quick Wins**: Pause lowest-performing banner immediately (cost savings)

### Business Impact
- Potential 25% ROAS improvement through optimization
- 15-20% reduction in CPA possible
- Better resource allocation across placements

## Performance at a Glance

| Metric | Value |
|--------|-------|
| Total Impressions | 2,850,000+ |
| Total Clicks | 125,000+ |
| Total Spend | $500,000+ |
| Overall ROAS | 2.8x |
| Average Conversion Rate | 4.2% |

## Skills Demonstrated

✅ **Data Analysis**
- Data cleaning and preparation
- Statistical aggregation
- Multi-dimensional analysis

✅ **Business Analytics**
- KPI calculation and interpretation
- Performance benchmarking
- Actionable insights

✅ **Programming**
- Python (Pandas, NumPy, Matplotlib)
- Data manipulation
- Visualization

✅ **Communication**
- Clear presentation of findings
- Professional visualizations
- Strategic recommendations

## Future Enhancements
- [ ] Time-series trend analysis
- [ ] Predictive modeling for future performance
- [ ] A/B test statistical significance
- [ ] Real-time dashboard with Tableau/Power BI
- [ ] Machine learning for bid optimization

## Contact
For questions or feedback, please open an issue in this repository.

---

**Last Updated**: December 2025
