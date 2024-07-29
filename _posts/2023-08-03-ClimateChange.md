---
layout: post
title:  "Analysis of Climate Change Data in Iran (2000-2021)"
date:   2023-11-22
excerpt: "Using ERA5-Land and Xarray"
project: true
tag: [Climate Change, Geology, Python]
comments: false
feature: assets/img/1692022656335.jfif
---

**Analysis of Climate Change Data in Iran (2000-2021) Using ERA5-Land and Xarray**

**July 2023 - August 2023**

[Climate change](https://github.com/aradfarahani/Climate-Change) is an increasingly critical concern in today's world. One of the significant impacts of climate change is the warming of the climate and the earlier melting of snow, which compromises natural water storage. Estimating snow cover is crucial for climate change studies and effective water resource management. Snow cover directly affects climate dynamics and supports the water supply for over one billion people globally.

For this project, we utilized the ERA5-Land reanalysis dataset to analyze climate change data in Iran from 2000 to 2021. ERA5-Land provides high-resolution information on surface variables at approximately 9km grid spacing, covering the period from 1950 to 2-3 months before the present. This dataset offers hourly data, making it an invaluable resource for detailed climate analysis.

To handle and analyze this extensive dataset, we used Xarray, an open-source Python package. Xarray provides a powerful toolkit and data structures for working with multi-dimensional labeled arrays, making it ideal for climate change analysis.

### Objectives

1. **Assess Climate Warming Trends**: Analyze temperature data to identify warming trends over the past two decades.
2. **Snow Cover Estimation**: Estimate snow cover changes and their impact on water resources.
3. **Precipitation Patterns**: Examine changes in precipitation patterns and their implications for water availability.
4. **Data Visualization**: Create visualizations to effectively communicate the findings.

### Methodology

1. **Data Collection**: We downloaded the ERA5-Land monthly averaged reanalysis dataset for Iran from 2000 to 2021.
2. **Data Processing**: Using Xarray, we processed the dataset to extract relevant variables such as temperature, precipitation, and snow cover.
3. **Trend Analysis**: We performed statistical analyses to identify trends and anomalies in the data.
4. **Visualization**: We used Python libraries such as Matplotlib and Seaborn to create visual representations of the data.

### Findings

- **Temperature Trends**: The analysis revealed a significant warming trend in Iran over the past two decades, with average temperatures increasing steadily.
- **Snow Cover Changes**: There was a noticeable decline in snow cover, particularly in the mountainous regions, which has implications for water storage and supply.
- **Precipitation Patterns**: Changes in precipitation patterns were observed, with some regions experiencing increased rainfall while others faced prolonged dry spells.

![1693444038279](https://github.com/user-attachments/assets/84cf252b-e8de-44a9-bc23-6affd6e3964e)
![image](https://github.com/user-attachments/assets/b234e9b9-28ee-4a7b-83db-f3cc56d5e151)
![image](https://github.com/user-attachments/assets/1507d8f7-02b9-4b25-abd7-773da64735f6)
![image](https://github.com/user-attachments/assets/02c36b3a-b45b-4a47-8091-eb809df12ae9)
![image](https://github.com/user-attachments/assets/48bc2f6f-6c21-41e8-bf4d-47886769bc16)
![image](https://github.com/user-attachments/assets/66917916-2ca2-4794-8dac-9531610e0375)

### Conclusion

This project highlights the importance of using high-resolution reanalysis datasets like ERA5-Land and powerful tools like Xarray for climate change analysis. The findings underscore the urgent need for effective climate change mitigation and adaptation strategies to manage water resources and ensure sustainability.
