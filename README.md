## Overview
This project is part of the Google Data Analytics Certificate through Coursera. It focuses on analyzing bike-share data to derive actionable insights that can help convert casual riders into annual subscribers. The company is fictious and it is called Cyclistic, data are real. 

---

## Objectives
1. Analyze usage trends of casual riders and subscribers.
2. Identify peak seasons, days, and stations for casual rider usage.
3. Recommend marketing strategies to increase subscriptions.
4. Generate data visualizations and provide actionable insights.

---

## Dataset
- **Source**: [Coursera].
- **Description**: Contains rental details such as trip duration, user type, and station data.
- **Note**: Ensure data privacy and adhere to terms of use for public datasets.

---

## Analysis Steps
### 1. Data Cleaning
- Removed null values and duplicate records.
- Standardized trip duration to cap outliers.
- Extracted useful columns for analysis.

### 2. Exploratory Data Analysis (EDA)
- Weekday vs. Weekend trends.
- Seasonal and hourly patterns.
- Station-based user distribution.

### 3. Revenue and Retention Analysis
- Calculated total and average revenue for casual riders.
- Compared revenue from casual riders to subscribers.
- Assessed customer retention rates.

---

## Key Observations
1. **Usage Trends**:
   - Casual riders peak during weekends and summer.
   - Subscribers have consistent usage throughout the year.
2. **Revenue Insights**:
   - Subscribers contribute the majority of revenue due to annual plans.
   - Casual riders show higher trip durations but lower frequency.
3. **Geographic Distribution**:
   - Key stations for casual riders: *Streeter Dr & Grand Ave*, *Lake Shore Dr & Monroe St*.
   - Subscriber hotspots: *Theater on the Lake*.

---

## Recommendations
1. **Target Marketing**:
   - Focus on weekends during spring and summer.
   - Use geo-targeted campaigns around popular casual rider stations.
2. **Promotional Offers**:
   - Weekend-exclusive subscription discounts.
   - Incentives for casual riders with frequent high-value trips.
3. **Subscriber Retention**:
   - Reward loyal subscribers with credits for additional rides.
   - Promote referral programs to attract more casual riders.

---

## Visualizations
The project includes:
- **Weekday vs Weekend Usage**: Highlights peak times for casual riders.
- **Trip Duration Distribution**: Comparison of casual and subscriber trip lengths.
- **Revenue Trends**: Monthly revenue breakdown for casual riders and subscribers.

---

## Tools Used
- **R**: Data cleaning, analysis, and visualization.
- **ggplot2**: Data visualization.
- **Kaggle**: Dataset and notebook hosting.
- **GitHub**: Repository for project files.

---

## Repository Structure
```bash
.
├── data/               # Cleaned dataset (if shareable)
├── scripts/            # R scripts for analysis
├── visualizations/     # Exported charts
├── README.md           # Project overview
```

---

## Next Steps
1. Integrate findings into a marketing campaign.
2. Validate insights with updated data.
3. Automate reporting using R or Python.

---

## Acknowledgments
- Google Data Analytics Certificate.
- Divvy Bikes for providing the data.
- Coursera for hosting the capstone project.
