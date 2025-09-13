# 🏠 Airbnb NYC Market Analysis: Data-Driven Host Strategy Optimization


## 📊 Project Overview

This project provides comprehensive insights into NYC's Airbnb market dynamics, focusing on **pricing optimization** and **host business strategies**. Through interactive Tableau visualizations, we analyze how hosts can maximize profitability by understanding the relationships between property features, amenities, pricing strategies, and market demand across different NYC neighborhoods.

### 🎯 Core Research Question
> "How can Airbnb hosts optimize their pricing, occupancy, and competitive positioning to maximize profitability across different NYC neighborhoods?"

## 🔍 Key Contributions

My analysis focused on two critical areas:

### 1. **Pricing Trends Analysis**
- Developed comprehensive pricing models examining factors influencing Airbnb rates
- Created multi-dimensional visualizations showing price variations across:
  - Property types (entire homes, private rooms, shared spaces)
  - Neighborhoods and districts
  - Host characteristics (experience, response rates, superhost status)
  - Seasonal patterns and market trends

### 2. **Host Business Strategies**
- Analyzed the **impact of amenities on pricing power** - identifying which amenities command premium rates
- Investigated how **property types influence pricing strategies** and occupancy rates
- Examined host behavior patterns including:
  - Multi-listing vs. single-listing pricing approaches
  - Superhost pricing premiums
  - Impact of instant booking on rates

## 📈 Key Findings

### Pricing Insights
- **Premium Amenities**: Entertainment features (TV, streaming) can increase nightly rates by 15-20%
- **Property Type Impact**: Entire homes command 2.5x higher rates than shared rooms
- **Location Premium**: Manhattan listings average 40% higher rates than outer boroughs
- **Superhost Advantage**: Superhosts successfully charge 8-12% premium over regular hosts

### Strategic Recommendations
1. **Amenity Investment**: Focus on high-ROI amenities (workspace, kitchen, entertainment)
2. **Property Selection**: Prioritize entire home/apartment listings in high-demand neighborhoods
3. **Host Optimization**: Pursue Superhost status for pricing power and occupancy benefits
4. **Dynamic Pricing**: Implement seasonal and event-based pricing strategies

## 🛠️ Technical Implementation

### Data Sources
- **Primary Dataset**: [Airbnb Listings Dataset (NYC)](https://www.kaggle.com/datasets/mysarahmadbhat/airbnb-listings-reviews)
- **Secondary Dataset**: [Inside Airbnb Reviews](https://insideairbnb.com/get-the-data/)
- **Sample Size**: 30,963 listings across 218 NYC neighborhoods

### Key Variables Analyzed
```
Host Metrics:
- host_response_time, host_acceptance_rate
- host_is_superhost, host_total_listings_count
- host_identity_verified

Listing Features:
- property_type, room_type, accommodates
- amenities, price, instant_bookable
- review_scores_rating, review_scores_value

Location Data:
- neighbourhood, district, city
- latitude, longitude
```

## 🔗 Live Demo

[[View Interactive Dashboard on Tableau Public]([url](https://public.tableau.com/app/profile/anh.che/viz/DataStory_FinalProject_DataNexus/AirbnbNY#1))](#)
## 📊 Visualization Gallery

### Pricing Analysis Dashboards
1. **Price Distribution Analysis**
   - Box plots comparing prices across room types and property categories
   - Geographic heatmaps showing pricing density by neighborhood

2. **Host Strategy Visualizations**
   - Scatter plots: Relationship between amenities count and nightly rates
   - Bubble charts: Multi-listing hosts' pricing strategies
   - Bar charts: Price premiums by property type

3. **Market Trends**
   - Time series: Pricing evolution across neighborhoods
   - Stacked bars: Room type distribution and pricing by district

## 🚀 Getting Started

### Prerequisites
- Tableau Desktop 2020.4+ or Tableau Reader (free)
- .rar extraction software

### Installation
```bash
1. Clone the repository
   git clone https://github.com/yourusername/airbnb-nyc-analysis.git

2. Extract the Tableau workbook
   Extract Airbnb_NY_Story_Dashboard.rar

3. Open in Tableau
   Double-click Airbnb_NY_Dashboard.twb
```

### Dashboard Navigation
The interactive dashboard includes:
- **Pricing Trends**: YoY analysis, neighborhood comparisons
- **Host Strategies**: Amenity impact, property type analysis
- **Market Dynamics**: Demand patterns, competitive positioning
- **Recommendations**: Data-driven insights for hosts

## 💡 Business Impact

This analysis provides actionable insights for:

### Airbnb Hosts
- **Optimize pricing** based on property features and market position
- **Strategic amenity investments** for maximum ROI
- **Competitive positioning** within neighborhoods

### Investors
- **Identify high-value property types** and neighborhoods
- **Understand market dynamics** for investment decisions
- **Predict revenue potential** based on property characteristics

## 📁 Project Structure
```
airbnb-nyc-analysis/
├── data_and_visualizations/
│   └── Airbnb_NY_Dashboard.twb
│   └── data
├── analysis/
│   ├── pricing_analysis.docx
├── final_presentation.pdf
└── README.md
```

---
