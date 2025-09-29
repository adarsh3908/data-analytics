# Airbnb Listing Analysis

## Project Overview
This project analyzes Airbnb listing data to understand pricing patterns, neighborhood trends, and market dynamics in Paris. The analysis focuses on how regulatory changes in 2015 affected the Airbnb market.

## Dataset
- **File**: `Listings.csv` (not included - please provide your own Airbnb dataset)
- **Source**: Airbnb listing data (available from various open data sources)
- **Size**: Large dataset containing comprehensive Airbnb listing information
- **Note**: Due to file size limitations, please obtain your own Airbnb listings dataset
- **Key Fields**: 
  - `host_since`: Date when host joined Airbnb
  - `neighbourhood`: Paris neighborhood where listing is located
  - `city`: City name (filtered for Paris)
  - `accommodates`: Number of guests the listing can accommodate
  - `price`: Price per night in Euros

## Analysis Focus Areas

### 1. Geographic Analysis
- Average listing prices by Paris neighborhood
- Identification of premium vs. budget neighborhoods
- Spatial distribution of listings

### 2. Accommodation Capacity Analysis
- Price variations based on guest capacity
- Market segmentation by accommodation size
- Value analysis for different group sizes

### 3. Temporal Market Trends
- Evolution of new host registrations over time
- Price trends and market maturation
- Impact of 2015 regulations on the market

### 4. Regulatory Impact Analysis
- Pre/post 2015 regulation comparison
- Market dynamics: fewer hosts, higher prices
- Long-term market stabilization patterns

## Key Findings

### Neighborhood Insights
- **Premium Areas**: Élysée district shows highest average prices
- **Price Variation**: Significant differences across Paris neighborhoods
- **Market Segmentation**: Clear distinction between luxury and budget areas

### Temporal Trends
- **2015 Regulation Impact**: Notable decrease in new host registrations
- **Price Evolution**: Gradual increase in average prices over time
- **Market Maturation**: Stabilization following regulatory changes

### Market Dynamics
- **Supply Constraint**: Regulations led to reduced new host entry
- **Price Response**: Limited supply resulted in higher average prices
- **Market Balance**: New equilibrium established post-regulation

## Technical Implementation

### Data Processing
- Pandas for data manipulation and analysis
- Date parsing for temporal analysis
- Data filtering and grouping operations

### Visualization
- Matplotlib for custom dual-axis plots
- Seaborn for enhanced statistical visualizations
- Bar charts for comparative analysis

### Analysis Techniques
- Groupby operations for aggregated insights
- Time series resampling for temporal trends
- Query-based data filtering

## Files Structure
```
airbnb listing analysis/
├── README.md
├── AirBnB Listing Analysis.ipynb
└── Listings.csv (please provide your own dataset)
```

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn

## Usage
1. Ensure all required libraries are installed
2. **Obtain an Airbnb listings dataset** and place it as `Listings.csv` in this folder
3. The dataset should include columns: host_since, neighbourhood, city, accommodates, price
4. Run the Jupyter notebook cells sequentially
5. Explore the generated visualizations and insights

## Future Enhancements
- Expand analysis to other cities
- Include seasonal pricing patterns
- Add machine learning price prediction models
- Incorporate additional listing features (amenities, reviews, etc.)

---
*This analysis demonstrates the practical application of data science techniques to understand real-world market dynamics and regulatory impacts.*