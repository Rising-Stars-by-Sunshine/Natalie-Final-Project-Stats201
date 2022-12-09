# Predicting the share of the population in the largest city using machine learning

## Project information
- **Author**: Natalie Aramendia, Computation & Design, 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Final Project for [STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second)](https://ms.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: A special thanks to professor Luyao Zhang for providing code and resources for completing this project. I would also like to thank Haoyang Yu for helping me set up my virtual machine and providing insightful peer feedback. 

- **Project Summary**: 
 Background/Motivation:
Changes in a country's economic health frequently lead to changes in population migration and distribution. This was evident with COVID-19, where large cities saw great numbers of residents leaving in search of cheaper and more spacious housing (Martel 2020). This project hopes to predict the future share of the population living in a country's largest city from the national GDP. For this project we will use historical data on Seoul, South Korea from 1960-2021 because of the rapid economic change Korea has undergone in the last few decades.
 
 
Research Question: 
How can we predict changes in the share of the urban population in a country's largest city from national GDP?
 
Data Source:
Data for GDP: GDP (current US$) - Korea, Rep. | Data (worldbank.org)
Data for the share of the population in the largest city: Urbanization - Our World in Data
 
Methodology:
For this project, different machine algorithms (Random Forest, Multi-layer, and Ridge regression classifiers) will be applied to predict the future population of Seoul using time series data from the past 5 years. Causal Inference will then be used to understand if changes in GDP are related to changes in population. The X will be GDP, Y population, and Z will be the date of January 20, 2020 - the date of the first covid case in Seoul, South Korea (Cha 2020). The determined relationship will then be used to predict future population data.
 
Results:
We expect to find that future GDP can be used to predict the future share of the population living in the largest city using the relationship between historical GDP data and historical population data.
 
Intellectual Merits and Practical impacts:
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
| [Process data](https://github.com/Rising-Stars-by-Sunshine/Natalie-Final-Project-Stats201/blob/main/code/Natalie_Final_Process.ipynb)) |
| [Analyze data](https://github.com/Rising-Stars-by-Sunshine/Natalie-Final-Project-Stats201/blob/main/code/Natalie_Final_Analyze.ipynb)|



## Spotlight


## More about the Author
- image

Natalie is a sophomore at Duke Kunshan University. She is studying Computation & Design, with a track in Social Policy, and concentration in Urban Design. She hopes to work in urban analytics & tech, and use machine learning to help solve urban issues. 

- Final reflections 

[how to apply a various machine learning methods to solve social science issues?]

## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

