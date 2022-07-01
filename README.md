# Module 9: Surf's Up with Advanced Data Storage and Retrieval

## Overview of the Analysis

### Purpose
Since W. Avy, the investor for our project, requested additional information regarding temperature trends, an analysis was completed to determine if the surf and ice cream shop business would be sustainable year-round. By extracting temperature data from the hawaii.sqlite database for the months of June and December, we can predict the successfulness of the business. 

### Resources
* Jupyter Notebook, Python 3.7.13
* Python Libraries: numpy, pandas, sqlalchemy
* Data Source: [hawaii.sqlite](https://github.com/daniel-sh-au/UofT_DataBC_Module09_surfs_up/blob/main/hawaii.sqlite)
* Challenge Code: [SurfsUp_Challenge.ipynb](https://github.com/daniel-sh-au/UofT_DataBC_Module09_surfs_up/blob/main/SurfsUp_Challenge.ipynb)

## Results
Statistical summaries for June temperatures and December temperatures are shown in the table below: 

| June Temps Summary | December Temps Summary |
| ------------------ | ---------------------- |
| ![Summary_June_Temps.png](https://github.com/daniel-sh-au/UofT_DataBC_Module09_surfs_up/blob/main/Resources/Summary_June_Temps.png) | ![Summary_Dec_Temps.png](https://github.com/daniel-sh-au/UofT_DataBC_Module09_surfs_up/blob/main/Resources/Summary_Dec_Temps.png) |

* From the summary statistics, it can be observed that June has a higher average temperature than December. June has an average temperature of 74.94°F and December has an average temperature of 71.04°F. 
* The temperature in June can range between 64°F and 85°F, which is a 21°F difference. The temperature in December can range between 56°F and 83°F, which is a 27°F difference. 
* In addition to the previous observation, December having the larger temperature range is reflected in the standard deviation of each dataset. December temperatures have a higher standard deviation of 3.75 than June temperatures which have a standard deviation of 3.26. 

## Summary
Although it can be observed that June has higher temperatures than December, the temperature differences are relatively small and only differ by a couple degrees. Therefore, we can conclude that the temperature difference of June vs. December will not significantly affect the surf and ice cream shop business. However, additional analysis should be performed to ensure that W. Avy is making an informed decision. In addition to temperature, precipitation is another factor that will affect the business. If precipitation was found to be significantly higher in December than June, business will decrease in December as visitors are less likely to purchase surfboards and ice cream when it is raining. Also, the analysis can be expanded to determine the temperature and precipitation for additional months, such as March and September. This would provide proper analysis for every season throughout the year. Finally, it may be beneficial to complete this analysis for each individual station to determine which stations have the most credible data. This analysis can establish the optimal location in Oahu for the surf and ice cream shop with the best weather. 