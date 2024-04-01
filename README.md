# Energy Consumption Analysis

## Introduction:

This dataset contains a refactorized version of the data from the London Data Store, which includes energy consumption readings for a sample of 5,567 London households participating in the UK Power Networks-led Low Carbon London project between November 2011 and February 2014. The data collected from smart meters is primarily associated with electrical consumption.

## Dataset Overview:

- **Total Number of Households:** 5,567
- **Duration:** November 2011 to February 2014
- **Total Records:** 3,510,433
- **Data Size:** 10,266,050,676 bytes (10.27 GB on disk)

## Approach:

1. **Data Compilation:** Combine all blocks into a single dataframe, retaining only relevant columns.
   
2. **Normalization:** Utilize day-level energy consumption data per household to normalize data for inconsistent household counts.
   
3. **Exploratory Data Analysis (EDA):** Investigate relationships between weather conditions, holidays impact, and energy consumption. Create clusters for weather data to add weather identifiers to day-level data.
   
4. **Holiday Indicator:** Incorporate UK holidays data into the day-level data as an indicator.
   
5. **Consumption Segmentation:** Create consumption segmentation to provide energy-saving recommendations based on consumption patterns.
   
6. **Time Series Analysis:**
   - Fit an ARIMAX model.
   - Conduct Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) analysis.
   - Explore Seasonal Decomposition.

## Results:

- The analysis revealed significant insights into the relationship between weather conditions, holidays, and energy consumption patterns.
- Consumption segmentation identified different consumer groups, allowing for tailored energy-saving recommendations.
- The ARIMAX model provided valuable forecasting capabilities for future energy consumption trends.

## Conclusion:

By leveraging the findings from this analysis, energy providers and policymakers can develop targeted strategies to promote energy efficiency and sustainability. Understanding the factors influencing energy consumption patterns is essential for optimizing resource allocation and promoting environmental stewardship.

## Future Directions:

- Continuously monitor energy consumption patterns and adjust strategies accordingly.
- Explore additional datasets to enhance the accuracy and robustness of the analysis.
