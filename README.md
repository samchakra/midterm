# Israel-Lebanon Cross-Border Attacks Dashboard

## 1. Reproducibility and Code
This project visualizes the Israel-Lebanon cross-border attacks that occurred from October 7, 2023, to October 11, 2024. The dashboard presents combined attack data, including the distribution of attack types, locations, and trends over time. You can view the public version of this Tableau dashboard through the following link:

[Tableau Public Dashboard Link](#) *(Add your Tableau public link here)*

## 2. Readme File

### Introduction: Domain Problem Characterization
This dashboard explores the ongoing conflict between Israel and Lebanon, focusing specifically on cross-border attacks during the given time frame. The visualizations aim to answer key questions about the intensity and distribution of attacks, highlighting:

- The number of attacks from Israel on Lebanon vs. Hezbollah attacks on Israel.
- The distribution of fatalities on both sides.
- The top locations affected by the conflict.
- The types of attacks occurring most frequently.
- The trends in weekly attack rates.

### What is the problem you want to solve?
The primary problem addressed by this dashboard is understanding the scale and distribution of cross-border attacks and their associated fatalities. The goal is to provide insights into where the majority of attacks are concentrated, what types of attacks are most common, and how these events have unfolded over time. This analysis is crucial for assessing the humanitarian impact and informing future diplomatic and military decisions.

### Data/Operation Abstraction Design
To create this dashboard, I prepared the data by:

1. **Data Collection**: The data was sourced from the Armed Conflict Location & Event Data Project (ACLED) and filtered for events involving Israel and Hezbollah from October 7, 2023, to October 11, 2024.
2. **Data Cleaning**: I created calculated fields to group and combine attack types and fatalities. Additionally, I cleaned the data by ensuring proper geographical mapping for each Admin 2 location in Israel and Lebanon.
3. **Visualization Design**: The data is visualized in the following ways:
   - A **map** with circles representing the number of attacks in each Admin 2 location, sized by total fatalities.
   - A **bar chart** showing the top locations by number of attacks.
   - A **bar chart** representing the distribution of different attack types.
   - A **line chart** showing weekly attack trends for both Israeli and Hezbollah attacks.

### Future Work
I plan to further improve this dashboard by:

- **Adding more detailed filters**: I will include filters for specific types of attacks, time periods, and more granular locations.
- **Incorporating additional data sources**: I aim to integrate data on humanitarian aid and displacement to provide a more comprehensive view of the conflict's impact on civilians.
- **Predictive Analytics**: Future work could involve applying machine learning models to predict future attacks based on past data trends and geopolitical indicators.

