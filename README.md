# Decoding the Resale Value of Gadgets

This repository contains the analysis and visualization code used in the comprehensive study of factors influencing the resale value of used electronic devices. By employing machine learning and data visualization techniques, this project provides actionable insights that can inform manufacturers, resellers, and consumers within the market.

## Project Overview

This project investigates the relationship between device specifications and their normalized used prices. With a rapidly advancing tech market, understanding these dynamics helps various stakeholders make informed decisions.

### Key Features

- **Exploratory Data Analysis (EDA):** Visualizing distribution of device brands, operating systems, and screen sizes.
- **Cluster Analysis:** Using K-Means to identify distinct groups of devices based on features and used prices.
- **Regression Analysis:** Examining relationships between device specs such as RAM, battery capacity, and their resale prices.

## Findings and Visualizations

### Exploratory Data Analysis (EDA)

#### Device Brand Distribution
![Device Brand Distribution](https://github.com/OsamaZahid22/Gadget_Resale_Insights_Exploration/blob/main/distribution.png)
The dataset shows a wide range of device brands with Samsung, Huawei, and LG among the most prevalent. This suggests a market preference which may influence resale values.

#### OS Distribution
![OS Distribution](https://github.com/OsamaZahid22/Gadget_Resale_Insights_Exploration/blob/main/os_distribution.png)
A significant majority of devices run on Android OS, indicating potential market saturation which could impact the demand and resale value of Android devices compared to those with iOS or other operating systems.

#### Screen Size Distribution
![Screen Size Distribution](https://github.com/OsamaZahid22/Gadget_Resale_Insights_Exploration/blob/main/screen_size.png)
Screen sizes center around a common standard with a notable concentration around the 15-inch mark. This could indicate a market standard or preference potentially affecting the resale value of devices with significantly smaller or larger screens.

#### Correlation Matrix of Numerical Features
![Correlation Matrix](https://github.com/OsamaZahid22/Gadget_Resale_Insights_Exploration/blob/main/correlation_heatmap.png)
The heatmap revealed several notable correlations. For example, a strong positive correlation between screen size and weight and between camera quality and release year implies that newer models are likely to have better features. A strong negative correlation between days used and normalized used price confirms the intuitive depreciation of devices over time.

### Cluster Analysis

#### K-Means Clustering
![K-Means Clustering](https://github.com/OsamaZahid22/Gadget_Resale_Insights_Exploration/blob/main/clusters.png)
Using K-Means clustering, we identified distinct groups of devices based on their features and used prices. The optimal number of clusters determined by the elbow method was three. The clusters suggest market segmentation based on device specifications and price points.

### Regression Analysis

#### Internal Memory vs. Price
![Internal Memory vs. Price](https://github.com/OsamaZahid22/Gadget_Resale_Insights_Exploration/blob/main/memory_vs_price.png)
A positive but weak correlation was observed with an R² of 0.03 suggesting other factors are at play.

#### Battery vs. Price
![Battery vs. Price](https://github.com/OsamaZahid22/Gadget_Resale_Insights_Exploration/blob/main/battery_vs_normprice.png)
A linear regression model demonstrated a weak to moderate positive relationship with an R² of 0.35.

#### RAM vs. Price
![RAM vs. Price](https://github.com/OsamaZahid22/Gadget_Resale_Insights_Exploration/blob/main/ram_vs_price.png)
The upward trend of the regression line indicates a positive correlation: as the RAM size increases the normalized used price tends to rise as well. This suggests that devices with higher RAM are likely to be valued more in the resale market. 

## Getting Started




