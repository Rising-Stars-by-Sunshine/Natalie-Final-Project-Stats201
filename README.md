# Predicting the share of the population in the largest city using machine learning

## Project information
- **Author**: Natalie Aramendia, Computation & Design, 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Final Project for [STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second)](https://ms.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: A special thanks to professor Luyao Zhang for providing code and resources for completing this project. I would also like to thank Haoyang Yu for helping me set up my virtual machine and providing insightful peer feedback. 

- **Project Summary**: 

**Background/Motivation:**
Changes in a country's economic health frequently lead to changes in population migration and distribution. This was evident with COVID-19, where large cities saw great numbers of residents leaving in search of cheaper and more spacious housing (Martel 2020). This project hopes to predict the future share of the population living in a country's largest city from the national GDP. For this project we will use historical data on Seoul, South Korea from 1960-2021 because of the rapid economic change Korea has undergone in the last few decades.
 
 
**Research Question:**
How can we predict changes in the share of the urban population in a country's largest city from national GDP?
 
**Data Source:**

[Data for GDP](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=KR)

[Data for the share of the population in the largest city](https://ourworldindata.org/urbanization)
 
**Methodology:**
For this project, different machine algorithms (Random Forest, Multi-layer, and Ridge regression classifiers) will be applied to predict the future population of Seoul using time series data from the past 5 years. Causal Inference will then be used to understand if changes in GDP are related to changes in population. The X will be GDP, Y population, and Z will be the date of January 20, 2020 - the date of the first covid case in Seoul, South Korea (Cha 2020). The determined relationship will then be used to predict future population data.
 
**Results:**
We expect to find that future GDP can be used to predict the future share of the population living in the largest city using the relationship between historical GDP data and historical population data.
 
**Intellectual Merits and Practical impacts:**
Previous research had modeled urban growth concerning other factors, for example, net construction, but has not been researched concerning GDP. Seoul, South Korea, will be the case study used; This project can later be used to predict population distribution for other global cities and applied in future research when analyzing how economic factors drive human movement and density.


## Table of Contents
- data
- code
- spotlight
- more about the author
- references



| Data |
|------|
| [Queried data](https://github.com/Rising-Stars-by-Sunshine/Natalie-Final-Project-Stats201/tree/main/data/Queried_Data) |
| [Processed data](https://github.com/Rising-Stars-by-Sunshine/Natalie-Final-Project-Stats201/tree/main/data/Processed_Data) |

| Code |
|------|
| [Process data](https://github.com/Rising-Stars-by-Sunshine/Natalie-Final-Project-Stats201/blob/main/code/Natalie_Final_Process.ipynb) |
| [Analyze data](https://github.com/Rising-Stars-by-Sunshine/Natalie-Final-Project-Stats201/blob/main/code/Natalie_Final_Analyze.ipynb)|



## Spotlight

![image](https://user-images.githubusercontent.com/89420894/206804346-6f24b526-bd4c-44a7-8eb7-2e64d5f997d8.png)
**Figure 1: Project poster**

Source: created using [canva](https://www.canva.com/design/DAFT0JQBBEk/f5DFuYQpuyg7bQZilRcDuQ/edit)

Figure 1 is the poster for this project. It displays the research question, data source, methodology, results, and contribution to literature. 

![image](https://user-images.githubusercontent.com/89420894/207613942-26c948d8-92b3-40ae-b35d-a79bda024e83.png)

**Figure 2: Contribution to literature (using [whimsical](https://whimsical.com/contribution-to-lit-2Wvf1uC1WdG8gzZf3y7pqU))**

<img width="1075" alt="image" src="https://user-images.githubusercontent.com/89420894/206879450-a56c2b6a-124d-46a3-989b-898ec2161874.png">

**Figure 3: Share of Korean urban population living in Seoul**

Figure 3 is shows the share of Korean urban population living in Seoul (Korea's largest city) from 1960 to 2021. This visualization is a scatterplot; the Y-axis shows the population as a percentage and the X-value shows the year. We can see that the share of Korean urban population in Seoul was steadily increasing in the decade between 1960 to 1970. After peaking in 1970, the share of population has been decreasing ever since.  

![image](https://user-images.githubusercontent.com/89420894/206804541-f46e430d-c895-4c96-8560-794dcdb9d0af.png)

**Figure 4: Confusion matrix from random forest classifier**

Source: data sourced from [Our World in Data](https://ourworldindata.org/urbanization) and matrix created with [Scikit Learn](https://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees)

Figure 4 is a confusion matrix for the random forest classifier algorithm for population prediction, using 5 year times series analysis. This is useful to see how suitable this algorithm is for the problem. Each box shows the number of occurences of True Positive, False Positive, False Negative, and True Negative. The legend on the right shows the counts of observations, with yellow being more observations and purple meaning fewer. The x-axis is predicted label and the y-axis is true label. 0 represents a decrease in population and 1 represents an increase in population. The precision is TP/(TP+FP) = 9/9 = 1. The recall is TP/(TP+FN) = 9/10 = 0.9.

references:  https://www.v7labs.com/blog/confusion-matrix-guide






## More about the Author
<img src="./Image/tomate.jpg" width="250" />



Natalie is a sophomore at Duke Kunshan University. She is studying Computation & Design, with a track in Social Policy, and concentration in Urban Design. She hopes to work in urban analytics & tech, and use machine learning to help solve urban issues. Natalie saw the variety of methods used to solve similar social  problems and the scope to which machine learning can be applied to with this project. She learned about how to use time series data to predict the future, the variables needed, and how to effectively communiate ideas with visualizations. She also learned about confusion matrix and how it can be used to understand the different algorithms performed. 

## References

### Data Source
Data for GDP: https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=KR

Data for the share of the population in the largest city: https://ourworldindata.org/urbanization

### Code Source

[rising-Stars-by-Sunshine/stats201-profile](https://github.com/Rising-Stars-by-Sunshine/stats201-profile/tree/main/code)

### Articles

Cha, Victor. “A Timeline of South Korea’s Response to COVID-19.” Csis.org, 2020, www.csis.org/analysis/timeline-south-koreas-response-covid-19.

Martel, Eric. “Are People Really Fleeing Cities because of COVID? Here’s What the Data Shows.” Fortune, 1 Dec. 2020, fortune.com/2020/07/17/people-leaving-cities-coronavirus-data-population-millennials-marriage-families-housing-real-estate-suburbs/.

### Literature

Kim, Yuna, et al. “Machine Learning Application to Spatio-Temporal Modeling of Urban Growth.” Computers, Environment and Urban Systems, vol. 94, June 2022, p. 101801, 10.1016/j.compenvurbsys.2022.101801.
https://www.sciencedirect.com/science/article/pii/S019897152200045X

Kutty, Adeeb A., et al. “Urban Resilience and Livability Performance of European Smart Cities: A Novel Machine Learning Approach.” Journal of Cleaner Production, vol. 378, Dec. 2022, p. 134203, 10.1016/j.jclepro.2022.134203.
https://www.sciencedirect.com/science/article/pii/S0959652622037751
 
Ron-Ferguson, Nathan, et al. “Leveraging Machine Learning to Understand Urban Change with Net Construction.” Landscape and Urban Planning, vol. 216, Dec. 2021, p. 104239, 10.1016/j.landurbplan.2021.104239.
https://www.sciencedirect.com/science/article/pii/S0169204621002024



