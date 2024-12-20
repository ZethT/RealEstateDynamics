# Real Estate Market Dynamics Analysis

## Overview
This project analyzes real estate market dynamics using a dataset of 38,057 real estate transactions across different regions of the United States. The analysis examines relationships between time on market, sales prices, and regional variations to provide insights for real estate professionals and market participants.

## Key Features
- Analysis of time on market correlation with above-list price sales
- Regional market characteristics comparison (Northeast, South, West)
- Property type performance analysis
- Seasonal market patterns evaluation
- Price sensitivity and market duration assessment

## Dataset
The analysis utilizes a comprehensive dataset containing:
- 38,057 real estate transactions
- Multiple property types (Single Family Residential, Condo/Co-op, Multi-Family, Townhouse)
- Regional coverage across Northeast, South, and West regions
- Temporal data capturing seasonal variations
- Detailed metrics on price and market duration

## Key Findings
1. **Time on Market Effect**: Each additional day on market decreases the probability of selling above list price by 0.08 percentage points (p < 0.001)
2. **Regional Variations**:
   - Northeast: 7.4% higher proportion of above-list sales
   - South: 1.8% below baseline for above-list sales
   - West: Consistent with national averages

3. **Property Type Performance**:
   - Single Family Residential: +0.6% probability of above-list sales
   - Condos/Co-ops: -4.4% probability of above-list sales
   - Multi-Family: -1.5% probability of above-list sales
   - Townhouses: +0.8% probability of above-list sales

## Technical Details
- R-squared value: 0.2099
- Adjusted R-squared: 0.2097
- F-statistic: 1261 on 8 and 37975 degrees of freedom
- Statistical significance: p < 2.2e-16

## Dependencies
- tidyverse
- lubridate
- scales
- stats

## Usage
The analysis code is structured in sections:
1. Data loading and cleaning
2. Exploratory data analysis
3. Regional market analysis
4. Property type analysis
5. Statistical modeling
6. Visualization generation

## Limitations
- Model accounts for 21% of variance in sales outcomes
- Interaction effects between variables not fully explored
- Seasonal effects not completely accounted for
- Geographic coverage may limit generalizability

## Future Development
Potential areas for expansion:
- Integration of economic indicators
- Analysis of local market competition
- Property characteristics impact study
- Temporal pattern analysis
- Additional data source integration:
  - Local economic indicators
  - School district ratings
  - Property condition assessments
  - Neighborhood demographics
  - Market competition metrics

